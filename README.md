# Manurag Khullar — academic website

A small, accessible academic website made with HTML and CSS. No build tools, analytics, or JavaScript are needed. Source Sans 3 loads from Google Fonts, with system-font fallbacks.

## Edit the site

- `index.html` contains a profile, short biography, graduate education, publications, selected honors, and a brief teaching and service note. Experience and undergraduate details are omitted.
- `style.css` controls colors, type, spacing, mobile layout, and printing.
- `favicon.svg` is the browser tab icon.
- `.nojekyll` tells GitHub Pages to serve these files directly.

The white, responsive layout places the portrait beside the introduction on desktop and above it on mobile, with profile details and accessible social icons below the photo. Top navigation links jump to each section. Its structure draws on https://janetlauyeung.github.io/, with earlier references https://andaqu.github.io/ and https://shami09.github.io/; the text and blue accents are specific to Manurag. The portrait loads from Manurag's public GitHub avatar, and university marks load through Google's favicon service. These images require an internet connection. Update the image and profile URLs in `index.html` to change them.

Update publication statuses and reviewer service as they change. The content was based on the live Overleaf CV on September 8, 2026, and condensed for the homepage. Phone numbers and the private Overleaf editor link are not published.

## Preview locally

Open `index.html` in a browser, or run `python -m http.server 8000` in this directory and visit http://localhost:8000.

## Publish with GitHub Pages

1. Use the public repository `manuragkhullar/manuragkhullar.github.io`.
2. Put these files at the repository root on the `main` branch.
3. Open **Settings → Pages**. Select **Deploy from a branch**, then **main** and **/(root)**, and save.
4. After the Pages deployment succeeds, the website is available at https://manuragkhullar.github.io/.

The relative stylesheet and icon paths also support deployment beneath a repository subpath.
