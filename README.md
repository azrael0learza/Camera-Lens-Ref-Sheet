# Camera-Lens-Ref-Sheet
A scene prompt guide for generators.


## Master Shot & Lens Matrix
| Shot / Lens | Prompt Template | What It Does |
| :-- | :-- | :-- |
| **Anamorphic** (cinematic scope) | `Cinematic wide shot of [subject] [action] in [setting], anamorphic lens look, 2.39:1 frame, oval bokeh from [background lights], soft horizontal flares, gentle edge softness, filmic color grade.` | Anamorphic lenses optically squeeze a wide field onto the sensor, and the image is stretched back out in post. The signature traits are oval bokeh, horizontal streak flares, and soft edge falloff. 2.39:1 is a common delivery ratio for anamorphic work, not part of the lens itself. |
| **Wide-angle** (18-28mm) | `Low-angle wide shot of [subject] in [setting], 20mm lens, deep depth of field, strong leading lines from [architecture or terrain] converging toward the subject.` | Exaggerates depth so foreground objects loom and distances stretch. Good for scale, environment, and isolation. Works especially well with one-point perspective (symmetrical, lines converging to a center). |
| **Ultra-wide rectilinear** (12-16mm) | `Ultra-wide shot of [subject] in [setting], 14mm rectilinear lens, dramatic perspective, stretched edges, straight lines stay straight.` | Extreme perspective and stretching near the frame corners, but straight lines remain straight. Use for dramatic interiors and towering environments. |
| **Fisheye** (8-15mm) | `Fisheye lens shot of [subject] in [setting], 10mm circular distortion, straight lines bend into curves, [high or low] angle.` | Curved projection that bends straight lines into arcs. Suits dream sequences, unease, claustrophobia, or energetic music-video looks. Not the same as ultra-wide. |
| **Standard** (35-50mm) | `Medium shot of [subject] [action] in [setting], 35mm lens, natural perspective, moderate depth of field, [light source] lighting.` | Close to natural human perspective. Reads as documentary, grounded, and honest. A safe default. |
| **Portrait telephoto** (85-135mm) | `Close-up portrait of [subject] [expression or action], 85mm lens, wide aperture, shallow depth of field, [background element] compressed into smooth bokeh.` | Compresses space and separates the subject from the background. Typical real-world apertures are f/1.4 to f/2 at 85mm and f/2 to f/2.8 at 100-135mm. |
| **Long telephoto** (200mm+) | `Telephoto shot of [subject] in [setting], 200mm lens, heavy compression, stacked layers of [background elements], softly blurred foreground.` | Flattens distance so far-apart layers appear stacked. Great for voyeuristic, surveillance, or wildlife looks. |
| **Macro** | `Extreme close-up macro of [small detail of subject], 100mm macro lens, razor-thin focus plane, visible surface texture, [light source] lighting.` | Reveals fine texture at very close range. Depth of field becomes extremely thin, so only a sliver is sharp. Good for tension, craft, and micro-detail. |
| **Tilt-shift** | `High-angle shot of [setting] with [subject], tilt-shift lens look, selective focus band, miniature-model effect, saturated colors.` | Blurs the top and bottom of the frame so a real scene looks like a tiny model. Works best from above. |
| **Profile** (introspection) | `Medium profile shot of [subject] looking toward [point of interest], side view, 50mm lens, shallow depth of field, [background] softly blurred or streaked with motion.` | Splits the frame between the subject and what they are looking at. Conveys contemplation, longing, or anticipation. |
| **Over-the-shoulder / dirty frame** | `Over-the-shoulder shot of [subject], framed past a blurred [foreground element] at the edge of the frame, 35mm lens, layered depth.` | A soft foreground obstacle adds depth and makes the viewer feel like a hidden observer. |
| **Reflection** (duality) | `Close-up of [subject]'s reflection in [reflective surface], 85mm lens, reflection in sharp focus, physical subject soft or in silhouette.` | Shorthand for hidden selves, secrets, or inner conflict by prioritizing the reflection over the physical subject. |


