
Quick Publish Guide (GitHub Pages)
===========================================

1) Create a new GitHub repository (public), e.g. "pwa".
2) Upload ALL files and folders from this package into the root of the repo:
   - index.html
   - forms.html
   - risk-assessment.html
   - manifest.json
   - service-worker.js
   - /icons/icon-192.png
   - /icons/icon-512.png
   - /assets/logo.jpg

3) Enable GitHub Pages:
   - Open the repo → Settings → Pages
   - Source: Branch = main, Folder = /(root)
   - Save. Wait up to a minute.
   - Your site will appear at: https://<your-username>.github.io/pwa/

4) Test & Install:
   - Open the site on Chrome/Edge (desktop or Android) → Install app / Add to Home Screen
   - On iPhone (Safari), use Share → Add to Home Screen (works best over HTTPS, which GitHub Pages provides).

Updating later:
- Replace /assets/logo.jpg with your final logo (same filename).
- Edit colors in manifest.json (background_color, theme_color).
- Add more forms to forms.html by duplicating the tile and adjusting the href.
- If you change filenames, also update service-worker.js ASSETS list.
