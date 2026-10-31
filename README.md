# Akhil Alladi — Creative Portfolio Experiment

A cinematic, Netflix-inspired presentation of Akhil Alladi's graphic design projects. This is a personal web-design experiment; the primary professional identity and work are graphic design.

## What's included

- A responsive, dark cinematic portfolio interface.
- A project collection based on 24 entries from the supplied saved Behance profile capture.
- 24 dedicated project detail pages under `projects/<project-id>/index.html`.
- Project summaries and available cover previews.
- About, services and contact sections.
- Responsive layouts, scroll effects and reduced-motion support.
- SEO and social-sharing metadata.

## Technology

This is a static website built with semantic HTML, CSS and vanilla JavaScript. It has no package dependencies or build step.

## Run locally

Open `index.html` in a browser, or run:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Publish with GitHub Pages

This project is intended for GitHub Pages and GitHub Actions; it does not require Vercel.

1. Open **Settings → Pages**.
2. Select **GitHub Actions** as the deployment source.
3. Push changes to `main`.
4. Check the Actions tab for the deployment result.

Expected site URL:

https://akhilalladi-code.github.io/akhil-alladi-netflix-portfolio/

## Project and asset provenance

The 24 project entries were recovered from the supplied saved Behance profile capture. The capture provided project-page content and cover-preview images; it did **not** include the complete original image galleries or original video files.

Consequently:
- The project pages are stored in this GitHub repository.
- Some cover previews currently reference Behance's image CDN; they are not yet repository-hosted originals.
- Do not treat a cover preview as a complete case study or full project gallery.
- Replace remote previews with approved original files in this repository when those source assets are available.
- Verify project titles, descriptions, credits and publication permissions before making changes.

Behance source profile: https://www.behance.net/akhil_alladi

## Customization

- Update the project collection in `index.html`.
- Update the corresponding detail page in `projects/<project-id>/index.html`.
- Store approved project imagery in a local `assets/` directory and reference those files with relative paths.
- Keep each project title, slug, preview and detail page correctly matched.

---

This repository is a personal web-development experiment and complements, rather than replaces, the graphic design portfolio.
