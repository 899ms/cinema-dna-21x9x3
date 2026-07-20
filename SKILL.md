---
name: cinema-dna-21x9x3
description: >-
  将人物、空间、产品、建筑、原始图片或简单故事转换为真实电影感的 21:9 单帧或默认 3 张连续叙事三联镜头提示词。Use when the user asks for cinematic image prompts, film still prompt design, 21:9 triptych narrative shots, scene staging, cinematic lighting/color/composition, director DNA translated into concrete visual language, or converting people/spaces/products/buildings into movie-like image prompts.
---

# CINEMA DNA 21:9 x 3

Convert a user's subject, story, person, space, product, building, or reference image into cinematic image prompts. Default to three independent 21:9 shots that feel like consecutive frames from one real film scene.

Do not simply apply a named-director filter. Translate style into concrete visual language: staging, lens distance, light source, color structure, spatial depth, character state, material realism, and narrative tension.

## Prime Directive

The goal is not to generate "images that look cinematic." The goal is to generate three frames that feel cut from the same real film sequence: one unified world, clear shot functions, real camera imaging, and a small readable narrative.

## PATCH v3 Hard Rules

Use these rules whenever generating, editing, testing, or reviewing three-shot cinematic image sets.

### Three-Shot Narrative Contract

Each triptych must have distinct functions:
- Shot 1 | Establish World: establish time, place, weather, spatial order, the character's distance from the world, and the primary atmosphere. Environment information must exceed character information. The frame should feel like an opening shot.
- Shot 2 | Establish Relationship: advance the event. Show a concrete narrative action such as approaching, delivering, discovering, observing, missing, waiting, making eye contact, or forming a relation across space. It cannot be just another angle of Shot 1.
- Shot 3 | Leave Aftertaste: reduce and condense information. Use back view, reflection, partial body, hand gesture, empty room, half-open door, read letter, object left behind, or distant departing figure. It should feel unresolved, as if the story continues after the frame.

Avoid triptych repetition:
- No three similar wide shots.
- No three shots of the same person simply standing.
- No three complete frontal spaces.
- No repeated composition skeletons.
- No style variations without event progression.
- No triptych without narrative information gaps.

Each triptych must vary at least four of these:
- Shot scale.
- Camera position.
- Foreground treatment.
- Information density.
- Light concentration.
- Composition skeleton.
- Subject-to-environment ratio.
- Emotional density.

### On-Site Camera Language

Every shot must place the camera physically in the scene. Specify at least five:
- Focal length.
- Camera height.
- Camera-to-subject distance.
- Subject frame-height percentage.
- Foreground obstruction or no obstruction.
- Main spatial axis.
- Light source.
- Focus point.
- Character sightline.
- Where the key information sits: foreground, middle ground, or background.

Default lens allocation:
- Shot 1: 24-28mm, medium-deep DOF, person 5%-15%, strong spatial order.
- Shot 2: 32-50mm, person 20%-35%, relationship clearer, layered by doors, columns, glass, rails, windows, curtains, table, crowd, or architecture.
- Shot 3: 50-85mm, or a changed wide observation position. Use compression, reflection, partial framing, less information, stronger residue.

### True 21:9 Use

21:9 is not a crop. It must serve:
- Horizontal spatial relationships.
- Distance between character and environment.
- Left/right information contrast.
- Corridor, road, water, columns, city edge, grassland, mountain ridge, train car, table, or shoreline narrative.
- Negative space and off-screen extension.

Avoid:
- Ordinary images cropped wide.
- Centered subject with empty side filler.
- Empty frames without blocking.

### Real Film Imaging

Cinematic feel must come from staging, real spatial order, camera position, light source, color body, physical materials, and optical imperfection. It must not come from generic "cinematic" adjectives, random teal/orange, strong grain, heavy flare, fake contrast, or a film-filter overlay.

Default imaging:
- Real narrative feature-film still.
- Dense blacks with preserved shadow detail.
- Soft highlight roll-off.
- Slight local halation.
- Extremely subtle real optical fringing.
- Medium-low microcontrast.
- Moderate sharpness, never digital razor sharp.
- Fine natural uneven grain.
- Slight edge softness.
- Air in the image, but not dirty blur.

Optical imperfections are allowed only when extremely restrained and local: high-contrast edges, highlights, window frames, lamp glass, architecture edges, silhouettes, wet reflections, metal edges. Never use cyber RGB split or make aberration the main visual.

### Composition Rules

Each triptych must satisfy at least three:
- At least one shot has meaningful foreground obstruction.
- At least one shot frames through a door, glass, columns, rail, curtain, furniture, crowd, or window.
- At least one shot makes the subject part of the space rather than the dominant object.
- At least one shot places key information in the background.
- At least one shot uses offset composition or controlled imbalance.
- At least one shot uses meaningful negative space.

Choose and mix two composition modes:
- Strong Order Composition: central axis, one-point perspective, geometric order, institutional pressure. Best for ritual space, power rooms, corridors, palaces, train cars, offices, hotels, and Wes Anderson-like precision. Symmetry must have story pressure and one meaningful break.
- Controlled Imbalance Composition: slight offset, foreground intrusion, imperfect horizon or perspective, in-progress feeling. Best for youth, memory, Venice, grassland, transition scenes, observation, and Eastern spatial poetics.

### Bright Subject Anti-Drift

For blue sky, grass, youth, campus, red/white buildings, sunlight, clean positive subjects:
- Bright does not mean animated, high-saturation, sweet commercial, school promo, idol-drama poster, travel ad, or real-estate brochure.
- Keep live-action film still realism, real sky and clouds, grass with air and irregularity, used architecture, event-driven human action, restrained color, real exposure, soft highlights, and light grain.
- Red can be a visual accent, not plastic saturated dominance.
- Ban: cartoon look, animation look, campus advertising, propaganda/promo look, sweet glossy look, oversaturated blue sky/green grass, excessive clarity, plastic skin, studio-commercial look.

### Director Direction Patches

Wes Anderson-like direction must not be reduced to purple plus symmetry. It needs: strong central order, calm faces, theatrical space, specific prop narration, unified palette, precise but not dead composition, people placed inside a geometric stage. Useful micro-narratives: delivering a letter, waiting for an elevator, silence in a reception room, a hotel-lobby pause, one action changing inside a strict color system.

