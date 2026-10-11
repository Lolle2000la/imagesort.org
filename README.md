# imagesort.org

Source for the [imagesort.org](https://imagesort.org) website — the documentation
and landing page for the **legacy (WPF/.NET) version** of Image Sort.

Image Sort is being rewritten in Rust and renamed to **Media-Sort**; that project
gets a new website. This repository keeps the original site available so the old
version's documentation stays online.

## Contents

This repository is a GitHub Pages (Jekyll) site served from the repository root.
It was split out, with history, from the `docs/` folder of
[`Lolle2000la/Image-Sort`](https://github.com/Lolle2000la/Image-Sort).

| File | Purpose |
|------|---------|
| `index.md` | Home page |
| `help.md`, `help/help.de.md` | Getting-started guide (EN/DE) |
| `privacy_policy.md` | Privacy policy |
| `_config.yml` | Jekyll configuration (`jekyll-theme-slate`) |
| `CNAME` | Custom domain (`imagesort.org`) |
| `sitemap.xml`, `sitemap.html`, `ror.xml` | Sitemap / crawler files |
| `google1896f4f871f455a4.html` | Google Search Console verification |

Pages and images are referenced from the main app repository via absolute URLs, so
`sitemap`/`help` screenshots continue to resolve.

## Managing the site

The site is plain Markdown rendered by GitHub Pages. Edit the Markdown files and
push to the default branch; Pages rebuilds automatically.
