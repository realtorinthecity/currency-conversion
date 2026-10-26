# FX Convert

A responsive currency toolkit with currency conversion, historical exchange-rate charts, a calculator, and mortgage estimates. It follows the device's light/dark appearance preference.

## Files to upload

- `index.html` — complete application (HTML, CSS, and JavaScript).
- `README.md` — setup and deployment instructions.
- `favicon.ico`, `favicon-16.png`, `favicon-32.png` — browser icons.
- `apple-touch-icon.png` — iOS home-screen icon.
- `icon-192.png`, `icon-512.png` — app icons.
- `site.webmanifest` — installable-app metadata.
- `.nojekyll` — tells GitHub Pages not to run Jekyll processing.

## Deploy to GitHub Pages

1. Download and unzip this package.
2. Upload **all files inside the `fx-convert-github-ready` folder** to the root of your GitHub repository. Ensure `index.html` is at the repository root, not nested in another folder.
3. In GitHub, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select your branch (usually `main`) and folder `/(root)`, then save.
6. Wait for GitHub Pages to publish and open the URL shown in the Pages settings.

## Data and limitations

- Live exchange rates and historical data are retrieved from external services configured in `index.html`; an internet connection is required.
- Historical availability depends on the external provider and currency pair.
- Exchange rates are indicative and are not a guaranteed transaction quote. Mortgage calculations are estimates and may exclude lender fees, insurance, taxes, and other costs.
- Screenshot sharing uses browser/device capabilities; where native sharing is unavailable, the app may download the screenshot instead.

No build step or backend is required.
