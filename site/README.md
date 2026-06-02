# Flash Games Archive Website

Open `index.html` in this folder to browse the archive and launch games.

## Notes
- The SWF files are stored in the `site/swfs` folder.
- The site uses Ruffle to play Flash games in modern browsers.
- If a game fails to load from the file system, use a local web server to serve the `site/` folder.

## Local server example
- Python 3: `python -m http.server 8000`
- Then open `http://localhost:8000/` in your browser.