King Hu / Eastern wuxia direction must not become game poster, costume-drama beauty still, or xianxia fantasy. It needs: emptiness, moisture, landscape and architecture co-narration, curtains, doors, corridors, bridges, water, bamboo shadows, layers, small but present figures, low-saturation red/dark clothing accents, more stillness than action, looking/being looked at, separation and threshold tension. Ban: strong combat, VFX sword aura, fantasy glow, game feel, xianxia atmosphere, costume-promo poster.

Ancient, ruin, mythic, coast, mountain, desert, and other scenic subjects must not become beautiful location photography. Add an explicit second narrative force early: watcher, pursuer, child, smoke signal, empty seat, abandoned tool, blocked doorway, unlit hearth, changed object, or trace of absence. Place the camera in a constrained practical position and make the landscape or ruin act as a social, ritual, or moral machine rather than scenery.

### Hidden Plot And Output Check

Before generation, internally answer:
- What second-to-second story does the triptych cover?
- Why is the character here?
- What happened just before Shot 1?
- What may happen after Shot 3?
- What information changes from shot to shot?
- What is the unresolved hook of Shot 3?

Before final output, check:
- Are the three shots truly different?
- Do they have clear functional division?
- Is there a small story?
- Does Shot 3 leave residue?
- Is the camera physically placed?
- Are foreground, middle ground, and background meaningful?
- Does it avoid poster, ad, comic, CG, game, promo, and filter-only cinema?
- Does bright subject matter avoid sugar and propaganda?
- Does Eastern material avoid xianxia/game/costume-promo drift?
- Does Wes-like material avoid becoming only symmetry and color?

## PATCH v4 Anti-AI Film Frame Rules

Use this patch whenever an output feels AI-like, oily, over-detailed, dirty in the wrong way, lens-poor, or conventionally stacked.

### Anti-AI Image Discipline

The frame should look like a captured film frame with limits, not a prompt trying to impress.

Reduce:
- Excess visible detail, decorative clutter, ornamental debris, smoke everywhere, and material callouts in every corner.
- Perfectly legible objects across foreground, middle ground, and background at the same time.
- Oily amber highlights, glossy wet surfaces, beauty-filter halation, artificial rim light, and render-like reflections.
- Over-designed production stills where every prop tells the viewer it is important.

Prefer:
- One readable story clue, one secondary clue, and everything else allowed to fall into shadow, blur, grain, occlusion, or mundane emptiness.
- Underplayed practical locations: ordinary rooms, hallways, vehicles, streets, courts, offices, classrooms, clinics, stations, hotel rooms, rehearsal spaces.
- Negative space, blank walls, empty floor, dull ceiling, dead corners, and boring real surfaces when they make the shot feel captured rather than designed.
- Human timing over visual richness: half-turns, missed gestures, interrupted looks, waiting, leaving, reaching too late, watching from the wrong side of glass.

Prompt rule:
- Cap each shot at 2-3 concrete scene details plus the camera position and light source.
- Do not list too many material textures. Choose only the material that matters to the story.
- Do not ask for "rich detail", "highly detailed", "intricate", "epic", "dramatic", "volumetric", "beautiful", or "masterpiece".

### Lens-Texture Calibration

When lens texture feels weak, specify a capture medium instead of more "cinematic" adjectives.

Choose one capture substrate per set:
- 35mm release print: soft gate, print density, mild color breathing, medium-low microcontrast, fine uneven grain.
- 16mm television transfer: softer resolution, chunkier but still natural grain, slight color bleed, imperfect exposure, practical documentary immediacy.
- VHS / old broadcast capture: lower fidelity, scan softness, luma noise, color bleed, unstable blacks, only for low-fi or archival scenes.
- MiniDV / early digital video: harsh small-sensor practical light, slight interlace/edge harshness, limited dynamic range, only for 1990s/2000s realism.
- Surveillance / CRT / monitor rephotograph: geometry distortion, screen texture, glare, black crush, only when the story needs a mediated viewpoint.
- Long-lens film compression: shallow but not creamy DOF, heat shimmer or window distortion, compressed figures, restrained detail.
- Wide/fisheye witness POV: optical distortion justified by the camera being physically trapped inside a vehicle, doorway, crowd, checkpoint, locker room, corridor, or hiding place.

Rules:
- Lens defects must be optical and local, not global effects.
- Let blacks crush a little, but keep enough shadow structure for story.
- Let highlights clip or bloom slightly when practical sources would do so.
- Keep faces less perfect: natural texture, darker skin values, no commercial fill, no porcelain smoothness.
- Grain should not be "more"; it should be uneven and attached to exposure, strongest in shadows and midtones.

### Controlled Dirt, Not Dirty AI

Dirty realism means selective imperfection, not adding grime everywhere.

Use only one dominant imperfection family:
- Dust and dry scratches.
- Rain and wet reflection.
- Smoke and low-output lamps.
- Fluorescent institutional grime.
- Broadcast/video noise.
- Fogged glass or condensation.
- Sun-faded fabric and chipped paint.

Avoid combining too many: dust + smoke + scratches + fog + dirt + rain + lens flare in one frame usually reads as AI.

### Unconventional Triptych Rhythm

A triptych does not need to be three equal, polite establishing/medium/detail images. It should feel like a few frames stolen from an edit.

Allowed external layouts after generating separate 2.39:1 frames:
- Classic equal stack: 1:1:1, use only when the sequence is balanced.
- Held opening: 1.25:0.9:0.85, Shot 1 larger, useful for world-first cinema.
- Impact middle: 0.85:1.3:0.85, Shot 2 larger, useful when a decision or action is the center.
- Aftertaste ending: 0.85:0.9:1.25, Shot 3 larger, useful when residue matters most.
- Uneven memory strip: 0.7:1.2:0.75 with 6-16px black breathing gaps, useful for subjective or archival sequences.
- Broken surveillance strip: 1:1:1 with one frame slightly lower contrast or softer, useful for mediated POV.

Never generate these layouts inside the image model. Generate separate frames first, then post-process externally.

Triptych variation rules:
- At least one shot may be a mediated frame: window reflection, TV/CRT image, surveillance angle, phone/video playback, mirror, porthole, car glass, or view through blinds.
- At least one shot should be less complete than expected: partial face, empty room, object left behind, too much ceiling, occluded body, or important action in a corner.
- Do not always place the emotional climax in Shot 3. Sometimes Shot 2 is the only dramatic frame and Shot 3 is nearly empty.
- Black spacing between images may be 0-16px. Use spacing as edit rhythm, not decoration.

