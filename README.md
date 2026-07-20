# St Andrew's Townsville B demo

Non-official static concept. Run `python3 -m http.server 8000` at repository root. Do not open with `file://`, because modules, fetch and localStorage workflows require HTTP.

GitHub Pages: deploy `main` from `/`. Cloudflare Pages: no build command, output `/`. Office PC: `python3 -m http.server 8000 --bind 0.0.0.0`.

Content baseline is `content/data.json`; `assets/storage-adapter.js` loads it and provides the localStorage replacement point. Export JSON before clearing browser storage and import it to restore.