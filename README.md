# Rajendra Criminal Law Firm — Astro Site

Modern, minimal Astro website for the criminal defence practice in Chennai.

## Stack
- Astro 4.x
- Tailwind CSS
- Static output

## Setup
```bash
npm install
npm run dev
```

## Build
```bash
npm run build
```

The `dist/` folder is ready for Cloudflare Pages, Netlify, or any static host.

## Deploy to Cloudflare Pages
1. Push this folder to a GitHub repository.
2. In Cloudflare Pages: Create project → Connect Git → set build command to `npm run build` and output directory to `dist`.
3. Add custom domain `criminaladvocate.in`.
4. Optional: enable Cloudflare Web Analytics and paste the token in `src/layouts/Layout.astro`.

## Structure
- `src/layouts/Layout.astro` — shared header, footer, fonts, schema
- `src/pages/` — Home, About, Practice Areas, Contact, 404, and practice detail pages
- `public/` — WebP images, robots.txt, sitemap.xml, _headers, _redirects

## Contact
- WhatsApp / Call: +91 99942 87060
- Email: criminaladvocate.in@gmail.com
