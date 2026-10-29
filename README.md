# Blazin Fadez — Website

Static site for Blazin Fadez Barbershop (Grand Forks, ND).

## Deploy to Vercel via GitHub

1. Create a new GitHub repo and upload the **contents of this `deploy/` folder** to the repo root
   (so `index.html`, `support.js`, `assets/`, and `uploads/` sit at the top level).
2. In Vercel, click **Add New → Project** and import that GitHub repo.
3. Framework Preset: **Other**. Leave Build Command empty and Output Directory empty (it's a static site).
4. Click **Deploy**. Vercel serves `index.html` at the root.

Every push to the repo's default branch redeploys automatically.

## Files
- `index.html` — the full site
- `support.js` — runtime required by the page (must stay next to index.html)
- `assets/`, `uploads/` — images and the hero background video

All individual files are under GitHub's 25 MB limit.
