# Ownly — Product, Document & Warranty Manager

Live app: open `index.html`, or deploy with GitHub Pages.

## Deploy on GitHub Pages (2 minutes)

1. Create a new GitHub repo (e.g. `ownly-app`). Do NOT add a README on GitHub.
2. Upload these files to the repo root (`index.html`, `assets/`, `.nojekyll`) —
   web upload works, or via terminal:
   ```bash
   cd ownly-site
   git init
   git add .
   git commit -m "Ownly app"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/ownly-app.git
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Deploy from a branch → `main` / `/ (root)` → Save.**
4. Open `https://YOUR-USERNAME.github.io/ownly-app/` — the app loads.

Need internet on first load (React + fonts via CDN).
