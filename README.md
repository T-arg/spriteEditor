# Sprite Editor

A browser-based sprite, tile and image editor for the Arduboy by TEAM a.r.g.
It merges the three old converters (image, tile and sprite) into one and lets you draw as well.

**Open `docs/index.html`** (or the GitHub Pages site) to use it.

## Features
- Draw with pencil, eraser, line, rectangle, ellipse, fill, picker and select (move, copy, cut, paste); mirror drawing; undo/redo.
- Three asset types: sprites (frames + mask), square tiles, single images (up to 128x64).
- Text tool (press T): stamps text as pixels with a font. Two small fonts are built in (3x5 and 5x7); add your own by exporting an `.atmfont` file from the Pixel Font Editor and choosing *Add font…* (or Import…, or drop it on the page). Supports multi-line text, letter/line gap, colour modes and wrap; added fonts are stored in the browser.
- Frames timeline with animation preview, onion skin, flip/rotate/shift/invert.
- Convert PNG/JPG/GIF files: single image, sprite sheet or tile sheet (`name_WxH.png` is detected).
- Import `.h` files and choose which arrays to import (`name`, `name_mask` and `name_plus_mask` are merged into one sprite).
- Export `.h` with sprite, mask and/or plus_mask arrays per asset; PNG sheet and animated GIF export.
- Projects are saved as `.atmsprite` files and autosaved in the browser.
