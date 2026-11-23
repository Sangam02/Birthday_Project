# Birthday Project

A birthday surprise web experience for **Varshuu**.

## Files

- `index.html` — page structure
- `styles.css` — styles
- `app.js` — logic and content
- `audio/` — background song and sound effects

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Deploy

Upload the whole folder (including `audio/`) to any static host (GitHub Pages, Netlify, etc.) over HTTPS.

## Install as an app (PWA)

On HTTPS (e.g. Vercel), Chrome/Safari can install it:

- **Android:** browser menu → Install app / Add to Home screen  
- **iPhone:** Share → Add to Home Screen  

The app name and icon letter follow `CFG.name` in `app.js` (Varshuu → “Varshuu” + **V**). It opens full screen (`standalone`).
