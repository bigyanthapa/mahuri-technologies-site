# Mahuri Solutions static site

Static marketing site for Mahuri Solutions, ready for GitHub Pages.

## Deploying on GitHub Pages

1. Push this folder to the repository's `main` branch.
2. In GitHub, open **Settings > Pages**.
3. Set **Source** to **Deploy from a branch**.
4. Select `main` and `/ (root)`.
5. Confirm the custom domain is `www.mahurisolutions.com`.

The `CNAME` file is included at the repository root for GitHub Pages.

## Contact form

The contact form posts to:

```text
https://formspree.io/f/{your-form-id}
```

Replace `{your-form-id}` in `contact/index.html` and the support pages after creating the Formspree form.

## Screenshots

The files in `assets/img/` are lightweight SVG preview images. Replace them with production screenshots when app store screenshots are finalized. Existing markup already uses lazy loading and fixed dimensions to avoid layout shift.
