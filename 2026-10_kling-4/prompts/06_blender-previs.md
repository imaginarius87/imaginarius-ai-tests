# A Blender previs as the motion reference

## Kling 4.0

References, in upload order: `PREVIS_R12_Chase`, `ENV_River_CHANNEL`, `PROP_VillainCar`, `PROP_DetectiveCar`

```text
Live-action car chase at night in the dry concrete bed of the Los Angeles River, a big-budget late-1980s action film played completely straight; three shots and no others, ten seconds.

FRAME LOCK: one photographic 16:9 frame filling the screen edge to edge at every moment. Never divided, never a grid, never two views at once. No on-screen text.

REFERENCES, each with one job:
@video1 is a grey 3D previs animation of this exact scene, made in Blender, with no sound. It controls the motion and only the motion: every car's path, speed, order and swerve, the camera's positions, heights, lenses and moves, and the two hard cuts at 0:04 and 0:07. Follow it frame by frame. It is a moving blueprint: its grey blocks become the real channel of @image1, its black block becomes the car of @image2, its slate block with the red light becomes the car of @image3; the picture itself is photographed.
@image1 is the place reference and controls the river channel, the bed, the walls, the banks, the arch bridge, the skyline and all the light, one view at a time; it shows the channel empty, and the cars below are in it now.
@image2 is a car reference and controls the fleeing car: a long black 1988 limousine sedan with a padded black vinyl roof, chrome grille and bumpers, near-black tinted windows, wire wheels with whitewall tyres.
@image3 is a car reference and controls the chasing car: a long black 1990 police sedan with chrome bumpers, black steel wheels and one red dome beacon on its roof above the driver's door, flashing.
The drivers are dark shapes behind the glass; no face is seen.

ORIENTATION AND THE PLACES: The flat concrete bed is about fifty metres wide, the narrow low-flow channel of shallow water runs down its middle, the concrete walls slope up on both sides to the fences on the banks, with the railway tracks on the near bank and the backs of brick warehouses on the far bank. Both cars drive forward, nose first, along the bed on the near side of the low-flow channel, toward the old concrete arch bridge with its three arches and its row of lamps. The fleeing car is always first, the chasing car twenty metres behind it. Every camera stands on the same side of the cars, so both cars always travel from FRAME-LEFT toward FRAME-RIGHT. This never changes.

The actions happen one after another, in this order, each on its seconds, exactly as in @video1:

0:00–0:04 — Shot 1, wide and high, from the lip of the near bank. The camera pans with the cars as the fleeing car races in along the bed, headlights blazing, and the chasing car follows twenty metres behind, its red beacon flashing. Sound: engines roaring, a siren wailing, echoing off the concrete.

0:04–0:07 — Hard cut. Shot 2, low tracking at the foot of the near wall, the camera travelling at the cars' speed. Both cars side-on: the fleeing car ahead at FRAME-RIGHT, the chasing car behind at FRAME-LEFT, the far wall and the warehouse backs streaming past behind them; the red beacon throws pulses of red over the black roof. Sound: tyres hammering over the concrete joints, the siren close and loud.

0:07–0:10 — Hard cut. Shot 3, the camera static, low in the bed beyond the arch bridge, looking back at its middle arch. The fleeing car bursts out from under the arch, swerves across the low-flow channel and fishtails, its wheels throwing a sheet of water high into the lamplight; then the chasing car comes through the arch after it, its beacon flashing. Sound: the roar under the bridge, water slapping the concrete, the siren echoing in the arch.

LIGHTING AND LOOK: Los Angeles at night in the late 1980s: wet concrete under sodium streetlights, hot orange pools and deep teal shadows, light haze in the air catching the lamps, the red beacon pulsing across the concrete walls, the city glittering beyond. 35mm film, fine grain, rich contrast with blacks that keep detail, slight halation on the highlights, subtle period softness.

TEXTURE: wet concrete and its joints, black paint and chrome catching the lamps, whitewall tyres, spray lit orange, haze; photographic everywhere, nothing drawn, painted or rendered.

PACING: real time, no slow motion, no speed ramping.

DIALOGUE: none. No music.

LOCKS: EXACTLY TWO cars. No people outside the cars. No readable lettering.
```

## Seedance 2.5

References, in upload order: `PREVIS_R12_Chase`, `ENV_River_CHANNEL`, `PROP_VillainCar`, `PROP_DetectiveCar`

