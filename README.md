# just adds

Simple static website for the "just adds" project.

## What I added

- `.github/workflows/pages.yml` — GitHub Actions workflow to publish the site to GitHub Pages on push to `main`.
- `.nojekyll` — disable Jekyll processing on Pages.

## How to publish

1. Make sure your repo is pushed to GitHub and the default branch is `main` (or change the `branches` value in the workflow).
2. Push any changes to `main`. The workflow will run and publish the repository root to GitHub Pages.
3. The site will be available at: `https://<your-github-username>.github.io/<repository-name>` (replace placeholders accordingly).

## Custom domain

To use a custom domain, add a `CNAME` file in the repository root containing your domain, or set it in the repository's Pages settings.

## Notes

- This repo already includes `index.html`, `script.js`, `style.css`, and `sw.js`.
- The workflow uploads the repository root (so ensure files are where you expect them). If you want to publish from `docs/` or another folder, update the `path` used in the workflow.

---

If you'd like, I can commit these changes and push them to GitHub or open a pull request—tell me which option you prefer.