### Reference-Learned Frame Grammar

From film-study contact sheets, extract these useful patterns:
- A row can mix a distant room, a face fragment, and an object/empty space without explaining everything.
- Strong sequences often include one "boring" transitional shot that makes the others feel real.
- Low-fi or imperfect media frames can feel more cinematic than polished film-still prompts.
- Color can shift shot-to-shot within one set if motivated by place or medium: cold exterior -> warm interior -> dark residue, or fluorescent room -> daylight window -> CRT blue.
- Composition may be awkward in a controlled way: too much headroom, subject cut by window edge, figure placed at the far margin, horizon slightly low, or action partially hidden.

### V4 Self-Check

Before final output, reject a set if:
- Every frame looks expensive, beautiful, and fully designed.
- Every frame is equally detailed.
- Every frame uses the same clean 21:9 composition.
- Dirt is spread uniformly across the image.
- The lens substrate is not visible.
- The sequence would look the same if shuffled.
- The images feel like prompt illustrations rather than frames captured from a scene.

### V4 Validated Defaults

Use these defaults when the user asks to test, randomize, or improve cinematic realism:
- Write shorter prompts than v3: one capture substrate, one color body, one story clue, one secondary clue, one camera position, one light source.
- Prefer 35mm release print, 16mm television transfer, long-lens film compression, or mediated glass/monitor views over generic "cinematic still" language.
- Use one intentionally underplayed or "boring" shot in each triptych: empty lounge, plain pier, blank corridor, closed door, empty seat, dead ceiling, or object left behind.
- Let composition become controlled-awkward when useful: too much ceiling, subject at a far edge, action hidden through a window, object in foreground but person missing.
- Use uneven external stitching by default when the user complains that the triptych feels conventional.

Validated triptych rhythms:
- Hotel / room looking out: held opening `1.25:0.9:0.85`.
- Sea / departure / loss: aftertaste ending `0.85:0.9:1.25`.
- Ritual / refusal / ceremony: impact middle `0.85:1.3:0.85`.

Validated subject recipes:
- Hotel interior looking at African savanna: yellow ochre window light, dark hotel interior, off-road vehicle and animals as distant story clue, avoid safari-tourism beauty.
- Very blue sea with large ship: restrained blue body, long-lens compression, missed departure clue, plain pier or floating ticket, avoid postcard travel imagery.
- Eastern ritual symmetry: strict axial staging, saffron/yellow field, deep red accent, black ceremonial shadows, refused seal or closed box, avoid costume-poster gloss.
- Refined Go master and boy: if the user references Zhang Yimou's `Shadow`, use stable ink-wash monochrome, rain on silk screens, strict central table axis, same room/light/costumes across all shots, sparse board allowed, wrong stone / empty cushion as story clue, avoid luxury tea-room, macro stones, color-temperature jumps, or costume-drama polish.
- Real F1 track rain: overcast daylight, wet asphalt black, desaturated racing white, tiny red track-safety accent, speed from panning blur and tire spray, avoid neon/cyberpunk/showroom gloss.
- Chinese county absurd realism: 16mm or old broadcast texture, cement gray body with bus-stop blue / plastic red / faded wedding pink accents, mundane absurd object treated seriously, avoid nightclub ruin and global green-pink filters.
- Art Deco imperial hotel interior: use solemn interior order, dark polished-but-aged wood, brass only as a restrained accent, vertical lobby or corridor symmetry, and one small social action. Avoid tourist lobby brochure, purple luxury lounge, empty showroom, or decorative symmetry without pressure.
- Louvre / Paris city line with sun: motivate lens flare from the actual sun entering the lens near glass, stone, river, or roofline; keep the flare local and photographic. Avoid random anamorphic streaks, postcard skyline, clean travel-ad blue, or a sun that does not affect exposure.
- Zhang Yimou-like red-blue contrast: make contrast come from costume, weather, and time of day, not arbitrary grading. Example: red textile against blue hour snow/rain, blue-gray weather surrounding a red procession, or cold daylight with one saturated costume field. Avoid copying known frames or turning it into stage-poster color blocking.
- Datong temple, Buddha sculpture, snow: prioritize solemn scale, polychrome Buddhist sculpture, snow daylight, and a designed human silhouette as scale. Use a ritual conservator, restorer, attendant, or pilgrim with a clear coat/scarf/tool silhouette rather than an ordinary tourist. Keep the human visually memorable but smaller than the sacred architecture.
- Journey to the West from the original novel: evoke the literary roles and mythic road through silhouettes, burdens, weather, and terrain. Do not resemble TV actors, animation, game key art, or cosplay lineup.
- Hong Kong absurd comedy inspired by deadpan timing: build the joke from mundane blocking, delayed reactions, prop misuse, and narrative cause/effect. Do not use actor likeness, meme faces, slapstick poster posing, or nightclub color filters.

## Progressive References

Read [references/cinema-dna-full-spec.md](references/cinema-dna-full-spec.md) when any of these apply:
- The user asks for a specific director/film DNA, Eastern wuxia staging, experimental POV, or nuanced visual system.
- The user provides reference images and you need exact preservation/extraction rules.
- The prompt output feels generic, repetitive, or lacks continuity across the three shots.
- You need the original examples or full quality checklist.
- Read [references/cinema-dna-v4-anti-ai.md](references/cinema-dna-v4-anti-ai.md) when the user says the image feels AI-like, oily, over-detailed, dirty, lens-poor, or the triptych layout feels conventional.

For routine prompt generation, use the core workflow below without loading the full reference.

## Default Behavior

