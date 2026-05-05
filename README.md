# LA 2028 Traffic CA — Vercel Site

## Deploy in 3 steps

### Option A — Vercel CLI (fastest)
```bash
npm i -g vercel
cd ca-traffic-site
vercel --prod
```
### Option B — Vercel Dashboard (no CLI)
1. Go to https://vercel.com/new
2. Click "Deploy without a Git repository" → "Upload files"
3. Drag this whole folder in
4. Click Deploy

## Files
- `index.html` — the entire simulation (self-contained)
- `vercel.json` — tells Vercel this is a static site
