# Koi Pond 3D

An interactive 3D koi pond that runs in any modern browser. Real-time WebGL (three.js): realistic koi with scaled skin and fin rays, refractive water with caustics and sun glints, a pebble pond floor, lily pads and lotus flowers.

**Live:** https://ahmedbadawix77x-gif.github.io/koi-pond/


## What you can do

| Action | Result |
| --- | --- |
| Move the mouse | A ring follows the cursor on the water. The fish swim away from it. |
| Click or tap | Drops food. Nearby fish swim over, eat it and leave ripples. |
| `S` or the Swimsuits button | Puts tiny swimsuits on the koi (bikinis and swim trunks in different prints). |
| `M` or the Music button | Opens the music mode menu (see below). |
| `F` or the Fullscreen button | Fullscreen. |
| `Space` | Pause. |
| `H` | Hide or show the buttons. |


## Music mode: how to use it

The fish listen to your music and dance. They do group routines (circle, figure eight, bloom, conga line) and kick, flap and splash on every beat. The water glows with the bass.

1. Start your music on your laptop (Spotify, YouTube, anything).
2. Open the pond and click **Music mode**.
3. Pick one option:
   - **Tab / system audio (best).** Your browser asks what to share. Choose the tab that plays the music and tick **Share tab audio**. On Windows with Chrome or Edge you can also pick **Entire screen** and tick **Share system audio**. The video part is ignored, only the sound is used.
   - **Microphone.** Allow the microphone and play the music out loud from the speakers. Works in every browser.
   - **Demo beat.** A fake 120 BPM beat, to see the dance without any audio.
4. Click the pink **Music on** button to stop.

Notes: tab and system audio sharing works in Chrome and Edge on desktop. Firefox and Safari only support the microphone option. The audio is analysed in your browser and never recorded or sent anywhere. Opening `index.html` from a file works for the demo, but the audio options need the page served over `https` or `http://localhost` (the live link above works).


## Run it

No build step. The page loads three.js from a CDN, and browsers need it served over HTTP:

```
python3 -m http.server 8000
# then open http://localhost:8000
```

Or use the GitHub Pages link above. It needs an internet connection to load three.js.

## Use as a wallpaper

- Windows: open the live link fullscreen (`F`), or use Lively Wallpaper and point it at the live link. Add `?ui=0` to the link to hide the buttons.
- macOS: Plash or a similar web-wallpaper app.

## URL options

- `?ui=0` hides the buttons.
- `?suits=1` starts with swimsuits on.
- `?music=1` starts the demo beat.
- `?seed=5` changes the layout of the pads and the fish.

## Older version

The first version (pixel art) is kept in `pixel-art-v1.html` and in the git history of this repo.

## Files

- `index.html`: the app.
- `pixel-art-v1.html`: the original pixel-art pond.

Inspired by a "koi pond wallpaper" reel by @karimeltalawii.
