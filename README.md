# blog

A minimal [Eleventy](https://www.11ty.dev/) blog inspired by the **eleventy-excellent** starter and configured for GitHub Pages deployment.

## Local development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

The static site is generated into `_site`.

## GitHub Pages deployment

This repository includes `.github/workflows/deploy.yml`.

1. Push to the `main` branch.
2. In repository settings, set **Pages → Build and deployment → Source** to **GitHub Actions**.
3. The workflow builds with Eleventy and deploys the `_site` output to GitHub Pages.
