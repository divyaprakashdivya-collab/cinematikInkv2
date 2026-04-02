# CinematikInk – GitHub-ready static website

This repository contains the final static website for **Divya Prakash / CinematikInk**.

## Files
- `index.html` — main landing page
- `assets/` — SVG artwork and favicon
- `robots.txt` — crawler guidance
- `sitemap.xml` — sitemap starter
- `404.html` — fallback page
- `.nojekyll` — keeps GitHub Pages from processing the site with Jekyll

## GitHub Pages deployment
1. Create a new GitHub repository.
2. Upload all files from this folder to the repository root.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - **Source:** Deploy from a branch
   - **Branch:** `main` (or `master`) / root
5. Save and wait for deployment.

## Important edits before publishing
Update these placeholders in `index.html` and `sitemap.xml`:
- `https://your-domain.example/`

Replace it with:
- your custom domain, if available
- or your GitHub Pages URL

## Security notes
This is a **static marketing site**, so the attack surface is already low:
- no database
- no login
- no server-side form processing
- no package dependencies

Still recommended:
- use GitHub Pages or another reputable static host
- enable a custom domain with HTTPS
- use Cloudflare for DNS / caching / basic protection if needed
- do not add random third-party scripts without review

## SEO notes
This package includes:
- page title and meta description
- Open Graph and Twitter tags
- JSON-LD structured data
- robots file
- sitemap starter
- canonical placeholder

## Contact
Email currently set to:
`cinematikink@gmail.com`
