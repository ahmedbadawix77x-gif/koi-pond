# Blocky Lake Wallpaper

A Minecraft-style voxel lake scene that runs by itself as a living laptop wallpaper, framed like a shader-pack screenshot: big trees on both sides, a mirror lake, autumn hills, a snowy range and soft clouds. The camera is fixed (a slow, subtle drift only). Built with three.js. All textures and models are original, drawn in code.

Live: https://ahmedbadawix77x-gif.github.io/koi-pond/

## What happens on its own (no buttons)
- A full day cycle: sunrise, morning, noon, sunset, night with stars, moon and fireflies. One day is about 2.5 minutes (`?dayLen=` to change).
- Betta-style blocky fish with flowing translucent fins swim in the sea. They flee when the mouse gets close.
- Lovebird pairs perch in the trees, on the beach house and on the swing. A pair builds a nest, lays eggs, a chick hatches and fledges over several days.
- A sea turtle lays eggs on the beach at dusk, and hatchlings walk to the sea at sunrise. Crabs, butterflies and a longtail boat too.
- At night the fish, birds and crabs sleep (with little Z bubbles).
- Music only: while a song plays, the island reacts to its mood (tempo, energy, brightness). Happy or fast music: fish dance in rings, hearts and swirls and jump on the beat, birds hop and fly in orbits, notes float up. Calm music: slow gentle circles and swaying. Sad or slow music: fish sink low with drooping tails and bubble tears, birds droop their heads and cry little tears, a soft rain falls and the light dims. With no music everything behaves naturally.
- World: a lake in front, a far meadow, autumn hills, a snowy mountain range, autumn and green hills, tall grass and flowers swaying in the wind, soft clouds, and a water surface that reflects the scene.
- Rendering: real-time reflections, bloom, god rays, soft shadows, a water shader (blocky ripples, shore foam, depth colour, sun glints), sharp at device pixel ratio. Quality adapts to keep the frame rate smooth.

## Music
Browsers only allow audio listening after permission. On the first click or key press the page asks for the microphone, which hears whatever your speakers play. Add `?mic=0` to skip that. `?music=1` runs a demo beat (`&mood=1` happy, `&mood=-1` sad, `&mood=0` calm). `?refl=0` turns reflections off.

## Use as a Windows wallpaper
1. Install Lively Wallpaper (free, Microsoft Store).
2. Add Wallpaper, paste the live link above, and set it.
Or open the link in Chrome or Edge and press F11 for fullscreen.

## Options (URL)
`?tod=0.25` fixed time of day (0 sunrise, 0.25 noon, 0.5 sunset, 0.75 night), `?pr=1` pixel ratio, `?post=0` no post effects, `?seed=`, `?life=`, `?dayLen=`.

## Older versions
- Earlier island versions (v3 and v3.1) stay in the git history of this repo (commit "Brighter moonlit night" is the last island build).
- `koi-pond-3d-v2.html`: realistic 3D koi pond
- `pixel-art-v1.html`: original pixel version
