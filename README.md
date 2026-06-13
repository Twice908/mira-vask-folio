# Mira Vask Folio

This repository contains a simple static website built from `mira-vask-folio.html`.

## Deployment

A GitHub Actions workflow is configured to deploy the site to GitHub Pages automatically when changes are pushed to the `main` branch.

### Workflow

- File: `.github/workflows/deploy.yml`
- Trigger: `push` on `main`
- Deploys the repository root to GitHub Pages using GitHub Actions

## Usage

1. Push changes to the `main` branch.
2. GitHub Actions will build and deploy the site.
3. The site will be available via GitHub Pages once the workflow completes.

## Notes

- The main website source file is `mira-vask-folio.html`.
- If you want the site to load at the repository root, you can rename or copy it to `index.html`.
