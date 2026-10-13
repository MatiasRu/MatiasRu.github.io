# Matias Ruiz - academic website

## Publish with GitHub Pages

1. Download and extract this ZIP on your computer.
2. Sign in to GitHub as Matias-Ruiz. Create a public repository named `matias-ruiz.github.io`. If it already exists, use that repository and review existing files before replacing them.
3. In the repository, select Add file > Upload files (or the uploading an existing file link for an empty repository).
4. Drag the extracted `index.html`, `assets` folder and `README.md` into the upload area. Include `.nojekyll` if visible. Keep the assets folder intact. Upload the contents of the extracted folder, not the ZIP or its outer folder.
5. Commit the files to the main branch. Confirm that index.html appears at the repository root and the CV is at assets/Matias-Ruiz-CV.pdf.
6. Open Settings > Pages. Under Build and deployment, set Source to Deploy from a branch, Branch to main, and folder to / (root). Click Save.
7. GitHub will provide the published link: https://matias-ruiz.github.io/ . Allow up to 10 minutes for publishing. Check the Actions tab if a deployment fails.
8. Open the live site and check Home, all three Research tabs, Teaching, Get in touch and the CV link.

No installation, theme, build command or paid hosting is needed for this public repository. No custom domain is required.

## Package contents

- index.html: the production website, with embedded portrait, logo and book cover.
- assets/Matias-Ruiz-CV.pdf: the latest supplied CV, unchanged. The CV navigation link opens this file directly.
- Other assets: original portrait, university logo and book cover, retained for future edits.
- .nojekyll: tells GitHub to serve these static files directly. No Jekyll configuration is needed.
- README.md: these instructions.

The separate Matias-Ruiz-academic-website.html chat preview is NOT the production index.html. It includes rendered PDF pages to support the chat preview environment. Use the index.html in this ZIP for GitHub.

## Later updates

- Replace assets/Matias-Ruiz-CV.pdf with a new PDF using exactly the same filename to update the CV.
- Edit the corresponding sections of index.html for biography, teaching, talks and contact text.
- Research uses Interests, Publications and Talks subpages. Publications is a continuous list with Monograph first and Papers next.
- Commit changes to main; GitHub Pages republishes automatically.

Official instructions: https://docs.github.com/en/pages/quickstart
Publishing settings: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
