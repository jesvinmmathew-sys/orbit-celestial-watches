# ORBIT — Celestial Timepieces

A single-page, scroll-driven 3D watch collection featuring Earth, Jupiter, Saturn, Luna, Neptune, and Mars editions.

## Run locally

No build step or package installation is required. Serve this directory with a static server:

```sh
python -m http.server 8000
```

Then open http://localhost:8000.

## Features

- Six distinct procedural 3D watch designs
- Scroll-linked flight paths and exploded detail sequence
- Drag-to-rotate inspection and scroll-to-zoom
- Nebula background, drifting particles, and animated mechanics
- Responsive layout and reduced-motion preference support

## Files

- `index.html` — page sections and watch inspector
- `styles.css` — responsive layout and visual styling
- `main.js` — watch geometry, materials, animation, and interactions
- `assets/aframe.min.js` — bundled A-Frame 1.8.0, exposing Three.js
- `assets/nebula.webp` — generated space background
- `assets/logo.webp` — ORBIT mark

Inter and Instrument Serif load from Google Fonts. A WebGL-capable browser is required for 3D rendering.

This is a concept collection, not a functioning shop. Designs are inspired by supplied watch references and do not reproduce their brand marks. The nebula is AI-generated; watch models are built procedurally in JavaScript.

A-Frame is a third-party dependency, licensed under MIT: https://github.com/aframevr/aframe/blob/v1.8.0/LICENSE