Unless the user specifies otherwise:
- Output 3 separate 21:9 ultra-wide cinematic prompts.
- If the user asks to generate or "show" the result, produce three independent 21:9 images first, then crop and stitch externally; never ask the image model for a built-in collage.
- Make the three shots one continuous narrative fragment: same world, same subject, same event, same time/weather, same film texture, same light logic, same color family.
- Use no text, no title, no subtitles, no watermark, no poster/collage/split-screen/storyboard layout.
- Keep every generated shot at 2.39:1. Do not ask the image model to draw a triptych collage, contact sheet, storyboard grid, poster layout, or multi-panel image.
- Avoid cheap cinematic filters, game concept art, glossy commercial ad lighting, fake HDR, oversharpening, plastic skin, meaningless props, duplicated people, extra limbs, and random lens flare.
- Prioritize a natural photographic film-still look over spectacle: restrained exposure, matte surfaces, imperfect practical locations, real dust/smoke/rain/fog, human-scale blocking, and physical lens limits.
- Avoid words that often push image models toward oily CGI unless the user explicitly asks for them: "epic", "ultra detailed", "masterpiece", "dramatic masterpiece", "hyperreal", "8k", "volumetric fantasy", and excessive "halation".

Switch to single-frame mode only when the user explicitly asks for one image, tests one visual direction, or provides a single product/portrait/architecture angle that does not need progression.

## Input Analysis

Before writing prompts, extract:
- Subject: who or what is central.
- Place: where the scene happens.
- Event: what is happening now.
- Previous second and next second.
- Primary emotion and conflict.
- Best narrative template.
- Main visual engine and 1-2 support engines.
- Whether triptych or single frame fits.
- Character/space scale relationship.
- Lens distance, camera position, and light source.
- Main color, support color, and accent color.
- Any locked identity, structure, product features, clothing, pose, or expression from user-provided material.

## Conversation-Calibrated Defaults

Use these defaults when the user asks for repeated visual tests, says "再来几个", "生成看看", or gives terse Chinese subject lines:

- Generate quickly: write one compact prompt per shot and run the three image generations in parallel when the available toolchain permits it.
- Save generated images under `D:\Codex_Outputs\images`, prompts under `D:\Codex_Outputs\drafts`, temporary crops under `D:\Codex_Outputs\temp`, and final composites under `D:\Codex_Outputs\exports` or the active image test folder. Do not place new large files on the desktop or C drive unless the user asks.
- Default delivered composite: crop each generated frame to `1530x640`, vertically stack the three frames with 8px black gaps, and verify the final image is `1530x1936`. If the user requests no gaps or a different rhythm, adjust in external post-processing only.
- Keep the three source frames next to the composite so the user can inspect individual shots.
- When using a local OpenAI-compatible image gateway, prefer existing environment or auth configuration before asking the user for credentials. If `OPENAI_API_KEY` exists in local Codex auth and the user has said image generation is configured, use it with the configured `OPENAI_BASE_URL` and image model.
- If the user corrects a visual direction, make the next prompt change explicit in the scene language instead of only adding adjectives.

### Styled Human Rule

When the subject includes a person inside a ceremonial, architectural, fashion, fantasy, or historical-feeling setting:
- Avoid "ordinary person", "tourist", "visitor", or generic standing figure unless explicitly requested.
- Give the person one readable silhouette and one functional narrative role: ritual conservator, attendant, courier, restorer, clerk, guard, apprentice, driver, witness, or performer.
- Use 1-2 costume or prop details only: coat shape, scarf color, tool case, gloves, hat, sleeve, bag, ledger, or lantern. The details must support story and scale, not become cosplay.
- Keep Shot 1 dominated by place and scale; let the styled figure become clearer in Shot 2; use back view, silhouette, reflection, or trace in Shot 3.

### Character Continuity Lock

When a triptych contains any recurring human subject, do not rely on "same person", "same bride", "same guard", or "same character" alone. Before writing shot prompts, create a short identity capsule and repeat it verbatim in every shot where the subject appears.

Identity capsule must include:
- Ethnicity or regional facial type when implied by place or subject. For Chinese, East Asian, Japanese, Korean, Central Asian, Indian, Middle Eastern, African, European, or Latin American settings, lock the relevant identity explicitly. Do not let a Chinese or East Asian scene drift into a Western actor unless the user asks for that.
- Approximate age range and gender presentation.
- Face anchors: face shape, hair length/style, one distinctive facial feature, and skin value.
- Body anchors: height/build or posture.
- Wardrobe anchors: one coat/top silhouette, one color, one repeated accessory or prop.
- Role anchor: the character's function in the scene, not a model pose.

Use stable wording:
- Good: "the same East Asian woman in her early thirties, oval face, short black bob tucked behind one ear, natural medium skin, slim build, bottle-green wool coat, carrying the same sealed brown envelope."
- Weak: "same woman", "same bride", "beautiful girl", "Asian style", "cinematic person".

For ensemble scenes, define 2-4 identity capsules only for recurring story-critical people. Keep background people generic, but lock their regional/cultural casting if the setting requires it.

If a frame uses back view, reflection, silhouette, blur, or partial face, still include the identity capsule plus visible continuity anchors such as the same coat color, hairstyle outline, accessory, prop, or body posture.

## Image Generation Workflow

When actually generating images, use this order:

1. Write a continuity bible before generation: recurring character identity capsule(s), fixed wardrobe, repeated prop, environment, main color family, material language, lighting system, capture substrate, and forbidden drift.
2. Generate one master reference image for the character and scene if no reference image exists and the available image workflow supports reference-based generation or edit. Use it to lock identity, wardrobe, and setting.
3. If no reference-image mechanism is available, copy the same identity capsule verbatim into Shot 1, Shot 2, and Shot 3. Do not shorten it after Shot 1.
4. Generate Shot 1, Shot 2, and Shot 3 separately as individual 2.39:1 images.
5. Never ask the image model to compose the three shots into one triptych. This often turns into a storyboard, poster, or graphic layout.
6. After all three images exist, crop each externally to the same 2.39:1 ratio if needed.
7. Stitch externally in a vertical stack for final delivery.
8. Before final delivery, inspect the triptych for identity drift: ethnicity, face shape, hair, age, body build, wardrobe, and repeated prop. If a story-critical person changes identity, regenerate the drifting frame before showing the result.
9. For night scenes, dense interiors, ensemble crowds, smoke, rain, wet reflections, temples, markets, sci-fi rooms, or any visually complex frame, create a lightly denoised delivery version before stitching. Use external post-processing only: reduce high-frequency noise and oily micro-detail, keep faces readable, preserve real shadows and local film grain, and avoid plastic smoothing.

