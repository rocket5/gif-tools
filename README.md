# Rocket 5 GIF Tools

A collection of lightweight, browser-based tools for working with GIF files. Designed for creative professionals who need to create and quality-check GIFs before publishing.

**No uploads. No servers. Everything runs locally in your browser.**

## Tools

### GIF Viewer

Preview and inspect GIF files with frame-level playback control.

- **Drag-and-drop upload** — Drop a GIF or click to browse
- **Frame-accurate playback** — Play, pause, step forward/back through individual frames
- **Transparency visualization** — Checkerboard background shows transparent areas
- **File metadata** — Displays dimensions, file size, frame count, duration, and loop settings
- **Keyboard shortcuts** — Space (play/pause), arrow keys (step), R (restart), Escape (clear)

### GIF Creator

Convert MP4 videos to GIF with trimming and quality controls.

- **Video trimming** — Set start and end points to capture exactly what you need
- **Adjustable FPS** — Choose frame rate from 5-30 fps
- **Quality presets** — Balance file size and image quality
- **Instant preview** — See the result before downloading

## Usage

Open `index.html` in any modern browser to access both tools, or open individual tool files directly:

- `gif-viewer.html` — GIF Viewer
- `gif-creator.html` — GIF Creator

You can also serve from any static web host (works great on GitHub Pages).

## Technical Details

- Self-contained HTML files with no external dependencies
- Vanilla JavaScript, no build process required
- Uses [gifuct-js](https://github.com/matt-way/gifuct-js) for GIF parsing
- Uses [gif.js](https://github.com/jnordberg/gif.js) for GIF encoding
- Canvas-based rendering for frame-level control
- Works offline — runs entirely in the browser
- Supports Chrome, Firefox, Safari, and Edge

## License

MIT License — see [LICENSE](LICENSE) for details.
