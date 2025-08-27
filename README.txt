# Realtime — Deployable PWA

Files:
- index.html (your full prototype with activations)
- sw.js (service worker for offline caching)
- manifest.json (PWA metadata)
- icon-192.png, icon-512.png

Deploy (GitHub Pages):
1) Create a new repo and push these files to the repo root.
2) GitHub → Settings → Pages → Branch: main, Folder: / (root).
3) Open the GitHub Pages URL on your phone and "Install" / "Add to Home Screen".

Deploy (Vercel/Netlify):
- Drop this folder, get an HTTPS URL, open on phone, install.

Notes:
- If you update code, bump CACHE name in sw.js (e.g., realtime-merged-v4) to avoid stale cache.
