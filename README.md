# Karaoke Challenge (PWA)

Static web app – no build step, no server logic.

## Run locally
Any static server works, e.g.:

    npx serve .

Open http://localhost:3000 and use "Install app" (Chrome/Edge) or Share → "Add to Home Screen" (iOS Safari).

## Deploy (free)
- **GitHub Pages:** push this folder to a repo, Settings → Pages → Deploy from branch → root. URL: https://<user>.github.io/<repo>/
- **Netlify Drop:** drag the folder onto https://app.netlify.com/drop

Service worker needs HTTPS (or localhost) – both hosts provide it.

## Files
- index.html – the whole app (cards, logic, styles)
- manifest.webmanifest – PWA metadata
- sw.js – offline cache
- icon-*.png – app icons
