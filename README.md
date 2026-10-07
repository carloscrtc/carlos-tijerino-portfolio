# Carlos Tijerino — Mobile Developer Portfolio

Personal portfolio website for Carlos Raymundo Tijerino Capetillo.

**Focus:** iOS · Android · Flutter

## Tech

This portfolio is intentionally lightweight and does not require a build system:

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts
- GitHub Pages

## Project structure

```text
carlos-tijerino-portfolio/
├── index.html
├── README.md
├── .nojekyll
├── assets/
│   ├── images/
│   ├── icons/
│   └── cv/
│       └── CV_Carlos_Tijerino.pdf   # add your CV here
├── css/
│   └── styles.css
└── js/
    └── main.js
```

## Run locally

No server is required for basic preview. Open `index.html` in a browser.

For a local HTTP server:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Deploy to GitHub Pages

1. Create a GitHub repository, for example:
   `carlos-tijerino-portfolio`
2. Upload all files from this folder.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, select:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
5. Save.
6. GitHub will provide the published URL.

If you name the repository:

```text
YOUR_USERNAME.github.io
```

the site can become your root GitHub Pages website.

## Personalization checklist

Before publishing:

- Add your current CV as `assets/cv/CV_Carlos_Tijerino.pdf`.
- Replace placeholder project images if you want visual screenshots.
- Add your GitHub profile URL.
- Add public GitHub repositories to project cards if available.
- Confirm that any company/client screenshots are safe to publish.
- Do not upload confidential banking, insurance, customer or production information.

## Source basis

The content in this portfolio is based on the supplied CV. Confidential projects are described at a high level and do not expose proprietary source code, credentials, endpoints or internal information.
