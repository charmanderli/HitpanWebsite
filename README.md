# Hitpan! website

Static landing page for Hitpan!, by Soft Signals Lab Inc.

## Local preview

From this directory, run `python3 -m http.server 8000` and open `http://localhost:8000`.

## Cloudflare Pages

Connect this repository to Cloudflare Pages. Select `main` as the production branch, use no framework preset and no build command, and leave the build output directory empty so Cloudflare serves the repository root. The site is plain HTML with assets under `assets/`.

Changes to `main` will deploy automatically once the Pages project is connected.
