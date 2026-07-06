# KADO-IDOR

This is a micro-project demonstrating a scroll-triggered animation using a pinned Three.js model.

## Features

- Three.js scene with a GLB model loaded from `public/models`
- Scroll-synced animation playback
- Pinned camera / model layout while scrolling
- Built with Vite, Three.js, GSAP, and Lenis

## Project structure

- `index.html` — main entry point
- `script.js` — Three.js setup, model loading, and scroll sync
- `style.css` — basic styles and scroll layout
- `public/models` — place your `.glb` file here

## Usage

1. Install dependencies

```bash
npm install
```

2. Start the development server

```bash
npm run dev
```

3. Open the local dev URL shown in the terminal

## Notes

- The GLB file should be placed inside `public/models`
- The app expects the model to be loaded from that folder during runtime
