# FocusFlow

FocusFlow is a dependency-free, offline-first study tracker PWA. It includes a real-time focus timer, full-screen focus mode, subject management, goal tracking, weekly analytics, session history, and study streaks.

## Run locally

Service workers require HTTP rather than opening `index.html` directly:

```powershell
python -m http.server 4173
```

Then open `http://localhost:4173`.

## Deploy

Upload this folder to Vercel or Netlify, or publish it with GitHub Pages. No build step is required.

## Data and privacy

All subjects and study sessions are stored in the browser's `localStorage`. FocusFlow has no server, account, analytics, or external runtime dependencies.

## Files

```text
index.html
manifest.json
sw.js
icons/
  icon-192.png
  icon-512.png
```
