# 916 Gold Booking Planner

A zero-dependency, mobile-first static web app (`index.html`) for purchase-day 916 (22K) gold advance booking decisions. Works offline once loaded and can be added to an iPhone or Android Home Screen.

## Deploy for Free via GitHub Pages (GitHub Actions)

> **Note:** On a free GitHub account, GitHub Pages requires a **public** repository. No personal bill numbers, names, or store locations are stored in `index.html`. If you prefer a **private** repo for free, use Cloudflare Pages below.

1. Create a new **public** GitHub repository (e.g. `gold-booking-planner`).
2. Push this folder to `main`:
   ```bash
   git init
   git branch -M main
   git add .
   git commit -m "Initial 916 Gold Booking Planner"
   git remote add origin https://github.com/<your-username>/gold-booking-planner.git
   git push -u origin main
   ```
3. In GitHub, go to **Settings → Pages → Build and deployment → Source** and choose **GitHub Actions**.
4. Re-run the workflow (or push any commit) — your app goes live in ~20 seconds at:
   `https://<your-username>.github.io/gold-booking-planner/`

## Alternative: Free Private Repo Deployment (Cloudflare Pages)

1. Push this folder to a **private** GitHub repository.
2. In [Cloudflare Dashboard](https://dash.cloudflare.com/) → **Workers & Pages → Create → Pages → Connect to Git**.
3. Select the repo, leave **Build command** blank, set **Build output directory** to `/`, and click **Save and Deploy**.
4. Your private-repo app deploys to `https://<project>.pages.dev` with automatic HTTPS and free deploys on push.

## Use Like a Native Phone App

Open the deployed URL on your phone:
- **Android (Chrome):** Menu (`⋮`) → **Add to Home screen**
- **iPhone (Safari):** Share button → **Add to Home Screen**

All edits (rate, MC%, showroom piece tag weights, checklist ticks) save automatically in your phone's browser (`localStorage`).
