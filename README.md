# Liftly AI — Smart Strength Tracker (PWA)

A modern, AI-assisted gym workout logger that works as a full Progressive Web App.

## Features

- AI progressive overload suggestions
- Automatic rest timer
- Beautiful exercise picker (by muscle group)
- Dark / Light mode toggle
- Offline support via Service Worker
- Installable on Android & iOS

## How to Install on Android (right away)

1. Open the `index.html` file in **Chrome** on your Android phone  
   (or host the folder on any static server / GitHub Pages / Netlify)

2. Tap the **three-dot menu** → **“Add to Home screen”** or **“Install app”**

3. Confirm. Liftly will now appear as a real app icon and open in standalone mode (no browser UI).

That’s it — no Play Store needed.

## Files

- `index.html` — Main app
- `manifest.json` — PWA manifest
- `sw.js` — Service Worker (offline caching)
- `icons/` — App icons (192, 512, Apple touch)

## Local Development

Just open `index.html` in a browser.  
For full PWA testing (install prompt + offline), serve the folder with any static server:

```bash
npx serve .
# or
python3 -m http.server 8080
```

Then open the local URL on your phone.
