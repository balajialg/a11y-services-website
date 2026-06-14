# Campus Accessibility Intelligence Website

A lightweight static website designed for sharing with:
- Digital accessibility experts at US universities
- CIO, procurement, and budget decision leaders

## Included
- Strategic messaging for AI-based agentic accessibility services
- References to:
  - https://github.com/berkeley-dsep-infra/jupyterlab-a11y-checker
  - https://jupycheck.vercel.app/
  - https://pdfremediationagent.vercel.app/
- Ready deployment options:
  - Vercel (`vercel.json` included)
  - GitHub Pages (GitHub Actions workflow included)

## Publish immediately on Vercel
1. Open terminal in this project folder.
2. Run:
   ```powershell
   npm i -g vercel
   vercel --prod
   ```
3. Follow login + project prompts.
4. Share the generated URL.

## Publish on GitHub Pages
1. Create a new GitHub repo and push this folder to the `main` branch.
2. In GitHub repo settings, enable Pages with source set to GitHub Actions.
3. Push triggers `.github/workflows/deploy-pages.yml`.
4. Share the Pages URL shown in workflow output.

## Customize quickly
- Update CTA email in `index.html`.
- Adjust branding colors in `styles.css` under `:root` variables.
- Edit service positioning copy in the `#services` and `#contact` sections.
