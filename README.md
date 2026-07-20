# St Andrew's Townsville modern static proposal

A concept demo, not an official church website. Static HTML, CSS and JavaScript only.

## Run locally

Clone the repository then run `python3 -m http.server 8000` from the repository root. Open `http://localhost:8000/`. Do not use `file://`: browser storage, imports and relative route testing can behave differently.

## GitHub Pages

Deploy from `main` and `/` in GitHub Pages settings.

## Cloudflare Pages

Connect the repository or direct-upload this folder. Build command: none. Build output directory: `/`.

## Office PC

Run `python3 -m http.server 8000 --bind 0.0.0.0` from the repo root.

## Content backup and restore

Use **Manage demo** to export JSON before browser data is cleared, then import that JSON to restore it. Data is stored only in localStorage for this demo. `data.json` is the baseline schema and `assets/site.js` provides the storage boundary.
