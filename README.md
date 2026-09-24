# Adamya Sharma — Portfolio

A static, single-page portfolio site built from your CV. Plain HTML/CSS, no build step.

## Files
- `index.html` — page content
- `styles.css` — all styling

## Push to GitHub

```bash
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

## Deploy on Vercel
1. Go to vercel.com → **Add New Project**.
2. Import the GitHub repo you just pushed.
3. Framework preset: **Other** (it's static, no build command or output directory needed).
4. Click **Deploy**.

Every future push to `main` redeploys automatically.

## Before you publish
- Double-check the phone number and email in `index.html` (`#contact` and the sidebar) — remove either if you'd rather not have it public.
- Swap in a real headshot or project screenshots if you want images later; the layout doesn't require them.
