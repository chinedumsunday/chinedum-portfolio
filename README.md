# chinedumsunday.dev

Personal portfolio — data engineering.

Static site, no build step. Open `index.html` in a browser or serve the folder.

```
python3 -m http.server 8000
```

## Files

- `index.html` — the site
- `support.js` — runtime for the component format the page is authored in
- `image-slot.js` — image placeholder element (portrait)
- `uploads/` — CV PDF

## Deploy

GitHub Pages: Settings → Pages → Deploy from branch → `main` / root.
Any static host (Netlify, Vercel, Cloudflare Pages) works with no configuration.
