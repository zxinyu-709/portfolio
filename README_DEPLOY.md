# Portfolio website — GitHub Pages deployment

This folder is a static GitHub Pages portfolio. It uses only HTML, CSS, and local image/GIF assets, so no build step is required.

## Files

- `index.html` — main one-page portfolio
- `styles.css` — visual style and responsive layout
- `assets/` — supplied portfolio images and GIFs
- `.nojekyll` — prevents GitHub Pages from running Jekyll processing

## Before publishing

1. In `index.html`, replace the hero headline, profile text, project descriptions, and contact email.
2. For the three Google Drive videos, set sharing permission to **Anyone with the link can view**. Otherwise the embedded players may show a permission error.
3. The Auckland hero image is loaded from Wikimedia Commons. Replace `--hero-image` in `styles.css` with your own photo URL or a local `assets/hero-auckland.jpg` if you prefer.

## Deploy through GitHub Pages

Option A: user or organization site

1. Create a repository named `<your-github-username>.github.io`.
2. Upload all files in this folder to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose the `main` branch and the `/ (root)` folder.
6. Save. Your site should be available at `https://<your-github-username>.github.io/` after GitHub finishes deployment.

Option B: project site

1. Create any repository name, for example `portfolio`.
2. Upload all files in this folder to the repository root.
3. In **Settings → Pages**, choose `main` and `/ (root)`.
4. Your site should be available at `https://<your-github-username>.github.io/<repository-name>/`.

## Notes

- The embedded website uses: `https://cybird-d.github.io/AI-Model-LLM-Timeline/`
- The Google Drive videos use `/preview` URLs for embedding.
- If a browser blocks an iframe, the portfolio includes external links as fallback.
