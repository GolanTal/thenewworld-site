# The New World: The Key — Mini Site

A free, static landing page for the book. Optimized for GitHub Pages.

## Quick start
1) Upload `index.html` to the repo root. Create `images/cover-3d.png` and `images/cover-social.jpg` (your artwork).
2) Replace:
   - Amazon URL with your ASIN (keep UTMs).
   - `YOURSUBSTACK` in the iframe.
   - Optional GA4 ID in the commented script.
3) Enable GitHub Pages: **Settings → Pages → Build and deployment → Deploy from a branch**, choose `main` / root.
4) Your site will publish at `https://USERNAME.github.io/REPO/` (or your custom domain).

## Custom domain (optional)
- Add a `CNAME` file that contains your domain (e.g., `book.yourdomain.com`).
- In your DNS, create a CNAME record: `book` → `USERNAME.github.io`.
