# Aboringblog (Typlog export)

This is a **no-build** static website generated from a Typlog JSON export.

## What you get
- `index.html` (home + search)
- `posts/<slug>/index.html` (one folder per post)
- `tags/` pages
- `feed.xml` (RSS)

## Publish on GitHub Pages (fastest)
1. Create a new GitHub repo (public is easiest).
2. Upload **all files** in this folder to the repo root (or push with git).
3. In GitHub: **Settings → Pages**
   - Source: **Deploy from a branch**
   - Branch: `main` and folder `/ (root)`
4. Your site URL will look like:
   - `https://<username>.github.io/<repo>/`

## IMPORTANT: Update RSS base URL
Edit `feed.xml` and replace:
`https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPO`
with your real GitHub Pages URL.

## Customize
- Site title/description are inside `index.html` and each page header (generated).
- Styles are in `assets/style.css`.

Generated automatically from: `aboringblog.typlog.json`
