# GIF Viewer

A lightweight, single-page web tool for previewing GIF files. Designed for creative professionals who need to quality-check GIFs before publishing.

## Features

- **Drag-and-drop upload** — Drop a GIF or click to browse
- **Frame-accurate playback** — Play, pause, step forward/back through individual frames
- **Transparency visualization** — Checkerboard background shows transparent areas
- **File metadata** — Displays dimensions, file size, frame count, duration, and loop settings
- **Keyboard shortcuts** — Space (play/pause), arrow keys (step), R (restart), Escape (clear)
- **Works offline** — No server required, runs entirely in the browser

## Usage

Open `gif-viewer.html` in any modern browser:

- Double-click the file
- Drag it into a browser window
- Serve from any static web host

Then drop a GIF onto the page or click to browse.

## Technical Details

- Single self-contained HTML file (~15KB)
- Vanilla JavaScript, no build process
- Uses [gifuct-js](https://github.com/matt-way/gifuct-js) for GIF parsing
- Canvas-based rendering for frame-level control
- Supports Chrome, Firefox, Safari, and Edge

## Why?

Native browser GIF display doesn't expose frame-level control. This tool parses the GIF binary, extracts individual frames with timing data, and renders them to a canvas — enabling pause, step, and restart functionality that's not possible with a standard `<img>` tag.
