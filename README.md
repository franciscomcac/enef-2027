# ENEF 2027 — static site

Two pages, no build step:
- `index.html` — main site
- `contactos.html` — contacts page
- `assets/` — photos used by the site

## Push to GitHub

```bash
cd enef-2027-site
git init
git add .
git commit -m "ENEF 2027 site"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo-name>.git
git push -u origin main
```

(Create the empty repo first at github.com/new — don't initialize it with a README there, to avoid a merge conflict with the first push.)

## Deploy to Vercel

Once it's on GitHub, either:
- Import the repo at vercel.com/new, or
- Tell Claude the repo name (e.g. `yourname/enef-2027`) and it can link + deploy it via the Vercel connection already set up.

No build settings needed — it's a static site (framework: "Other" / none).
