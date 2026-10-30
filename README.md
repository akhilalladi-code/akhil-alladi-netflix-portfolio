# Akhil Alladi — Creative Portfolio

A cinematic, Netflix-inspired portfolio for Akhil Alladi, graphic designer based in Hyderabad, India.

## Experience
- Dark, cinematic visual direction with a bold featured introduction
- Horizontally scrollable collection featuring all 24 projects from the supplied Behance profile capture
- 24 dedicated project detail pages under `projects/<project-id>/index.html`
- Each detail page includes the available Behance cover preview, project summary, and a link to its original Behance page
- About, services and contact sections
- Responsive layouts for desktop, tablet and mobile
- Scroll reveal motion, sticky navigation and reduced-motion support
- SEO and social sharing metadata

## Tech
This is a lightweight static website built with semantic HTML, CSS and vanilla JavaScript. It has no build step or package dependencies, so it can be hosted directly with GitHub Pages.

## Run locally
Open `index.html` in a browser, or run a local server:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy to GitHub Pages
1. In the repository, open **Settings → Pages**.
2. Under **Build and deployment**, select **GitHub Actions** as the source.
3. Push to `main`. The included workflow publishes the site automatically.
4. The site will be available at https://akhilalladi-code.github.io/akhil-alladi-netflix-portfolio/.

## Content notes
The portfolio includes all 24 project entries found in the supplied saved Behance profile page. Each project has its own local GitHub Pages detail page. The saved page contains cover-preview images, not complete project galleries or original video files. At present, cover previews are displayed from Behance's image CDN; the HTML pages and project descriptions are stored in this repository. Full gallery assets and original video files were not included in the supplied page capture.

## Customize
- Edit the project list in `index.html` and the corresponding `projects/<project-id>/index.html` pages.
- Replace remote Behance preview image URLs with repository-hosted assets if you later add the original image files.
- Update the LinkedIn and GitHub links if your profile URLs change.
