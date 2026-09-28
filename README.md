# Muay Thai Training App

A minimal, GitHub-based starter for a Muay Thai training app with a camera-driven stance flow and a 3D jab proof-of-concept route at `/jab-poc`.

## Features in this starter

- Vite + React + TypeScript app scaffold
- Wouter-based route for `/jab-poc`
- Three.js scene with a debug-friendly GLTF loader
- Fallback geometric scene when the external GLB is unavailable
- Debug-mode hooks for mesh count, skeleton info, and bounding box checks

## Run locally

```bash
npm install
npm run dev
```

Then open:

- http://localhost:5173/
- http://localhost:5173/jab-poc

## Production build

```bash
npm run build
```

## Check / test

```bash
npm run check
npm test
```

## Notes

This is intentionally a safe starter scaffold. The external Soldier GLB and other production assets are not bundled into the repo. The `/jab-poc` page will render a fallback scene until the final asset URL is available.