For vertical stitching:
- Use no in-image text.
- Use no white border.
- Do not generate black bars inside any image.
- Use 0-16px black spacing between images only as external post-processing. Default to 0px when the user wants no black edge.
- When the user says the triptych feels conventional, use an uneven external rhythm instead of equal stacking: held opening, impact middle, aftertaste ending, uneven memory strip, or broken surveillance strip.
- Add any final outer border or spacing only in post-processing, never inside the generated images.

### Night And Complex Scene Denoise

When a generated set includes night, low-output lamps, smoke, fog, rain, wet streets, dense interiors, large crowds, temple sculpture, machinery, city skylines, or many small props, run a light cleanup pass before final stitching:
- Use a mild median/denoise or tiny blur radius, then restrained sharpening only if the face or main object becomes too soft.
- Prefer reducing random speckle, excessive microcontrast, crunchy edge detail, oily skin shine, and over-legible background clutter.
- Preserve the intended capture substrate: do not erase all film grain, do not make skin plastic, and do not turn the image into a smooth commercial render.
- Keep the denoised files in `D:\Codex_Outputs\temp` next to the crops; keep raw source frames in `D:\Codex_Outputs\images`.
- If denoise changes identity, expression, hands, readable story objects, or architecture geometry, discard that pass and use a lighter cleanup.

## Narrative Templates

Choose one:
- Entering: exterior/whole establishment -> approach/entry -> interior pause or observation.
- Confrontation: space establishment -> relationship forms -> tension lands.
- Wandering: world -> passage through space -> pause or look back.
- Discovery: approach unknown -> discover target -> emotional aftertaste.
- Solitude: person contained by world -> slight interaction with space -> quieter, emptier ending.
- Ritual: power/order of space -> person enters order -> individual is swallowed by or contrasts with structure.

## Visual Engines

Select one main engine and 1-2 supporting engines. Do not stack more than three.

- Order Composition: axial symmetry, central perspective, frame-in-frame, doors/windows, columns, corridors, foreground occlusion, geometric spatial cuts.
- Light Drama: hard window light, door-slit light, top light, backlit silhouettes, candle/fire/light fixtures, deep underexposure, volumetric light. Light must have a real source.
- Color Narrative: one main color, one support color, one small accent. Color must serve emotion and story.
- Spatial Narrative: architecture/interior/environment carries story. Add traces such as an unfinished drink, open door, disturbed chair, wet floor, curtain movement, left-behind clothing.
- Character State: waiting, observing, confronting, wandering, hiding, losing control, missing, ritual, loneliness. Avoid model poses and direct camera-gazing without reason.
- Scale and World: human vs megastructure, nature, civilization, myth, or cosmos. Large scenes must still preserve human fate.
- Eastern Staging: mountains/water as narrative space, architecture as blocking, stillness before movement, wind through fabric/bamboo, long-scroll horizontal space.
- Subjective/Experimental Lens: fisheye, close detail, low angle, tilted horizon, reflections, glass refraction, peephole/CCTV/water POV, motion blur, focus drift, negative space. Use sparingly and only when it serves emotion.

## Director DNA Translation

Use director/film references only as internal recipes. Translate them into concrete visual language instead of writing only “in the style of X.” Common DNA groups:
- Precise Absurdity: frontal static camera, strict but not mechanical symmetry, staged spaces, precise props, calm faces, retro blocks of color.
- Realist Epic: huge real spaces, small people, deep perspective, natural light, physical materials, wind/waves/dust/smoke.
- Silent Megastructure: minimal enormous spaces, rough architecture, silhouettes, dust/fog/grain, ritual rows, oppressive geometry.
- Eastern Wuxia: landscape and architecture as staging, hidden figures, frames/layers, stillness before action, wind moving fabric and bamboo.
- Dense Urban Emotion: deep reds/dark greens/smoke yellow/night blue, narrow rooms, mirrors/glass/curtains, near yet distant people, humidity/reflections.
- Geometric Unknown: extreme symmetry, central perspective, cold corridors, ritualized movement, unease inside order.
- Time Ruins: water traces, ruins, old industrial spaces, rain/fog/wind, slow time, memory and reality pressed together.
- Distant Eastern: remote observation, natural occlusion, real terrain, restrained clothing, action happening inside space.
- Cold Gray Future: blue-gray air, glass, minimal modern space, skyline, cold order, high-rise loneliness.

## Director DNA Strength Control

When the user says the director style is weak, strengthen the DNA through camera behavior, staging grammar, rhythm, and moral viewpoint rather than adding more director names.

For each selected DNA, define:
- Camera ethic: distant observer, frontal witness, constrained participant, surveillance-like view, ritualized symmetry, handheld uncertainty, or compressed voyeur distance.
- Staging habit: axial order, lateral blocking, bodies swallowed by architecture, off-screen event pressure, characters facing away, characters separated by thresholds, or action hidden in background.
- Rhythm: stillness before action, procedural waiting, sudden absence, delayed reveal, unresolved pause, or geometric repetition.
- Light logic: one dominant practical source pattern that repeats across all three shots.
- Color discipline: one color family that carries the emotional argument, with only one small counter-color.
- Signature imperfection: lens softness, local halation, smoke/dust density, deep negative space, occluded faces, or restrained grain.

Director DNA must be visible in every shot, but never as parody:
- Shot 1 shows the world-order of the DNA.
- Shot 2 shows how people are trapped, judged, or moved by that order.
- Shot 3 leaves the DNA's emotional afterimage.

If the result looks generic, increase one concrete staging rule instead of adding adjectives.

## Reference-Learned Interior / Social Staging Grammar

When the user provides cinematic references with ornate rooms, dining tables, windows, lamps, train compartments, palaces, restaurants, or ensemble blocking, extract the abstract grammar below. Never copy exact characters, costumes, sets, or famous shot layouts.

Core composition lessons:
- Build the frame from a social arrangement, not from a single subject pose.
- Use 3-7 narrative nodes when the scene allows it: protagonist, opponent, watcher, servant, guard, empty chair, fallen body, exit, lamp, window, table, or object of decision.
- Every node needs a role: observer, target, witness, blocker, victim, authority, exit, or consequence.
- Use furniture, lamps, windows, doors, paintings, mirrors, clocks, stairs, and floor patterns as power geometry, not decoration.
- Let sightlines, table edges, floor seams, window bands, chair backs, and lamp rows carry the viewer from cause to action to consequence.

