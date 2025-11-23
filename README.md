# Konark Sun Temple - Website

This repository contains a static, responsive single-page website about the Konark Sun Temple.
It's ready to be uploaded to GitHub and deployed via GitHub Pages.

## What is included
- `index.html` — the complete website (hero, history, architecture, materials, wheels, diagram, timeline, conclusion).
- `images/` — all images used by the site (renamed to human-friendly names).

## How to deploy to GitHub Pages (quick)
### Option A — Using the GitHub website (drag & drop)
1. Create a new repository on GitHub (e.g. `konark-sun-temple`).
2. Upload all files and folders from this ZIP (use *Add files → Upload files* or drag-and-drop the entire folder).
3. Go to **Settings → Pages** and select the branch (main) and folder (`/ (root)`), then save. Your site will be published at `https://<your-username>.github.io/<repo-name>/` (may take a minute).

### Option B — Using Git (recommended)
```bash
git init
git add .
git commit -m "Initial commit — Konark Sun Temple website"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```
Then enable GitHub Pages in repository **Settings → Pages** (branch `main`, folder `/ (root)`).

## Notes
- If you want the site at `https://<your-username>.github.io/` (user site), name the repo `<your-username>.github.io` and push to main branch root.
- Make sure `index.html` and the `images/` folder remain at the repository root so paths work as-is.
- To change paths or split CSS/JS into separate files, edit `index.html` accordingly.

Enjoy — if you want, I can:
- Create a README with more detailed deploy steps,
- Split inline CSS into `assets/css/styles.css` and update `index.html`,
- Add a basic `404.html` page,
- Create a GitHub Actions workflow to auto-deploy from another branch.

