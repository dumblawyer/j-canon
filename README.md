# Jeopardy Canon (installable web app)

Static site: put these files at the root of any HTTPS host (GitHub Pages works), then open the address in Chrome on Android and choose **Install app**.

- `index.html` holds the page and its data (ranked from J-Archive clues aired through 2026-09-30).
- `sw.js` caches everything for offline use. Its cache version changes whenever a file changes, so a new upload replaces the old copy on the phone the next time the app opens online.
- Fonts: Barlow, Barlow Condensed and Alegreya, under the SIL Open Font License (see `fonts/`).
