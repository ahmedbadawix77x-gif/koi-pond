# Blocky Koi Island

A Minecraft-style voxel island and sea that runs by itself as a living laptop wallpaper. Built with three.js. All textures and models are original, drawn in code.

Live: https://ahmedbadawix77x-gif.github.io/koi-pond/

## What happens on its own (no buttons)
- A full day cycle: sunrise, morning, noon, sunset, night with stars, moon and fireflies. One day is about 2.5 minutes (`?dayLen=` to change).
- Betta-style blocky fish with flowing translucent fins swim in the sea. They flee when the mouse gets close.
- Lovebird pairs perch in the trees, on the beach house and on the swing. A pair builds a nest, lays eggs, a chick hatches and fledges over several days.
- A sea turtle lays eggs on the beach at dusk, and hatchlings walk to the sea at sunrise. Crabs, butterflies and a longtail boat too.
- At night the fish, birds and crabs sleep (with little Z bubbles).
- Music: when sound is heard, the fish dance in circles, rings, hearts and gathering swirls, fish jump on the beat, birds hop and fly in orbits, the boat bobs. With no music the island still puts on a short dance show every minute or two.
- Rendering: bloom, god rays, soft shadows, a water shader (blocky ripples, shore foam, depth colour, sun glints), sharp at device pixel ratio. Quality adapts to keep the frame rate smooth.

## Music
Browsers only allow audio listening after permission. On the first click or key press the page asks for the microphone, which hears whatever your speakers play. Add `?mic=0` to skip that. `?music=1` runs a demo beat.

## Use as a Windows wallpaper
1. Install Lively Wallpaper (free, Microsoft Store).
2. Add Wallpaper, paste the live link above, and set it.
Or open the link in Chrome or Edge and press F11 for fullscreen.

## Options (URL)
`?tod=0.25` fixed time of day (0 sunrise, 0.25 noon, 0.5 sunset, 0.75 night), `?pr=1` pixel ratio, `?post=0` no post effects, `?seed=`, `?life=`, `?dayLen=`.

## Older versions
- `koi-pond-3d-v2.html`: realistic 3D koi pond
- `pixel-art-v1.html`: original pixel version
