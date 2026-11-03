# Chenhao Ding — Minimal Academic Homepage

A simple, responsive, text-first academic website inspired by the restrained layout of https://jiaxuan-li.github.io/. It is original HTML/CSS and does not copy the reference site's code or assets.

## Contents

- `index.html`: bio, news, selected papers, SPRING GX support, and education
- `styles.css`: minimal responsive layout; no framework, build step, or dependencies
- `assets/Chenhao_Ding_CV_Public.pdf`: one-page CV safe for a public site
- `assets/Chenhao_Ding_CV_Public.docx`: editable one-page CV
- `.nojekyll`: GitHub Pages compatibility

## Preview

Open `index.html` in a browser. Optionally run `python3 -m http.server 8000` and browse to `http://localhost:8000`.

## Deploy to GitHub Pages

1. Create a public repository called `YOUR_USERNAME.github.io` on GitHub.
2. Upload the **contents** of this folder to the root of the repository, not the folder itself.
3. Open GitHub repository **Settings → Pages** and set **Deploy from a branch → main → /(root)**.
4. Open `https://YOUR_USERNAME.github.io/` once GitHub Pages finishes deployment.

## Customize

- Edit your name, biography, publications, news, and other text in `index.html`.
- Add a **verified** GitHub profile or public contact address to `.identity-links` when ready.
- To add a portrait, save a photo to `assets/portrait.jpg` and uncomment the `img` in the Bio section. The layout works without a photograph.
- The public CV is intentionally separate from a private CV that identifies confidential manuscripts under double-blind review. Do not publish private submission details unless permitted.

No analytics, cookies, external scripts, Google Fonts, or JavaScript are required.
