# Portfolio Site

A static, single-page portfolio for an IT professional. No build step, no dependencies — just `index.html`, `styles.css`, `script.js`.

## Local preview
Open `index.html` directly, or run a tiny local server:

```bash
# Python
python3 -m http.server 8000
# Node (if installed)
npx --yes serve .
```

Then visit http://localhost:8000.

## What to edit
1. `index.html`
   - Replace **Your Name**, the hero copy, About text, Skills, Projects, Experience, Certifications, and Contact links.
   - Update the `<meta name="description">` and `<title>`.
   - Update social links (`mailto:`, LinkedIn, GitHub, résumé file name).
2. `styles.css` — change the accent colors at the top in `:root`:
   - `--accent`, `--accent-2`, `--accent-grad` control the highlight color/gradient.
3. Drop a `resume.pdf` next to `index.html` to make the "Download résumé" button work.

## Hosting options
See the chat conversation, but in short: GitHub Pages, Netlify, Vercel, or Cloudflare Pages all host this for free and let you attach a custom domain or subdomain.
