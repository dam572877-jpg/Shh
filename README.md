# Ahmed & Shahd — Our Little Universe

A romantic, responsive, single-page website made with plain HTML, CSS, and JavaScript.

## Run locally

No build step, package manager, or server is required. Open `index.html` in a modern browser.

## Publish with GitHub Pages

1. Create a new **public** GitHub repository (for example, `ahmed-shahd`).
2. Upload **the contents of this folder** to the repository's top level. `index.html` must be in the repository root, alongside `assets/` and `.nojekyll`.
3. Commit the files to the `main` branch.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select branch **main** and folder **/(root)**, then save.
7. Wait for GitHub Pages to finish publishing. Your site URL will appear in the Pages settings.

## Project structure

```text
.
├── index.html
├── README.md
├── .nojekyll
├── favicon.svg
└── assets/
    ├── her-1.jpg
    ├── her-2.jpg
    ├── her-3.jpg
    ├── her-4.jpg
    └── us.jpg
```

## Notes

- All photos are stored locally in `assets/`; the site does not depend on an external image host.
- The background music is generated in the browser with the Web Audio API. It starts only after the visitor taps the music control, as required by modern browser autoplay policies.
- Google Fonts are an optional enhancement. If they cannot load, the page uses local system-font fallbacks.
- The site uses relative asset paths, so it works both at a custom domain and at a GitHub Pages project URL such as `https://USERNAME.github.io/REPOSITORY/`.
- The photos are personal. Do not reuse or redistribute them without permission.
