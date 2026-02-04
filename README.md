# Sayva Web

Simple static website that explains what the Sayva app does and how it works. Uses the Sayva logo and app theme.

## Contents

- **index.html** – Landing page (what Sayva is, how it works, features, tech)
- **styles.css** – Theme aligned with the app (primary blue, green, orange)
- **assets/logo.png** – Sayva app logo

## GitHub Pages

A workflow is set up to deploy this site to GitHub Pages:

1. In the repo go to **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. On each push to `main`, the workflow `.github/workflows/deploy-sayva-web.yml` runs: it copies `sayva-web/` into the artifact and deploys it.

No build step is required; the site is plain HTML and CSS.
