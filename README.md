# Ella's portfolio website

Personal portfolio of Ella (镜文), digital artist — Daz3D, Blender and Unreal Engine.

One URL, two layouts: screens 760px wide or narrower get the phone layout, wider screens get the desktop layout. Nothing needs to be configured; the page switches by itself.

- **Entry page** — loading bar, then ENTER (this click also unlocks the background music).
- **Home** — rotary menu with a rendered 3D character (`hi/` wave, `look/` gaze, `ret/` turn-back frames). On desktop she follows the mouse over the menu; on phones she follows your finger.
- **About** — draggable profile card; turning it swaps to a second photo.
- **Works** — tilted ring of three scene videos; click one to enlarge it over a frosted background. Phones/PCs that decode AV1 in hardware get `*.av1.mp4`, everything else gets the H.264 files.
- **Contact** — email (with copy button), ArtStation, LinkedIn, Instagram.
- **Music** — `audio/bgm.mp3`, toggle in the top bar.

## Run locally
Open it through a local server rather than double-clicking `index.html`:

```
python3 -m http.server
```
