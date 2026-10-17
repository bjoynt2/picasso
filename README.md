# Picasso: Designed by Paul Smith — Our Auckland Visit (17 Oct 2026)

Curated photo journal and interactive 15-room exhibition guide from Brian & Monya's visit to **Picasso: Designed by Paul Smith** at Auckland Art Gallery Toi o Tāmaki.

## GitHub Pages Structure

- `index.html` — Main entry point optimised for GitHub Pages (also mirrored as `picasso_cubist_experience.html`).
- `.nojekyll` — Instructs GitHub Pages to bypass Jekyll processing and serve static files directly.
- `images/` — 90 curated full-resolution (1536×2048) progressive JPEGs and walkthrough videos.
- `thumbs/` — 90 web-optimised 640px progressive JPEG thumbnails for fast Lightbox Gallery grid & 15-Room badge loading.

## How to Publish to GitHub Pages

1. Create a new repository on GitHub (or use an existing one).
2. Upload or push the contents of this `github/` folder to the root of your repository's `main` branch:
   ```bash
   cd github
   git init
   git add .
   git commit -m "Publish Picasso: Designed by Paul Smith exhibition journal"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<your-repo>.git
   git push -u origin main
   ```
3. In your GitHub repository, go to **Settings → Pages**, select **Deploy from a branch**, choose **`main`** and **`/ (root)`**, and click **Save**.
