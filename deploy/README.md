# Best Buy Real Estate — Vercel deploy

## Deploy in 30 seconds

### Option A — Drag & drop (no account setup needed)
1. Go to https://vercel.com/new
2. Drag this whole folder into the import box
3. Click **Deploy**

### Option B — Vercel CLI
```bash
cd deploy
npx vercel          # first-time preview deploy
npx vercel --prod   # deploy to production
```

### Option C — GitHub
1. Create a new public repo on GitHub
2. Upload the contents of this folder (`index.html`, `vercel.json`)
3. In Vercel: **New Project → Import Git Repository → Deploy**

## Files
- `index.html` — the full Best Buy Real Estate site
- `vercel.json` — minimal Vercel config (clean URLs)
