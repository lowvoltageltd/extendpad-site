# 2nd Display website

Static site (plain HTML/CSS, no build step) for the 2nd Display app, plus the hosting for the Mac app download. Published by Low Voltage Ltd.

- Live: https://lowvoltageltd.github.io/extendpad-site/ (GitHub Pages, serves `master`; a push redeploys in about 1-2 minutes).
- Files: `index.html` (landing page, inline CSS, inline SVG illustration), `privacy.html` (privacy policy), `assets/` (icons).
- Mac download: GitHub Releases on this repo. The asset must be named `2nd-Display.dmg` so `releases/latest/download/2nd-Display.dmg` (used by the buttons) keeps working. Release notes include the SHA-256.
- Design: light and airy, orange accent (`#ee7524`), rounded system font; layout cues from duetdisplay.com but no content copied. The "iPad app on the App Store" button is disabled ("coming soon") until the App Store listing is approved; then link it to the real URL.
- Contact on the privacy page: `developers@lowvoltage.nz`. Keep the page's claims true (no data collected, no network requests).

The app source, build and release process, decisions and history live in the private repo `lowvoltageltd/ExtendPad` (see its `AGENTS.md` and `docs/`). This repo is public: don't put secrets, account details or internal notes here.
