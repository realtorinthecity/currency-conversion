# FX Convert

A responsive, dark fintech-style currency toolkit featuring currency conversion, exchange-rate history, calculator, and mortgage estimates.

## Files
- `index.html` — main application.
- `favicon.ico`, `favicon-16.png`, `favicon-32.png` — browser tab icons.
- `apple-touch-icon.png` — icon for iOS home-screen bookmarks.
- `icon-192.png`, `icon-512.png` — app icons referenced by the web app manifest.
- `site.webmanifest` — app name, theme, launch behavior, and icon declarations.
- `.nojekyll` — helps GitHub Pages serve static files without Jekyll processing.

## Deploy with GitHub Pages
1. Upload all files in this folder to the **root** of your GitHub repository.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select your branch (usually `main`) and folder `/ (root)`, then save.
5. Wait for deployment to finish and open the published Pages URL.

## Notes
- This is a static app and does not require a build step or backend.
- Live exchange rates and historical data depend on external services configured in `index.html` and require internet access.
- Icon paths are relative, so they work on GitHub Pages project URLs.
- Exchange rates are indicative and are not a guaranteed transaction quote.