## Shot Sizes, Angles & Composition

### Shot Size
| Term | Prompt Phrase | Effect |
| :-- | :-- | :-- |
| Establishing | `wide establishing shot of [setting] with [subject] small in frame` | Sets place and scale |
| Full shot | `full-body shot of [subject]` | Whole figure plus surroundings |
| Medium shot | `medium shot of [subject], waist up` | Conversational, balanced |
| Medium close-up | `medium close-up of [subject], chest up` | Intimate but still contextual |
| Close-up | `close-up of [subject]'s face` | Emotion and expression |
| Extreme close-up | `extreme close-up on [subject]'s eyes` | Intensity, detail, tension |

### Camera Angle
| Term | Prompt Phrase | Effect |
| :-- | :-- | :-- |
| Eye level | `eye-level shot` | Neutral, relatable |
| Low angle | `low-angle shot looking up at [subject]` | Power, scale, threat |
| High angle | `high-angle shot looking down at [subject]` | Vulnerability, smallness |
| Bird's-eye | `overhead bird's-eye view of [subject] in [setting]` | Pattern, layout, detachment |
| Worm's-eye | `worm's-eye view from ground level` | Towering, dramatic |
| Dutch angle | `dramatic Dutch angle, tilted horizon` | Unease, disorientation |
| POV | `first-person point-of-view shot` | Immersion |

### Composition Cues
- **Rule of thirds**: `subject placed on the left third, open space to the right`
- **Centered symmetry**: `perfectly symmetrical, centered composition`
- **Leading lines**: `lines converging toward the subject`
- **Frame within a frame**: `subject framed through [doorway, window, arch]`
- **Negative space**: `small subject, vast empty [sky, wall, field] around them`
- **Layered depth**: `distinct foreground, midground, and background layers`


## Lens Physics & Camera Keywords

### Reliable Keywords
| Goal | Phrase |
| :-- | :-- |
| Shallow depth | `wide aperture, shallow depth of field, creamy bokeh, soft background` (adding f/1.8 can help as a hint) |
| Deep focus | `deep depth of field, f/11, sharp from foreground to background` |
| Vintage lens character | `subtle chromatic aberration, soft vignette, gentle halation, slight edge softness` |
| Lens flare | `soft lens flare from [light source]` |
| Motion blur | `panning shot, sharp subject, motion-blurred [background]` |
| Frozen action | `frozen mid-motion, crisp suspended droplets or dust` |
| Light trails | `long exposure, streaking light trails` |

## Lighting & Atmosphere
| Look | Phrase |
| :-- | :-- |
| Midday sun | `bright midday sun, hard shadows, high-key lighting` |
| Golden hour | `warm golden hour glow, long shadows, soft rim light` |
| Blue hour | `cool blue hour twilight, deep blue sky, glowing practical lights` |
| Overcast | `soft overcast light, even shadows, muted tones` |
| Window light | `soft directional light from a window on one side of [subject]` |
| Backlit | `strong backlight, glowing rim light around [subject]` |
| Silhouette | `[subject] in silhouette against a bright [sky, window, screen]` |
| Low-key | `low-key lighting, deep shadows, single [light source], chiaroscuro` |
| Volumetric | `volumetric light rays through haze, floating dust or mist` |
| Neon | `colored neon light from [signs or screens], magenta and cyan glow, high contrast` |
| Practical lights | `lit by visible lamps, [candles, streetlights, screens] in frame` |
| Rhythmic light | `passing [lights] casting moving bands of light across [subject]` |

## Color Grade & Film Look
| Look | Phrase |
| :-- | :-- |
| Clean modern digital | `clean neutral color, natural skin tones, crisp detail` |
| Cool and moody | `cold teal and slate tones, desaturated, cinematic` |
| Teal and orange | `teal and orange color grading, warm skin tones, cool shadows` |
| Nostalgic 8mm | `Super 8mm film look, warm faded tones, light leaks, heavy film grain` |
| Classic Technicolor | `Technicolor-style saturation, rich color, deep blacks` |
| Modern 35mm film | `shot on 35mm film, natural grain, soft highlight rolloff` |
| Bleach bypass | `bleach bypass look, desaturated, high contrast, gritty` |
| Black and white | `black and white, high contrast, fine film grain` |
| Pastel | `soft pastel palette, low contrast, airy` |

