# Mindmap Infinite website

Public, search-friendly landing page and privacy policy for the Mindmap Infinite Android app.

- Live website: https://milkyway45.github.io/mindmap-infinite-site/
- Privacy policy: https://milkyway45.github.io/mindmap-infinite-site/privacy.html
- Public website and release updates: https://github.com/milkyway45/mindmap-infinite-site

The site is static HTML/CSS and deploys to GitHub Pages from `main` through GitHub Actions. Search metadata includes canonical URLs, Open Graph/Twitter cards, JSON-LD software and FAQ schemas, `robots.txt`, and an XML sitemap. It contains no credentials, third-party font requests, advertising, or analytics.

After deployment, the site owner can verify the site in Google Search Console and Bing Webmaster Tools, then submit `https://milkyway45.github.io/mindmap-infinite-site/sitemap.xml`. Search engine indexing and ranking are not immediate or guaranteed.

## Local preview

From this directory, run:

```powershell
python -m http.server 8000
```

Then open http://localhost:8000.

## Publishing

Every push to `main` deploys the site through `.github/workflows/pages.yml`. The Play Store release is not live yet; the landing page intentionally says it is coming soon.
