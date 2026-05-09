# Primis Landing

Static landing page for Primis Compute.

## Files

- `index.html` - standalone landing page
- `primis-logo-transparent.svg` - logo asset

## Waitlist

The waitlist form posts to Formspree:

```html
action="https://formspree.io/f/xlgzorbb"
```

## Deploy

Push this folder to a GitHub repo and connect it to Vercel, Netlify, or Cloudflare Pages.

For Vercel:

```bash
cd primis-landing
git init
git add .
git commit -m "Launch Primis landing page"
git branch -M main
git remote add origin YOUR_REPO_URL
git push -u origin main
```

Then import the repo in Vercel as a static site. No build command is required.