## Aspect Ratio Cheat Sheet
| Ratio | Feel | Midjourney Parameter |
| :-- | :-- | :-- |
| 2.39:1 | Anamorphic widescreen | `--ar 12:5` (about 2.4:1) |
| 16:9 | Standard video | `--ar 16:9` |
| 3:2 | Classic photo | `--ar 3:2` |
| 4:3 | Retro, academy-like | `--ar 4:3` |
| 1:1 | Square, social | `--ar 1:1` |
| 4:5 | Portrait, social | `--ar 4:5` |
| 9:16 | Vertical phone | `--ar 9:16` |


## Camera Movement (Video Gen)
| Move | Phrase | Effect |
| :-- | :-- | :-- |
| Push-in | `slow push-in toward [subject]` | Builds focus and tension |
| Pull-out | `slow pull-out revealing [setting]` | Reveals context |
| Pan / tilt | `slow pan left` / `tilt up to [subject]` | Follows or reveals |
| Tracking | `tracking shot alongside [subject]` | Energy and momentum |
| Orbit | `camera orbits around [subject]` | Dimensional, dramatic |
| Crane / drone | `rising crane shot over [setting]` | Scale and scope |
| Handheld | `handheld camera, subtle shake` | Raw, urgent realism |
| Rack focus | `rack focus from [foreground element] to [subject]` | Shifts attention |
| Dolly zoom | `dolly zoom on [subject]` | Disorientation, realization |
| Whip pan | `fast whip pan to [subject]` | Sudden transition |
| Locked-off | `static locked-off camera` | Stillness, formality |

**Template:** `[Subject] [action] in [setting], slow push-in, 35mm lens, shallow depth of field, [light source] lighting, [color grade].`


## Common Failures & Fixes
| Problem | Fix |
| :-- | :-- |
| Malformed hands | Avoid intricate hand poses, hide hands in pockets or frame edges, or keep gestures simple |
| Garbled text or signs | Avoid readable text, or add text in post |
| Extra or duplicated subjects | Specify 'a single \[subject\]' and keep the prompt short |
| Over-stylized, plastic look | Use `--style raw`, drop extra adjectives, add 'natural' and 'documentary' |
| Contradictory instructions | Don't combine opposites (fisheye with straight lines, deep focus with heavy bokeh) |
| Muddy lighting | Name one main light source and its direction |
| Generic faces | Add specifics: age range, expression, clothing, build |
| Look doesn't match | Change one variable at a time and compare |

**Negative prompt starter** (where supported): `blurry, low resolution, extra limbs, deformed hands, watermark, text, oversaturated`


## Worked Examples (One Template, Different Scenes)
**Portrait telephoto template:** `Close-up portrait of [subject] [action], 85mm lens, wide aperture, shallow depth of field, [background] compressed into smooth bokeh, [light], [grade].`

- **Market scene:** `Close-up portrait of a vendor arranging fruit, 85mm lens, wide aperture, shallow depth of field, crowded stalls compressed into smooth bokeh, warm late-afternoon sun, modern 35mm film look.`
- **Sci-fi scene:** `Close-up portrait of an astronaut checking a wrist console, 85mm lens, wide aperture, shallow depth of field, glowing control panels compressed into smooth bokeh, cool blue practical light, clean modern digital color.`
- **Wilderness scene:** `Close-up portrait of a hiker resting on a ridge, 85mm lens, wide aperture, shallow depth of field, distant mountains compressed into smooth bokeh, golden hour backlight, teal and orange grade.`


## Prompt-Building Checklist
1. Who or what is the subject, and what are they doing?
2. Where are they?
3. How close is the camera (shot size), and from where (angle)?
4. What lens look do you want (wide, standard, telephoto, macro)?
5. What is the main light source and mood?
6. What color grade or film look fits?
