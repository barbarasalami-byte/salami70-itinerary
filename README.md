# Prof. Lilian Salami @70 — Cancún Celebration Itinerary

A premium interactive itinerary website for the celebration week.

## Deploying to Vercel

### Option 1 — Vercel CLI (fastest)
```bash
npm i -g vercel
cd salami70
vercel
```
Follow the prompts. Your site will be live in ~60 seconds at a `.vercel.app` URL.

### Option 2 — Vercel Dashboard (no code needed)
1. Go to [vercel.com](https://vercel.com) and sign in / create a free account.
2. Click **"Add New → Project"**.
3. Choose **"Deploy without a Git repository"** → drag and drop the `salami70` folder.
4. Click **Deploy**. Done!

### Option 3 — GitHub (best for updates)
1. Push this folder to a GitHub repo.
2. In Vercel, import the repo.
3. Vercel auto-deploys on every push.

## Customising
- All content is in `index.html` — easy to edit.
- Colours are in `:root` CSS variables at the top of the `<style>` block.
- No build step, no dependencies — pure HTML/CSS/JS.
