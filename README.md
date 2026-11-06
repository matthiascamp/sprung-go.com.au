# Sprung-Go static site

This repository contains a copy of the public site served at [sprung-go.com](https://sprung-go.com/) on 6 November 2026. The files are placed at the repository root so they can be served directly from a web server or published at the root of a domain.

To preview locally, run:

```sh
python -m http.server 8000
```

Then open <http://localhost:8000/>. Use a server rather than opening `index.html` as a file, because the site uses root-relative asset paths.

This is a static copy of publicly available pages and assets. The original WordPress source, database, administration, and form backend are not included. The quote form will need a backend before it can accept submissions. The source site also referenced an unavailable video (`luxury_ad_final.mp4`); that broken reference was removed from the copied homepage.

The repository does not assign a custom domain. If publishing through GitHub Pages, configure the domain and Pages deployment in the repository settings, and point the domain's DNS records to GitHub Pages after the site is ready to go live.
