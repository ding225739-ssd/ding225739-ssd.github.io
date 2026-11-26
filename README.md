# Chenhao Ding — academic homepage 

A minimal, static GitHub Pages website. `index.html` contains its complete CSS so the page maintains its layout even if external stylesheets are missing or cached.

## Publish
1. Unzip this archive.
2. Upload **index.html**, **styles.css**, **.nojekyll**, **README.md**, and the **assets** folder directly to the `main` branch root of `ding225739-ssd/ding225739-ssd.github.io`.
3. Go to **Settings → Pages → Deploy from a branch → main / (root)**.
4. Wait for the latest `pages build and deployment` workflow to succeed, then hard-refresh the website.

## Paper images
- `assets/rada-original.png` is cropped directly from the author's EMNLP 2026 poster.
- `assets/soba-original.png` is the original Figure 1 from the author's SOBA manuscript.
- R²A Figure 2 loads directly from the author's public arXiv HTML figure URL; SuLoRA's extracted paper diagram loads from a public figure archive.
- Two collaborator paper figures load from Jizhou Han's public homepage. These are **external images**, not bundled in this ZIP. They require an internet connection. If remote images are blocked by the hosting provider, replace their `src` URLs in `index.html` with locally exported screenshots from the corresponding papers.
- For the one collaboration paper without a verified original figure, the page uses a neutral "View original paper" text link instead of a made-up diagram.

## CV
The PDF/Word under `assets/` are the public one-page CV with R²A as an arXiv preprint, not identified as a CVPR submission.

## Notes
Do not upload the ZIP as a single file: upload its **contents**. Original paper figures have been kept as original material without stylistic redrawing.
