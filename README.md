# Tyson Mulwa — Portfolio

Personal portfolio site. A single, self-contained static page — no build step, no dependencies. All CSS, the animated "glitter" node-field, and the liquid-glass UI are inlined in `index.html`.

## Deploy on Vercel

**Dashboard**
1. Push this repo to GitHub (origin: `github.com/tysonmulwa/Tyson-fortfolio`).
2. In Vercel → **Add New… → Project → Import** this repo.
3. **Framework Preset:** `Other` · **Build Command:** *(leave empty)* · **Output Directory:** `./` (root).
4. **Deploy.** Vercel serves `index.html` at `/`.

**CLI**
```bash
npm i -g vercel
vercel          # preview deploy
vercel --prod   # production deploy
```

## Files

| File | Purpose |
|---|---|
| `index.html` | The entire site — markup, styles, canvas glitter, and liquid-glass cards |
| `favicon.svg` | Emoji favicon |
| `vercel.json` | Static hosting config (clean URLs) |

## Contact

- **Email:** tysonmulwa25@gmail.com
- **WhatsApp:** +254 703 739265
- **GitHub:** [github.com/tysonmulwa](https://github.com/tysonmulwa)
