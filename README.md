# Tasks & Spends

Personal Android-friendly app (installable web app / PWA) for:
- To-do list (due date, priority, active/done filters)
- Spending tracker in INR (categories, daily/7-day/monthly totals, monthly budget, per-segment breakdown and insights)

## Structure
- `docs/index.html` – the whole app (HTML, CSS, JS; data in localStorage)
- `docs/manifest.json` – PWA manifest
- `docs/sw.js` – service worker (offline support; bump `VERSION` when app files change)
- `docs/icon-*.png`, `docs/icon.svg` – app icons
- `docs/ROADMAP.md` – planned work

## Run locally
Open `docs/index.html` in a browser, or run `python3 -m http.server -d docs 8000`.

## Install on Android
Host `docs/` with GitHub Pages (Settings > Pages > Deploy from a branch > main /docs), open in Chrome, then menu > Add to Home screen.
