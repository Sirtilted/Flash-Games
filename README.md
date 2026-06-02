# Flash Archive Website

This repository contains a local Flash game archive website built from the Selenite Flasharchive source.

## Contents
- `site/` — playable website files and the local SWF library
- `site/swfs/` — Flash game files used by the player
- `dev/` — legacy HTML pages from the original archive
- `html/` — original per-game wrapper pages from the archive source

## Local usage
1. Open `site/index.html` in your browser.
2. If the browser blocks local SWF loading, run a local server from the `site/` folder:
   - `python -m http.server 8000`
3. Open `http://localhost:8000/`

## GitHub deployment
This repo includes a GitHub Actions workflow to deploy the `site/` folder to GitHub Pages.

To publish:
1. Create a new GitHub repository.
2. Add this project and push it to `main`.
3. Enable GitHub Pages or rely on the included workflow.

## Notes
- The playable site uses Ruffle via `https://unpkg.com/@ruffle-rs/ruffle`.
- The old `dev/` pages are legacy and no longer used for the new site.