Interior staging families:
- Ornate Power Tableau: high or wide view, dense room, multiple witnesses, one political or violent center, hierarchy organized by chandelier, table, floor pattern, doorway, and bodies.
- Table Negotiation Cinema: characters separated by a table, lamp, meal, window, or empty chair; the action is small but decisive.
- Window-Silhouette Chamber Drama: pale window rectangles and dark bodies create moral distance; curtains, chairs, and table legs structure the conflict.
- Saturated Social Density: crowded interior, local red/green/gold accents, faces and costumes forming a social web around one seated or trapped subject.
- Constrained Witness POV: camera stands behind ironwork, glass, doorway, chair, table end, carriage seat, service corridor, or window recess; obstruction must make the viewer feel like a witness.

Color and light lessons:
- Warmth must be local: table lamps, chandeliers, fireplace, stained glass, desk lamps, or windows. Do not flood the whole image with amber.
- Useful interior palettes: tobacco umber + dark green + dirty tungsten; burgundy upholstery + smoke black + pale window cyan; ivory daylight + dark wood + muted gold; jade accent + black lacquer shadow + red lamp; cool gray daylight + brown wood + small fire.
- Skin is shaped by practical light and shadow, not beauty fill.
- Fabric should absorb or scatter light: velvet, wool, silk, lace, cotton, brocade. Avoid waxy faces and glossy costume shine.
- Smoke, dust, humidity, and veiling must be motivated by visible light and room atmosphere.

Lens lessons:
- 24-28mm: room as institution, people as pieces inside order.
- 32-50mm: conversation, negotiation, meal, interrogation, role conflict.
- 50-85mm: compression through frames, partial face, reflection, consequence.
- Avoid close-ups that erase social geometry.

## Linear Story Spine

A three-shot set must not be three beautiful related stills. It needs a visible story line with cause, action, and consequence.

Before generating, write an internal one-line spine:
- Shot 1: because something has already happened, the character enters or faces a specific space.
- Shot 2: the character performs or refuses one specific action.
- Shot 3: the space records the consequence, absence, or unresolved decision.

Every shot must contain a story verb, not only a mood:
- arrives, waits, crosses, hides, opens, studies, refuses, repairs, listens, discovers, abandons, follows, returns, loses, removes, burns, locks, or leaves.

Continuity objects must move or change:
- envelope, plan, lamp, car door, coat, tool, ticket, map, chair, window, doorway, fire, train, bus, signal printout, costume, or water trace.

Linear composition should guide the story:
- Use a dominant line that carries the viewer from previous cause to current action to future consequence.
- Avoid shots where the line only creates depth but does not point to a decision.
- If a frame has no visible cause/effect relation, rewrite it before generating.

## Lens Rules

- 18-24mm: megastructures, architecture, epic scale; avoid excessive distortion and stretched bodies.
- 28-35mm: default cinematic spatial narrative, streets, rooms, hotels, forests, groups.
- 40-50mm: interiors, dialogue, waiting, psychology, two-person relationships.
- 65-85mm: distance, compression, ritual, isolation, shooting through glass/doorframes, distant wuxia observation.
- 100mm+: only for strong compression and distance.
- Fisheye / 14-18mm witness POV: use sparingly, at most one shot per triptych, only when the camera is physically trapped inside a car, elevator, checkpoint booth, locker room, bus, closet, corridor corner, or other justified tight viewpoint. It should increase narrative pressure, not become a novelty effect.

## Special Lens And Light Inserts

When composition feels too conventional, one shot in a triptych may use a motivated special lens or special light event while the other two shots stay stable.

Allowed inserts:
- Fisheye witness POV from a physically constrained camera position.
- Water caustics from pool water, aquarium glass, flooded floors, wet ceilings, or moving reflections.
- Projector beams, venetian-blind shadows, fan-blade shadows, railing shadows, train-window bands, headlights sweeping through a room, surgical lamp falloff, or sodium-vapor tunnel pools.

Rules:
- Use special lens/light as narrative pressure, not decoration.
- Keep the light source explainable and preferably visible or inferable.
- Keep foreground, middle ground, and background readable.
- Keep the same color body across the triptych; the special light may be an accent, not a new palette.
- Avoid music-video lighting, neon beams, fantasy caustics, random fisheye exteriors, horror gimmicks without story reason, and anything that reads like a game/concept-art effect.

## Three-Shot Camera Rules

For default triptych output, treat these as hard camera rules unless the user overrides them.

### Shot 1 | Establish Space
- Use 24-28mm.
- Set camera height around 1.1-1.4m.
- Make the person occupy only 5%-15% of frame height.
- Use medium-deep depth of field.
- Include a clear architectural axis or large foreground element.
- The frame should first make the viewer understand the place, scale, and spatial order.

### Shot 2 | Establish Relationship
- Use 32-50mm.
- Set camera height close to the character's chest.
- Make the person occupy 20%-35% of frame height.
- Use doorframes, columns, glass, crowds, furniture, or structural openings to create a frame-within-frame.
- Let light begin concentrating on the character and the event.
- The frame should clarify the relationship between character, space, and conflict.

### Shot 3 | Leave Aftertaste
- Use 50-85mm, or keep a wide lens but change observation position clearly.
- The person may appear only as a partial body, back view, reflection, silhouette, or occluded figure.
- Allow obstruction and selective defocus.
- Reduce information and increase pause.
- The ending does not need to explain the story.
- The frame should leave a precise emotional residue rather than resolve the plot.

## Composition Rules

Each shot should include at least two of foreground, middle ground, and background.

Prefer doors, glass, columns, corridors, furniture, water, smoke, curtains, railings, branches, shadows, or partial bodies as spatial layers. Allow off-center characters, backs to camera, partial occlusion, large negative space, and important action in the background.

Avoid everyone facing the camera, ad-like posing, no foreground/background relationship, no sightline direction, and evenly lit space.

## Cinematic Beauty Rules

