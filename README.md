# Ella's portfolio website

Personal portfolio of Ella, 3D character artist.

- **Home** — rotary menu with an animated 3D android character (frame sequences in `hi/`, `look/`, `ret/`, `g/`).
- **About** — draggable holographic profile card.
- **Works** — WebGL (three.js r176) tilted ring of curved video screens with motion-smear shader and a glass sculpture.

## Run locally
Videos are used as WebGL textures, so open it through a local server rather than double-clicking:

```
npx serve .
```

## Replace the works
Put your UE renders in `works/` and edit the `WORKS` list near the bottom of `index.html`.
