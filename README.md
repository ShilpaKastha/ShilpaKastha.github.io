# Shilpa Kastha — personal homepage

A responsive, static academic homepage about gravitational waves, black holes, and the person behind the research. No build tools or installation required.

## Publish with GitHub Pages

1. Upload this folder's contents to your GitHub repository (keep `index.html` at the repository root).
2. Open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select your branch (usually `main`) and **/ (root)**, then save.

For a personal root URL, name the repository `YOUR-USERNAME.github.io`. It also works in project repositories because all local asset paths are relative.

## Edit the site

- `index.html`: introduction and featured KAN research.
- `research.html`, `group.html`, `publications.html`, `about.html`, `teaching.html`, `talks.html`, `news.html`, `photography.html`, `contact.html`: separate pages for each navigation entry.
- `style.css`: colors, typography, layout, and responsive styles.
- `script.js`: accessible image viewer.
- `assets/cv.pdf`: replace with an updated CV and update its visible date in `index.html`.
- `assets/photography/`: original personal images, resized for web delivery.

Career, teaching, publication, and email information has been updated from the user-supplied latest CV (`cv_ShilpaKastha.pdf`). The downloaded CV is the exact supplied PDF. Facebook URLs are user-supplied direct links; their contents were not accessible for verification. Two YouTube talks were verified against the speaker names and uploader information. The news article was checked at its original URL.

The site uses system fonts and needs no external font services. There are no analytics, cookies, or other runtime dependencies. Reduced-motion preferences are respected.

## Preview locally

Run `python3 -m http.server 8000` from this folder, then open http://localhost:8000.
