# GitHub Hosting + SEO Setup

## 1) Push this folder to a GitHub repo

```bash
git add .
git commit -m "Add SEO-optimized landing page + GitHub Pages files"
git branch -M main
git remote add origin https://github.com/<your-user>/<your-repo>.git
git push -u origin main
```

## 2) Enable GitHub Pages

- Open **Repo → Settings → Pages**
- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/(root)**
- Save

Your site URL will be like:
- `https://<your-user>.github.io/<your-repo>/` (project page), or
- `https://<your-user>.github.io/` (user page)

## 3) Replace placeholder URLs for best SEO

Update these files to your final URL:
- `index.html` JSON-LD: `https://example.github.io/`
- `sitemap.xml` `<loc>` value

## 4) Submit sitemap to search engines

After site is live:
- Google Search Console → add property → submit `sitemap.xml`
- Bing Webmaster Tools → submit `sitemap.xml`

## 5) Keep content fresh

Search engines rank freshness + utility. Keep this page updated and add useful explanatory content over time.
