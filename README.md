# ParKar landing (GitHub Pages)

Production‑ready static landing for ParKar. Deployed via **GitHub Pages** at **https://turbodario.github.io/parkar-site/**.

## Quick start

1. **Clone or create** this repository: `parkar-site` under your `TurboDario` account.
2. Copy the contents of this folder to the repo root (or unzip the release if provided).
3. Commit and push to the `main` branch.
4. Enable Pages: go to **Settings → Pages** and set **Source** to “Deploy from branch”, **Branch** to `main`, **Folder** to `/root`.
5. Visit **https://turbodario.github.io/parkar-site/** once the build completes.

## Customize

- Replace placeholder screenshots with real images:
  - `screen1.png`, `screen2.png`, `screen3.png` at repo root (1080×2280 recommended)
- Replace `og-image.png` with a 1200×630 promo image and keep the same filename (or update the meta tag in `index.html`).
- Update `SUPPORT_EMAIL` in the HTML if you use a different address.
- Edit copy in `index.html`, `privacy.html`, `terms.html`, `support.html` as needed.

## SEO & metadata

- **Open Graph** and **Twitter Cards** are set up in every page.
- **JSON‑LD** (`SoftwareApplication`) is embedded in each page to describe the app.
- `robots.txt` and `sitemap.xml` are included and reference `https://turbodario.github.io/parkar-site/`.

## Link this site in Google Play Console

In your app listing:
- Store presence → Main store listing:
  - **Developer website**: `https://turbodario.github.io/parkar-site/`
  - **Privacy policy**: `https://turbodario.github.io/parkar-site/privacy.html`
  - **Support email**: the same used here
- Save and submit for review.

## UTM tracking (optional)

Append UTM parameters when linking to Google Play to identify traffic sources, e.g.:  
`https://play.google.com/store/apps/details?id=com.turbomonguerdev.parkar?utm_source=youtube&utm_medium=video&utm_campaign=launch`

## Local development

This is a plain static site. Use any local server to preview, for example:
```bash
python3 -m http.server 8080
# open http://localhost:8080
```

## License

The site content is © 2025 TurbomonguerDev. Styles may be reused freely for your app landing.