Anti-CGI realism is not enough. Every shot must still have a deliberate film-image design:
- One clear visual axis: corridor, window line, table edge, stair, shadow band, water line, wall joint, or skyline.
- One emotional focal point: a hand, face edge, object, doorway, light patch, reflection, empty chair, crack, stain, or distance between two figures.
- One memorable graphic shape: a bright rectangle, dark void, diagonal shadow, repeated columns, circular opening, narrow slit of light, or large negative-space block.
- Separation between subject and background through value, occlusion, silhouette, depth, or a motivated practical light. Do not rely on sharpness alone.
- A controlled light ratio: at least one area should fall into meaningful shadow, and one local area should hold the viewer's eye.
- A color accent that is small but intentional. Avoid all-gray documentary flatness unless the scene has strong graphic contrast.
- A foreground layer that feels like camera placement, not decoration.
- A frame should be beautiful because of blocking, proportion, light geometry, and emotional timing, not because it is glossy or digitally spectacular.

For architecture subjects, prioritize spatial elegance:
- Align the human figure with a strong architectural line, void, threshold, or vanishing point.
- Use morning/evening side light, skylight slots, window bands, reflected floor light, or work lamps to carve geometry.
- Show scale through a small human body, not through exaggerated fantasy architecture.
- Include one imperfect trace of labor or decision: pencil marks, model fragments, dust on drawings, taped plan, cracked sample, wet footprint, displaced chair, or unfinished mockup.

## Composition Philosophy / Anti-Meaningless Foreground

Do not use foreground objects as generic "cinematic" decoration. Foreground must earn its place by changing how the viewer understands space, danger, privacy, distance, or attention.

Before adding foreground blur, close foreground bars, shoulders, leaves, furniture, curtains, glass, or partial bodies, verify at least one function:
- It explains where the camera is physically standing.
- It creates a frame-within-frame that points to the emotional focal point.
- It separates foreground, middle ground, and background into readable spatial planes.
- It hides or delays information for narrative tension.
- It expresses the character's trapped, watched, excluded, or isolated state.
- It creates a meaningful graphic relationship with the architecture, light patch, horizon, or body line.

Reject meaningless foreground close-ups:
- No random blurry object covering the frame just to look cinematic.
- No oversized hat brim, shoulder, glass, railing, leaf, weapon, candle, or furniture edge unless it has narrative or spatial purpose.
- No macro detail replacing scene design. A close-up must still carry story, location, and emotional consequence.
- No shallow-depth-of-field trick that destroys architecture, blocking, or the three-shot progression.
- No foreground that competes with the subject without adding tension or meaning.

Composition should be built from film logic:
- Start with a visual axis: corridor, canal line, road, table edge, column rhythm, window band, stair, wall seam, shoreline, skyline, or shadow line.
- Place the subject by blocking, not posing: entering, hesitating, waiting, crossing, leaning, turning away, being watched, or partially hidden.
- Balance masses, voids, and light fields before adding texture.
- Let the viewer's eye move through the frame in a controlled path: foreground cue -> subject/event -> background consequence.
- Use negative space as pressure, not emptiness.
- Use symmetry only when it creates order, ritual, power, or unease; break it when the story needs instability.
- In triptychs, change the camera's ethical distance: Shot 1 observes the world, Shot 2 witnesses the relation, Shot 3 leaves a precise residue.

When an output feels pretty but not cinematic:
- Reduce scenic completeness and postcard balance.
- Add one unresolved human action or decision trace.
- Make the camera stand somewhere physically constrained: doorway edge, table end, platform corner, stair landing, service corridor, window recess, vehicle interior, or work pit.
- Use one imperfect architectural or environmental interruption without making it decorative.
- Preserve the visual axis, but break ornamental balance.
- Keep beauty from blocking and light geometry, not from scenic spectacle.

## Optical Imperfection System

Use optical imperfection to make the frame feel photographed by a real cinema camera, not rendered. Keep it subtle and local.

Default optical baseline:
- 2.39:1 widescreen frame.
- Real narrative feature-film still, 35mm film texture unless the user specifies another format.
- Dense, slightly deep blacks with preserved shadow detail.
- Soft highlight roll-off; practical lamps or bright highlights may have slight local halation.
- Medium-low microcontrast. The subject is clear but not digitally razor-sharp.
- Fine, uneven, natural grain; never grain stickers or heavy texture overlays.
- One main color family, one support color, and very small accents.
- Overall exposure is slightly under by about 0.5-1 stop.
- Use only explainable practical or natural light sources.
- Natural, slightly darker skin. No commercial beauty fill.
- Shot 1 uses medium-deep depth of field.

Chromatic fringing rules:
- Use only subtle optical imperfection, never stylized chromatic effects.
- Add extremely light color fringing only on high-contrast edges: window frames, architecture edges, backlit branches, character silhouettes, metal reflections, practical-light edges, glass edges.
- Keep fringing local and low strength. Do not create global RGB split, obvious red/blue outlines, vaporwave effects, cyber filters, or edge-wide color noise.
- Never let fringing reduce subject identity, readability, or spatial detail.

Halation and bloom rules:
- Let halation appear only around bright practical lights, windows, flame, candlelight, tungsten bulbs, or sharp reflections.
- Keep it soft, restrained, and photographic, like film emulsion gently eating the highlight edge.
- Use slight optical bloom or veiling only where light, lens, and air would plausibly create it. Do not use beauty-glow, fog filters, or global white haze.

Anamorphic/edge rules:
- Allow mild edge softness, slight corner falloff, weak vignette, and minor lens color bias at frame edges.
- Do not blur the subject, simulate low-resolution footage, or destroy architectural detail.

Optical look recipes:
- Oppenheimer Optical Look: 5% chromatic fringing, low-medium halation, medium highlight softening, low edge softness, fine grain, medium-high contrast. Best for historical realism, natural light, firelight, laboratories, meetings, large rooms, heavy physical images.
- Brutalist Optical Look: 4-6% edge fringing, low halation, medium-low edge softness, restrained cool/warm separation on backlit concrete and glass, fine controlled grain, medium-high contrast. Best for architecture, concrete, halls, columns, interiors, modernist power.
- Blade Runner 2049 Optical Look: 6-10% atmospheric color separation, medium halation, medium bloom, high atmospheric density, medium-low edge softness, fine grain, medium contrast, low-medium saturation with strong color atmosphere. Best for fog, dust, desert, night cities, glass, vehicles, wet ground, sci-fi scale.

## Vintage Film Stock / Anti-Oily Calibration

