# Intake — Ready to Deploy

This is the finished app that saves to the browser's
own `localStorage`.


## Files in this bundle
- `index.html` — the app
- `manifest.json` — home-screen name/icon/color metadata
- `sw.js` — offline caching
- `icon-192.png`, `icon-512.png`, `icon-512-maskable.png`: app icons

## Note on data
Entries are stored per-device in that browser's `localStorage` as there
is no account and no sync between devices. Clearing site data, or
opening the app in a different browser, starts a fresh log, this is the perfect lightweight web app.
