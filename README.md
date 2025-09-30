# ParKar landing (GitHub Pages)

Bilingual static site (EN/ES) for **ParKar** at **https://turbodario.github.io/parkar-site/**.

## Deploy

1. Create the repo **parkar-site** under **TurboDario** (or use the existing one).
2. Copy these files to the repo root and push to the `main` branch.
3. Enable GitHub Pages: **Settings → Pages** → Source **Deploy from branch**, Branch **main**, Folder **/**.
4. Your site will be available at **https://turbodario.github.io/parkar-site/**.

## Customize

- Replace placeholder screenshots with real 1080×2280 PNGs named `screen1.png`, `screen2.png`, `screen3.png` at repo root.
- Replace `og-image.png` with a 1200×630 promo image (update `<meta>` if you change the filename).
- Update contact info in `support.html` and `es/support.html` if you change phone or email.

## Google Play Console

In **Store presence → Main store listing** for your app:
- **Developer website**: `https://turbodario.github.io/parkar-site/`
- **Privacy policy**: `https://turbodario.github.io/parkar-site/privacy.html` (you may also add the Spanish version at `https://turbodario.github.io/parkar-site/es/privacy.html`)
- **Support email**: `turbomonguer.dev@gmail.com`
- **Support phone**: `+34 633 708 982`

## SEO

- Each page includes Open Graph, Twitter Cards, and JSON‑LD (`MobileApplication`), plus `robots.txt` and `sitemap.xml`.
- `hreflang` and language switch links for EN and ES.

## Local preview

```bash
python3 -m http.server 8080
# open http://localhost:8080
```

## License

© 2025 TurbomonguerDev. Content may be adapted for your app.