When a result feels oily, too smooth, too amber, or too CG-clean, apply this calibration before generating again:
- Replace "warm golden cinematic light" with "aged tungsten practical light, amber but dirty and low-output".
- Keep amber highlights local. Do not let the whole frame become honey-gold or lacquered.
- Put grain mostly in shadows and midtones, with irregular fine-to-medium density. Avoid uniform grain overlays.
- Add period film-stock texture: slight gate softness, imperfect emulsion, mild color density variation, matte blacks, and muted warm highlights.
- Lower saturation in skin, fabric, polished wood, brass, and water reflections. Skin should be natural, slightly dark, textured, and not waxy.
- Make fabrics absorb light: wool, felt, linen, canvas, and old coats should look dry, fibrous, and non-reflective.
- Make stone, plaster, wood, and metal aged by dirt, oxidation, scratches, chipped paint, salt, smoke, or water stains.
- Reduce bloom by half if lamps or windows start to look like a beauty filter.
- Keep contrast shaped by real shadows, not by glossy high dynamic range.
- Prefer "1970s/1990s cinema print density" or "aged release-print grain" over "vintage filter".

For Venice / old palace / noir interiors:
- Use olive-umber shadows, aged plaster, oxidized brass, dirty tungsten lamps, canal humidity, and smoke-darkened corners.
- Avoid clean gold walls, shiny hotel-lobby polish, waxy faces, spotless suits, overly smooth water, and decorative fantasy luxury.
- The image should feel like an old feature-film print: dense, tactile, slightly worn, and optically imperfect.

Avoid naked or unsafe prompt terms:
- Do not use "chromatic aberration" alone. Qualify it as subtle, local, optical, and only on high-contrast edges.
- Avoid RGB split, heavy film grain, vintage filter, retro washed out, cinematic color grading, moody film still, anamorphic flare, hyper realistic, ultra detailed, razor sharp, dramatic neon, strong aberration.

## Light and Color Rules

Light must answer “where does it come from?” Use daylight, overcast light, sunset, moonlight, fire, candle, practical lamps, car lights, signs, corridor lights, portholes, industrial lights, or window reflection.

Avoid source-less rim light, arbitrary blue/orange grading, dead black shadows, clipped white highlights, HDR, oversharp clarity, and random flares.

Default color structure: one main color, one support color, one small accent. Useful combinations: cold gray + smoky blue + near black; dark gold + brown + deep black; ink green + cinnabar + fog white; sea blue + off-white + dark red; burnt orange + gray brown + metallic black.

## Anti-CGI Film Texture Rules

When the result risks looking oily, artificial, or game-like, use this stricter texture profile:
- Say "photographed film still from a practical location" instead of only "cinematic".
- Use matte, dry, dusty, worn, oxidized, weathered, or coarse material language instead of glossy, polished, glowing, sleek, or pristine surfaces.
- Keep highlights dull and local. Avoid global glow, shiny specular edges, wet-looking skin, plastic armor, lacquered stone, and render-engine reflections.
- Prefer available light and underexposed ambient fill. Do not add theatrical rim lights unless the scene has a visible practical source.
- Add negative constraints: no CGI render, no Unreal Engine look, no game cinematic, no concept art, no fantasy illustration, no digital painting, no over-smooth surfaces, no glossy specular highlights, no plastic materials.
- If ancient, sci-fi, fantasy, or epic subject matter is requested, ground it with mundane physical details: dust on fabric, chipped stone, uneven masonry, exhausted posture, practical tools, smoke from a real fire, footprints, condensation, scratches, and imperfect weather.

## Preservation Rules

If the user provides an original person image, preserve identity, facial features, expression, clothing, pose, and body proportions unless asked to change them. Adjust only composition, light, environment, camera quality, and atmosphere.

If the user provides architecture/interior, preserve structure, doors/windows, wall proportions, furniture count and major positions, and design language.

If the user provides a product/furniture object, preserve shape, proportion, material, color, structure, and identifying features. Cinematic transformation happens in scene, light, camera, spatial relation, color, composition, and narrative.

Reference images are analysis material, not redraw templates. Extract abstract visual DNA only: lens distance, composition skeleton, spatial relation, light direction, color structure, texture, emotional density, foreground layers, character placement, and still/motion relation. Do not copy specific characters, costumes, scenes, camera positions, iconic shots, or signature color combinations.

## Output Templates

### Default Triptych

```markdown
### 电影判断
- 输出模式：三联叙事
- 叙事模板：
- 主引擎：
- 辅助引擎：
- 人物状态：
- 构图：
- 镜头体系：
- 光线：
- 色彩：
- DNA：

### Shot 1｜建立镜头
[one complete 21:9 prompt]

### Shot 2｜关系镜头
[one complete 21:9 prompt]

### Shot 3｜余韵镜头
[one complete 21:9 prompt]
```

### Single Frame

```markdown
### 电影判断
- 输出模式：单帧
- 主引擎：
- 辅助引擎：
- 人物状态：
- 构图：
- 镜头：
- 光线：
- 色彩：
- DNA：

### 提示词
[one complete 21:9 prompt]
```

### Original Image Provided

```markdown
### 原图锁定
[what must remain unchanged]

### Shot 1｜建立镜头
[prompt]

### Shot 2｜关系镜头
[prompt]

### Shot 3｜余韵镜头
[prompt]
```

## Quality Check

Before final output, verify:
- Narrative: previous second, next second, reason the subject is there, conflict, and aftertaste.
- Continuity: same subject/clothing/space/time/light/color across triptych; not three unrelated variants.
- Character identity: recurring people keep the same ethnicity/regional facial type, age range, face anchors, hair, build, wardrobe, and repeated prop; regenerate any drifting frame before delivery.
- Progression: shot scale, camera position, composition, emotional density, and focus evolve.
- 21:9: horizontal staging is purposeful, not just cropped.
- Light: real source, readable shadows, no fake cinematic glow.
- Color: controlled 2-3 color relationship, natural skin/materials, no overdone teal/orange, dirty yellow, gray wash, or plastic saturation.
- Texture: film-camera feel, gentle grain, soft highlights, tactile materials, photographed rather than rendered.
- Style: director DNA translated into specific visible choices and not copied from known frames.
- Naturalness: no game-engine lighting, no glossy CGI surfaces, no heroic concept-art pose, no over-clean costume, no impossible blue/orange rim light, and no spectacle-first composition unless requested.
- V4 realism: no uniform detail density, no prompt-showoff clutter, visible capture substrate, one dominant imperfection family, and a triptych rhythm that would not read the same if shuffled.
