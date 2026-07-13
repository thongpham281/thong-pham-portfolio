# Thong Pham — Data Engineer Portfolio

A responsive, accessible, single-page portfolio website built with plain HTML, CSS, and JavaScript. It is based on the supplied UI mockup and contains no framework or build-step dependency.

## Features

- Responsive desktop, tablet, and mobile layouts
- Sticky navigation with active-section tracking
- Mobile navigation menu
- Hero data-platform illustration built entirely with CSS
- Experience timeline, technical-skills grid, education, and contact sections
- Scroll reveal animations with reduced-motion support
- Downloadable resume
- GitHub Pages deployment workflow

## Project structure

```text
.
├── .github/workflows/deploy.yml
├── assets/
│   ├── favicon.svg
│   └── Thong_Pham_Resume.pdf
├── index.html
├── styles.css
├── script.js
├── package.json
├── LICENSE
└── README.md
```

## Run locally

The project can be opened directly by double-clicking `index.html`. For a local web server:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

You can also run:

```bash
npm run preview
```

## Customize

- Edit profile and experience content in `index.html`.
- Update colors, spacing, and layout tokens at the top of `styles.css`.
- Replace `assets/Thong_Pham_Resume.pdf` with a newer resume while keeping the same filename.
- Change the LinkedIn and email links in `index.html` as needed.

## Deploy with GitHub Pages

1. Create a GitHub repository and push these files.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, select **GitHub Actions**.
4. Push to the `main` branch. The included workflow will deploy the site.

## License

MIT
