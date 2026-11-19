# ACLLC — Web Design & Development

Static landing page for **ACLLC** (web design, redesigns, landing pages, maintenance).

**Live URL:** http://acllwebdesignco.vercel.app

## Project structure

- `index.html` — main landing page
- `assets/` — images (portfolio screenshots, 4K OG image)

## Deploy to GitHub

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin main
```

## Deploy to Vercel

1. Push this repository to GitHub.
2. Go to [vercel.com/new](https://vercel.com/new) and import the repository.
3. Framework preset: **Other** (static site). No build command required. Output directory: `.` (root).
4. Deploy.

Or with Vercel CLI:

```bash
npm i -g vercel
vercel
```

## Notes

- Contact form uses `mailto:achdouzcompany@gmail.com` (opens the visitor’s email client with details pre-filled).
- Social/OG tags are configured for `http://acllwebdesignco.vercel.app` with a 4K image at `assets/og-image-4k.png`.
