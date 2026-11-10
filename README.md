# Repeat Sketchpad

Draw in a square tile and watch the seamless repeat update as you paint.

Most tiling tools have you upload an image, look at the result, then go back to an image editor to fix it. Here the drawing area and the repeated pattern sit side by side, and every brush stroke shows up in the repeat right away.

## Features

- **Edges wrap.** A stroke that runs past one edge of the tile continues from the opposite edge, so the tile stays seamless. "Show neighbors" draws the edges of the adjacent tiles around the editor.
- **Paint on the repeat.** You can also draw anywhere in the repeat preview, and the tile updates to match.
- **Repeat types:** grid, brick, half-drop and mirror. "Show tile edges" outlines each tile in the preview.
- **Seam checking:** "Offset ½" moves the tile by half its width and height so the edges land in the middle. The arrow keys move it by 1 px.
- **Tools:** brush, eraser, fill (the fill also wraps across edges), colour picker, and a hard-pixel mode for pixel art. The tile can be 16 to 512 px square.
- **Import and export:** load or paste an image to start from. Export shows the tile and a 3×3 repeat at 1× to 8× scale.
- Undo and redo, and your tile and settings are saved in your browser.

## Running it

It's one HTML file with no build step and no dependencies apart from Google Fonts. Open `index.html` in a browser, or serve the folder with any static file server.

To host it with GitHub Pages, go to **Settings → Pages**, choose **Deploy from a branch**, and select `main` and `/ (root)`.

## Keyboard shortcuts

| Key | Action |
| --- | --- |
| `B` / `E` / `F` / `I` | Brush / eraser / fill / colour picker |
| Hold `Alt` | Pick a colour while using another tool |
| `[` / `]` | Smaller / larger brush |
| `X` | Swap the brush and background colours |
| Arrow keys | Move the tile 1 px (wraps around) |
| `Ctrl/Cmd + Z` | Undo |
| `Ctrl/Cmd + Shift + Z` or `Ctrl/Cmd + Y` | Redo |
| `Ctrl/Cmd` + scroll on the preview | Zoom the preview |
