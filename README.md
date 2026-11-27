# Koi Pond

An interactive pixel-art koi pond that runs in any browser. Open `index.html`, press `F` for fullscreen, and use it as a live wallpaper or a calm background on a second screen.

Live: https://ahmedbadawix77x-gif.github.io/koi-pond/

Inspired by a "koi pond wallpaper" reel by @karimeltalawii (Claude series, part 3).

## What it does

- Animated water with soft moving light patterns (caustics), drawn pixel by pixel.
- Koi in several colour patterns (red and white, orange, yellow, black and gold, brown). Each one swims with a flexible body, fins and tail.
- Lily pads with flowers that drift slowly.
- Move the mouse and a ring appears on the water. The fish steer away from it.
- Click to drop food. Nearby fish swim to it and eat it, leaving ripples.

## Controls

| Key / action | Result |
| --- | --- |
| Move mouse | Ring on the water, fish avoid it |
| Click / tap | Drop food |
| `F` | Fullscreen |
| `Space` | Pause |

## Run it

No install and no dependencies. Download the repo and open `index.html`, or host it with GitHub Pages.

## Use as a wallpaper

- Windows: open it fullscreen in a browser, or use a tool like Lively Wallpaper and point it at `index.html`.
- macOS: Plash or a similar web-wallpaper app can load the page.

## Files

- `index.html`: the whole app (HTML, CSS and JavaScript, canvas based).

## Tweaks

At the top of the script in `index.html`: `PIX` sets the pixel size, `PALETTES` the fish colours, and the fish count is set in `initWorld()`.
