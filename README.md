# zigzagalc.org

Static copy of the ZigZag Agile Learning Community website, moved off WordPress in Nov 2026.
Hosted on Cloudflare Pages (no build step, output directory is the repo root).

- Pages live at `<page>/index.html` (home is `index.html`).
- Images and theme files keep their old WordPress paths under `wp-content/` and `wp-includes/`.
- The contact form on `/contact/` posts to the ZigZag Google Apps Script (emails Hany and Keli, logs to the "ZigZag Contact Form Submissions" sheet, sends the Prospective Family Guide).
- `/zero/` is Subject Zero, Zain's reading game (not linked from the rest of the site).
- `_redirects` holds Cloudflare redirects for old WordPress URLs.
