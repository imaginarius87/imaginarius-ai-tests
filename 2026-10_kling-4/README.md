# Is Seedance 2.5 DETHRONED? — Kling 4.0, first impressions

The prompts, frames and Blender previs behind the episode of **The Good, the Bad and the Ugly** (October 2026).

## How it was tested

- The same brief for every model, written in each model's own prompt form (the content is identical; the syntax differs).
- One run per prompt. **Every clip in the video is a first take: no fixes, no cherry-picking.**
- 720p, 10–15 seconds a clip (one round at 30 s).
- Kling 4.0 on klingai.com; Seedance 2.5 and Wan 3.0 Prime on Runway or TopView; Seedance 2.0 for part of the style round.
- The characters (Nick, Nora, Silas, Eddie and the band) are original characters made for these tests. Tags like `@CHAR_Nick_SHEET` point at uploaded reference images (character sheets, place images, car images); upload your own under the same names, or rename the tags.
- On Kling's site, references are selected by hand: characters as **Elements**, images as `@image1`, `@image2`… in upload order.

## The rounds

| Round | What it tests | Result |
|---|---|---|
| [Drama at a table](prompts/01_drama.md) | Two characters in a diner booth, two lines of dialogue. Faces, eyelines, voices, the 180° line. | Seedance 2.5 held the geography exactly; Kling 4.0 had strong faces but reversed the two-shot; Wan 3.0 got the voices but broke the geography across cuts. |
| [Street fight (15 s, text only)](prompts/02_street-fight.md) | A six-shot brawl on a 1980s LA sidewalk; every punch written with its hand and its target. | Seedance 2.5: a film-ready first take. Wan 3.0: close behind. Kling 4.0: blows without weight, a cartoon fall; about 8–9 usable seconds. |
| [Kling keyframes on the same fight](prompts/03_keyframes.md) | The R2 text unchanged, plus four photoreal keyframes at 0:04, 0:06, 0:09 and 0:14. | Kling hit the middle keyframes; usable seconds went from about 8–9 to about 11–12. The end keyframe was overridden by its own big fall. |
| [Lip sync to a song](prompts/04_lip-sync.md) | A five-piece band on a ferry deck at night, the lead vocal sung to the song. | Kling 4.0: the mouths land on the words (a big step from 3.0). Seedance 2.5 remains the best; Wan 3.0 did not hold up. |
| [30 seconds in one take](prompts/05_30-seconds.md) | Six shots in a police squad room, a prisoner, three photographs, two lines. | Seedance 2.5 (TopView): almost perfect, ~29 of 30 seconds usable. Wan 3.0: good, ~25–28 s. Kling 4.0: frays after ~15 s, ~9 s usable. |
| [A Blender previs as the motion reference](prompts/06_blender-previs.md) | A grey 10 s previs of a car chase (three cameras) given to every model with a place image and two car images. | All three followed the previs. Kling kept both cars as their reference images; Seedance and Wan turned the unmarked car into a patrol car (partly our prompt's fault: it said "police sedan"). |
| [Styles: "Why am I drawn?"](prompts/07_styles.md) | One rooftop moment in anime, 3D, black-and-white noir and photoreal, each starting on its own frame. | All three generators held every style; it is a matter of taste. Kling's noir was the most beautiful, and its 3D kept the character from the first frame. |
| [Kling 3.0 vs 4.0: two old drives rebuilt](prompts/08_kling-3-vs-4.md) | Two Kling 3.0 clips (native 4K via Runway) rebuilt on Kling 4.0 from the takes. | The driver is on the right side now and the hands hold the wheel. Our mistake: the first shot of the canyon drive named nobody, so the car drove itself for four seconds. |

Image prompts (keyframe board, rooftop frames, thumbnails): [prompts/images.md](prompts/images.md)

## Media

- [`media/previs_chase.mp4`](media/previs_chase.mp4): the 10-second grey Blender previs used as the motion reference in the previs round.
- [`media/previs_plan.jpg`](media/previs_plan.jpg): its top-down plan.
- [`media/fight_keyframe_board.jpg`](media/fight_keyframe_board.jpg): the 2x2 keyframe board for the fight (split into four keyframes).
- `media/rooftop_*.jpg`: the four start frames of the style round (photoreal master, anime, 3D, noir).

## Prices used (per second, 720p, list prices, October 2026)

| Model | Price per second |
|---|---|
| Kling 4.0 (klingai.com) | $0.075 |
| Seedance 2.5 | $0.12 (TopView) – $0.24 (Runway) |
| Wan 3.0 Prime | $0.06 (TopView) – $0.11 (Runway) |

Per usable second on the 30-second take: Kling 4.0 ≈ $0.25 (≈9 of 30 s usable), Seedance 2.5 ≈ $0.12 (≈29 of 30 s, TopView).

## Verdict in one line

Not dethroned. Kling 4.0 sits below Seedance 2.5 in every section, but close enough to matter, at a fraction of the price. Look at the budget first; go to Seedance where the action is fast, physical and long.
