# Akhil Alladi — Netflix-inspired Creative Portfolio

A dark, entertainment-platform-inspired portfolio that presents Akhil Alladi's graphic design and creative work through a project carousel and individual project pages.

**Live site:** https://akhilalladi-code.github.io/akhil-alladi-netflix-portfolio/  
**Repository:** https://github.com/akhilalladi-code/akhil-alladi-netflix-portfolio  
**Primary portfolio:** https://akhilalladi-code.github.io/akhil-alladi-portfolio/

## Experience

- Netflix-inspired dark interface and featured hero section.
- Horizontal project rails and named project-detail URLs.
- Individual HTML project pages with project descriptions and available source previews.
- Responsive layouts and reduced-motion CSS support.
- GitHub Pages deployment through GitHub Actions.

## Project content and asset integrity

The repository contains individual project pages for the projects represented in the saved Behance profile capture. Several project pages use Behance-hosted source images or embedded media. Those external assets may depend on Behance availability and are not locally archived originals.

Some legacy numeric project directories remain alongside human-readable project slugs for compatibility with the earlier URL structure. Avoid deleting those legacy paths until redirects or inbound links have been checked.

## Local preview

This is a static HTML site. From the repository root, start any static file server, for example:

```bash
python -m http.server 8000
```

Open http://localhost:8000.

## Deployment

GitHub Pages is deployed by `.github/workflows/deploy.yml` after a lightweight HTML structure check. In repository settings, configure Pages to use GitHub Actions.

## Manual quality checks

- Open the homepage and visit every project card.
- Open a project URL directly, then refresh it.
- Check image and video embeds when online.
- Test the navigation and modal interactions.
- Check at mobile widths and with keyboard navigation.
- Review browser console/network errors for blocked external assets.

The workflow checks HTML document structure; it does not replace browser-based functionality, accessibility, or responsive testing.

## Credits and permissions

Project titles and source links are based on the supplied Behance portfolio material. Only publish original assets that you own or are authorized to share. Retain attribution and the original-project link where useful.

---

© Akhil Alladi.