```text
Photorealistic live-action cinema, a big-budget late-1980s action film played completely straight. One generation, three shots with hard cuts, ten seconds. At night, two cars race nose first down the dry concrete bed of the Los Angeles River: a black limousine sedan fleeing, an unmarked black police sedan with a flashing red beacon chasing it.

FRAME LOCK: one photographic 16:9 frame filling the screen edge to edge at every moment. Never divided, never a grid, never two views at once. No on-screen text.

LOOK: Los Angeles at night in the late 1980s: wet concrete under sodium streetlights, hot orange pools and deep teal shadows, light haze in the air catching the lamps, the red beacon pulsing across the concrete walls, the city glittering beyond. 35mm film, fine grain, rich contrast with blacks that keep detail, slight halation on the highlights, subtle period softness.

REFERENCE JURISDICTION:
@PREVIS_R12_Chase is a grey 3D previs animation of this exact scene, made in Blender, with no sound. It controls the motion and only the motion: every car's path, speed, order and swerve, the camera's positions, heights, lenses and moves, and the two hard cuts at 0:04 and 0:07. Follow it frame by frame. It is a moving blueprint: its grey blocks become the real channel of @ENV_River_CHANNEL, its black block becomes @PROP_VillainCar, its slate block with the red light becomes @PROP_DetectiveCar; the picture itself is photographed.
@ENV_River_CHANNEL controls the river channel, the bed, the walls, the banks, the arch bridge, the skyline and all the light. It is a source of space only, one view at a time. It has ZERO authority over the vehicles.
@PROP_VillainCar controls the fleeing car only: a long black 1988 limousine sedan with a padded black vinyl roof, chrome grille and bumpers, near-black tinted windows, wire wheels with whitewall tyres. It has ZERO authority over the place or the light.
@PROP_DetectiveCar controls the chasing car only: a long black 1990 police sedan with chrome bumpers, black steel wheels and one red dome beacon on its roof above the driver's door, flashing. It has ZERO authority over the place or the light.
The drivers are dark shapes behind the glass; no face is seen.

DIRECTION: both cars drive forward, nose first, the front wheels leading, toward the old concrete arch bridge. The order never changes: @PROP_VillainCar first, @PROP_DetectiveCar twenty metres behind it. Every camera stands on the same side of the cars, so both cars always travel from FRAME-LEFT toward FRAME-RIGHT.

THE PLACES: the flat concrete bed is about fifty metres wide, the narrow low-flow channel of shallow water runs down its middle, the concrete walls slope up on both sides to the fences on the banks, with the railway tracks on the near bank and the backs of brick warehouses on the far bank. The two cars race along the bed on the near side of the low-flow channel. The arch bridge with its three arches and its row of lamps stands ahead of them. This never changes.

0:00–0:04 — Shot 1, wide and high, from the lip of the near bank, as in @PREVIS_R12_Chase. The camera pans with the cars as @PROP_VillainCar races in along the bed, headlights blazing, and @PROP_DetectiveCar follows twenty metres behind, the red beacon flashing. <engines roaring, a siren wailing, echoing off the concrete>

0:04–0:07 — HARD CUT. Shot 2, low tracking at the foot of the near wall, the camera travelling at the cars' speed, as in @PREVIS_R12_Chase. Both cars side-on: @PROP_VillainCar ahead at FRAME-RIGHT, @PROP_DetectiveCar behind at FRAME-LEFT, the far wall and the warehouse backs streaming past behind them. The red beacon throws pulses of red over the black roof. <tyres hammering over the concrete joints, the siren close and loud>

0:07–0:10 — HARD CUT. Shot 3, the camera static, low in the bed beyond the arch bridge, looking back at its middle arch, as in @PREVIS_R12_Chase. @PROP_VillainCar bursts out from under the arch, swerves across the low-flow channel and fishtails, its wheels throwing a sheet of water high into the lamplight; @PROP_DetectiveCar comes through the arch after it, the beacon flashing. <the roar under the bridge, water slapping the concrete, the siren echoing in the arch>

END STATE: @PROP_VillainCar across the low-flow channel at FRAME-RIGHT, still fishtailing in its own spray; @PROP_DetectiveCar coming out of the middle arch behind it.

TIMING: real time throughout, no slow motion, no speed ramping.

SOUND: engines at full throttle, a siren, tyres on concrete, water spray. No music, no dialogue.

LOCKS: EXACTLY TWO cars in this clip. No people outside the cars. No readable lettering.
```

## Wan 3.0 Prime

References, in upload order: `PREVIS_R12_Chase`, `ENV_River_CHANNEL`, `PROP_VillainCar`, `PROP_DetectiveCar`

