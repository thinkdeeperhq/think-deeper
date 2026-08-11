# Think Deeper — static publication site

A zero-cost static website designed for GitHub Pages or Cloudflare Pages.

## Files
- `index.html` — homepage
- `essays/the-abundance-paradox/index.html` — Essay #001
- `about.html` — editorial identity and AI disclosure
- `corrections.html` — public corrections log
- `assets/styles.css` — complete responsive visual system

## Free deployment with GitHub Pages
1. Create a new public GitHub repository, e.g. `think-deeper`.
2. Upload/commit the contents of this folder to the repository root.
3. In GitHub: Settings → Pages.
4. Under Build and deployment choose `Deploy from a branch`.
5. Select `main` and `/ (root)`, then Save.
6. GitHub will publish the site at your free `github.io` address.
7. A custom domain can be connected later without rebuilding the site.

## Editing
The site has no framework, database or paid CMS. It is plain HTML/CSS so it can be hosted almost anywhere for free.

## Future upgrade path
When Essay #002 arrives, we can either:
- continue with static HTML for maximum simplicity, or
- migrate the essay content to Markdown using a static-site generator while preserving the visual design and URLs.
