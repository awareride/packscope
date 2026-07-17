# Packscope GitHub Pages

This folder powers the Packscope website at
**https://open.awareride.com/packscope/**.

## Files

- `index.html` — landing page
- `styles.css` — site styles
- `assets/` — icons and images
- `.nojekyll` — disables Jekyll processing so assets are served as-is

## Publish

1. Push the `docs/` folder to the `main` branch.
2. In the GitHub repository, go to **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose the `main` branch and the `/docs` folder, then click **Save**.

GitHub Pages will build and serve the site from `docs/`.