```text
FRAME LOCK: one photographic 16:9 frame filling the screen edge to edge at every moment, with no black bars. Never divided, never a grid, never two views at once. No on-screen text.

REAL CINEMA RULE:
This is a real live-action car chase from a big-budget Hollywood action film of the late 1980s, photographed at night on 35mm film by a real camera crew, with real stunt cars on the real concrete bed of the Los Angeles River, played completely straight. Every frame is a real photograph of real things. Never drawn, never painted, never animated, never a render, never a video game.

MOTION RULE:
@PREVIS_R12_Chase is a grey 3D previs animation of this exact scene, made in Blender, with no sound. It controls the motion and only the motion: every car's path, speed, order and swerve, the camera's positions, heights, lenses and moves, and the two hard cuts at 0:04 and 0:07. Follow it frame by frame. It is a moving blueprint: its grey blocks become the real channel of @ENV_River_CHANNEL, its black block becomes @PROP_VillainCar, its slate block with the red light becomes @PROP_DetectiveCar; the picture itself is photographed.

REFERENCES:
@ENV_River_CHANNEL is a real location photograph of the river channel in four views. It controls the bed, the walls, the banks, the arch bridge, the skyline and all colour and light. Its views show the channel empty; the cars below are in it now.
@PROP_VillainCar is the fleeing car: a long black 1988 limousine sedan with a padded black vinyl roof, chrome grille and bumpers, near-black tinted windows, wire wheels with whitewall tyres. It keeps its exact shape and colour from its reference in every shot.
@PROP_DetectiveCar is the chasing car: a long black 1990 police sedan with chrome bumpers, black steel wheels and one red dome beacon on its roof above the driver's door, flashing. It keeps its exact shape and colour from its reference in every shot.
The drivers are dark shapes behind the glass; no face is seen.

THE PLACES:
The flat concrete bed is about fifty metres wide, the narrow low-flow channel of shallow water runs down its middle, the concrete walls slope up on both sides to the fences on the banks, with the railway tracks on the near bank and the backs of brick warehouses on the far bank. Both cars drive forward, nose first, along the bed on the near side of the low-flow channel, toward the old concrete arch bridge with its three arches and its row of lamps. @PROP_VillainCar is always first, @PROP_DetectiveCar twenty metres behind it. Every camera stands on the same side of the cars, so both cars always travel from FRAME-LEFT toward FRAME-RIGHT. This never changes.

Shot 1 [0–4s]: Wide shot from high on the lip of the near bank, panning with the cars, as in @PREVIS_R12_Chase. @PROP_VillainCar races in along the bed of @ENV_River_CHANNEL, headlights blazing; @PROP_DetectiveCar follows twenty metres behind, its red beacon flashing.

Audio: no dialogue. Engines roaring + a siren wailing, echoing off the concrete. No music.

Shot 2 [4–7s]: Low tracking shot at the foot of the near wall, the camera travelling at the cars' speed, as in @PREVIS_R12_Chase. @PROP_VillainCar ahead at FRAME-RIGHT and @PROP_DetectiveCar behind at FRAME-LEFT, both side-on, the far wall and the warehouse backs streaming past behind them; the red beacon throws pulses of red over the black roof.

Audio: no dialogue. Tyres hammering over the concrete joints + the siren close and loud.

Shot 3 [7–10s]: Static low shot in the bed beyond the arch bridge of @ENV_River_CHANNEL, looking back at its middle arch, as in @PREVIS_R12_Chase. @PROP_VillainCar bursts out from under the arch, swerves across the low-flow channel and fishtails, its wheels throwing a sheet of water high into the lamplight; then @PROP_DetectiveCar comes through the arch after it, its beacon flashing.

Audio: no dialogue. The roar under the bridge + water slapping the concrete + the siren echoing in the arch.

OVERALL VISUAL DIRECTION:
LOOK: Los Angeles at night in the late 1980s: wet concrete under sodium streetlights, hot orange pools and deep teal shadows, light haze in the air catching the lamps, the red beacon pulsing across the concrete walls, the city glittering beyond. 35mm film, fine grain, rich contrast with blacks that keep detail, slight halation on the highlights, subtle period softness.
TEXTURE: wet concrete and its joints, black paint and chrome catching the lamps, whitewall tyres, spray lit orange, haze. Real time throughout.
Final frame: @PROP_VillainCar across the low-flow channel at FRAME-RIGHT, fishtailing in its own spray, @PROP_DetectiveCar coming out of the middle arch behind it.

HARD NEGATIVES:
No third car.
No people outside the cars.
No music.
No slow motion.
No readable lettering.
No black bars at the top or bottom of the frame.
```
