# Ella's portfolio website

Personal portfolio of Ella (镜文), digital artist — Daz3D, Blender and Unreal Engine.

One URL, two layouts: screens 760px wide or narrower get the phone layout, wider screens get the desktop layout. Nothing needs to be configured; the page switches by itself.

- **Entry page** — WEN STUDIO logo and loading bar, then ENTER (this click also unlocks the background music). Entering plays a blue chip-block transition that reveals the home page while the logo flies into the top bar.
- **Home** — fixed top bar (WEN STUDIO, page links, 简 / 繁 switch) and a rotary menu with a rendered 3D character (`hi/` wave, `look/` gaze, `ret/` turn-back frames). On desktop she follows the mouse over the menu; on phones she follows your finger.
- **About** — draggable profile card; turning it swaps to a second photo.
- **Works** — tilted ring of three scene videos; click one to enlarge it over a frosted background. Phones/PCs that decode AV1 in hardware get `*.av1.mp4`, everything else gets the H.264 files.
- **Characters** — three Daz characters (Yoyo, Laura, Vela) on CD-style pedestals with profile and making-of notes. Each character's frames are packed into one file (`chars/*.pack.webp`) so they download in a single request.
- **Artbook** — 41 illustrations in a 3D card row; the centre one pops out, click it for the full image and a bilingual one-line note (`album/NNs.webp` for the row, `album/NNl.webp` for the full view).
- **Contact** — email (with copy button), ArtStation, LinkedIn, Instagram.
- **Music** — `audio/bgm.mp3`, toggle in the top bar.

## Run locally
Open it through a local server rather than double-clicking `index.html`:

```
python3 -m http.server
```
