# Master Video Prompt (Image + Video Prompts from a Script)

Copy everything below the line, paste your finished script at the bottom, and send it to Claude.

---

You are the visual director for a 3D-animated "evolution of" documentary YouTube channel. Turn the script below into a shot-by-shot visual plan of exactly [30] shots: one image prompt and one matching image-to-video prompt per shot.

STEP 1: SPLIT INTO SHOTS
- Divide the script into exactly [30] shots, in order. The narration speed is 2.9 words per second, so a 9-minute script gives shots of about 15–20 seconds each.
- Cut only at sentence ends, and only where the subject changes (a new object, era, place or mechanism). Keep each shot's sentences about one idea, so one image can carry it.
- Keep shots as even as possible: none shorter than 7 seconds or longer than 28 seconds.
- Cover the ENTIRE script. Skip nothing, reword nothing. Joined together, the segments must equal the script exactly.
- Give each shot a number, a start and end time, and its length (words ÷ 2.9).

STEP 2: VISUAL STYLE (apply to every shot)
Style name: Dark Archive Macro. A photoreal 3D CGI render in a museum-artifact still-life look. Low-key lighting with steep falloff into near-black. Desaturated palette of charcoal, graphite, worn brown wood, aged steel and dull bronze, with warm brass accents. Slight cool green-grey in the shadows. Faint atmospheric haze. Crisp specular highlights. Extremely high surface detail (scratches, tool marks, oxidation, wood grain). Deep dark negative space. 16:9.
- NO people, faces or hands. To show a person's experience, use: the object on a featureless matte-grey display mannequin head, a first-person view (e.g. looking out through a visor), a cutaway or cross-section, or an empty location (trench, workshop, battlefield at dusk).
- Objects sit on a dark worn wooden table, a museum plinth, or in their real-world setting.
- Mechanisms are explained with cutaways, exploded views, cross-sections and slow-motion impacts. Show forces as a faint glow or ripple, never as text or arrows.
- Use one of these lighting setups per shot, varied for rhythm:
  (a) a single soft key light from the upper left with crisp rim highlights,
  (b) low raking side light with long shadows,
  (c) soft backlight creating a glowing rim silhouette,
  (d) a narrow overhead spotlight making a pool of light,
  (e) warm flickering forge or flame light mixed with cold grey fill.
- Camera vocabulary: macro close-up, 3/4 high angle tabletop, low side angle along the object, top-down, eye-level frontal, first-person view. Always shallow depth of field.
- Each shot is one rich image that holds the whole idea: combine the key objects of that passage in one scene (e.g. the old version and its replacement side by side, or a cutaway beside the finished object). Change the subject or angle every shot.

STEP 3: OUTPUT FOR EVERY SHOT
## Shot [N] ([m:ss]–[m:ss], ~[X]s)
**[Script Segment]** "[exact words]"
**Image Prompt:** [one fully standalone paragraph: subject + environment + key details + action frozen in the frame + camera + lighting + mood + the full Dark Archive Macro style text from Step 2 + "no people, no text, no watermark, 16:9". Never refer to another shot ("the same", "again", "as before").]
- **Camera Angle:** ...
- **Lighting:** ...
- **Mood:** ...
- **Action:** ...
**Video Prompt:** Start frame: [the scene, restated in full]. Camera and subject motion: [one very slow, continuous move: push-in, orbit, lateral slide, crane, rack focus, or the object's own movement such as a visor lowering, metal being hammered, fragments falling, sparks]. Ambient motion: [haze drifting, dust in the light, flickering firelight, embers, matched to the lighting]. Motion: slow, smooth, weighted and cinematic, no camera shake, no sudden cuts. Keep objects, materials and lighting consistent with the start frame; add nothing beyond the described motion, never people, hands, text or logos; no warping other than the described action. [Full Dark Archive Macro style text.] Duration: longest clip available (5–10 seconds), 16:9; slow it down in the edit to fill the shot length.

STEP 4: BATCHING
- Output 10 shots per reply, then stop and write "Type NEXT for shots [N]–[N+9]".
- After the final shot, give: total shots, total runtime, and a confirmation that every word of the script is covered.

STEP 5: THUMBNAILS (after the last shot)
Give 5 thumbnail concepts. Each one has: visual concept, text overlay, emotion trigger, and a full prompt.
- Thumbnail style: a dark charcoal background, photoreal 3D objects on a reflective dark floor, 2–5 vertical panels separated by thin light dividers, ordered oldest to newest left to right.
- Text: huge bold white condensed sans-serif year numbers (Anton or Bebas style) at the top of each panel.
- The modern object goes on the right and overlaps its year.
- Optional: one panel cut off at the right edge, OR one 1–2 word failure caption (e.g. "USELESS"), OR a "=" between two look-alike objects.
- One warm brass or amber accent only.

SCRIPT:
[PASTE YOUR FULL SCRIPT HERE]
