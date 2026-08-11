# Craftify Website

Single-file static site (index.html) — the Craftify marketing page, built
to match the official brand guidelines (logo, colors, offers).

## Deploy to Vercel

1. Push this folder to a new GitHub repo (see commands below).
2. Go to vercel.com → **Add New Project** → **Import Git Repository** → select the repo.
3. Framework preset: **Other** (it's a static file, no build step needed).
4. Click **Deploy**. Vercel will serve index.html automatically.

## Push to GitHub

```bash
cd craftify-repo
git init
git add .
git commit -m "Craftify website"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

Then import that repo in Vercel as described above.
