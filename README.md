# Nick the Tile Man — Website

A mobile-first, single-page website with an interactive tile design builder.

## Deployment

### Vercel (Recommended)
1. Push this folder to a GitHub repo
2. Import the repo on [vercel.com](https://vercel.com)
3. Vercel auto-detects static — click **Deploy**

Or via Vercel CLI:
```bash
npm i -g vercel
cd this-folder
vercel
```

### Netlify
Drag and drop this folder onto [netlify.com/drop](https://app.netlify.com/drop)

### Any Static Host
Upload `index.html` + `vercel.json` (optional on non-Vercel hosts).

## Files
- `index.html` — Complete website (self-contained, no dependencies)
- `vercel.json` — Vercel routing + security headers config
- `README.md` — This file

## Features
- Mobile-first responsive design (320px → 1440px+)
- Interactive Tile Pattern Builder (Canvas-based)
- Upload your own tile texture
- Full portfolio gallery with lightbox
- Animated hero with tile snap-in effect
- Sticky CTA bar + fullscreen mobile nav
- Click-to-call + SMS links
- Contact form with photo upload
