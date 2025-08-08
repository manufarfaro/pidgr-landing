# Pidgr Landing

A minimal, static “Coming Soon” page for Pidgr.com.

- HTML/CSS/JS only (no build tools)
- Lightweight background animation using GSAP (loaded via CDN)
- Assets live under `assets/`

## Quick preview

You can open `index.html` directly in a browser, but using a local server is recommended.

### Node

```bash
npx serve -p 5173 .
```

Open `http://localhost:5173`.

## What to edit

- Page markup/styles/animations are all in `index.html`.
- Images and icons are in `assets/`.

## Deploying

This is a static site. Deploy by serving the repository root (or the `index.html` and `assets/` directory) on any static host.