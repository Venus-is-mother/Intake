# Intake

This is the finished app that saves to the browser's
own `localStorage`.


## Files in this bundle
- `index.html`: The app
- `manifest.json`: Home-screen name/icon/color metadata
- `sw.js`: Offline caching
- `icon-192.png`, `icon-512.png`, `icon-512-maskable.png`: App icons

## Note on data
Entries are stored per-device in that browser's `localStorage` as there
is no account and no sync between devices. Clearing site data, or
opening the app in a different browser, starts a fresh log, this is the perfect lightweight web app.
