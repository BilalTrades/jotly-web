# jotly landing page

A responsive, self-contained landing page. Open index.html in a browser or serve it with any static web host. It needs no npm installation, JavaScript framework, API key, tracking service, or runtime CDN. The screenshot, original SVG icons and Plus Jakarta Sans fonts are embedded in index.html. Font license included as FONT-LICENSE.txt.

## Publish free with GitHub Pages (separate website repository)

1. Create a PUBLIC repository named `jotly-web` in your BilalTrades account.
2. Upload `index.html` to its ROOT (not inside another folder). Include FONT-LICENSE.txt.
3. Open repository Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Select main and / (root), then Save.
6. Wait for the Pages deployment to finish. The expected address is https://bilaltrades.github.io/jotly-web/ — use the exact published URL GitHub shows.
7. Add that URL to Instagram Links and to the app repository's About > Website field.

Do not replace the desktop project's index.html: this is a separate marketing website. If you prefer hosting within the existing jotly repo, put this website in docs/index.html and set Pages to main /docs instead. Check your existing Pages configuration before changing it.

## Current destinations

Download buttons: https://github.com/BilalTrades/jotly/releases/latest
Source: https://github.com/BilalTrades/jotly
Guide: https://github.com/BilalTrades/jotly#readme
Feedback: https://github.com/BilalTrades/jotly/issues
Instagram / founder: https://www.instagram.com/bilal_tradess/

Download buttons open the GitHub release page, not a guessed executable URL. Users choose the Windows asset there. No version number is hardcoded, so links keep following the latest published release. External link availability and release assets were not verified during this website build.

## Content and editing

Edit visible text and links directly in index.html. The stylesheet is inline. Large base64 strings contain the image and bundled fonts; leave them unchanged unless replacing those assets.

The site explains local storage honestly: journals and backups are not encrypted, backups are user-triggered, and MT imports are CSV-based rather than broker API connections. There is no contact form or email collection. The GitHub / Instagram destinations have their own policies. Footer copyright year is static.

## Checks completed

- Desktop: 1440px wide
- Mobile: 390px wide, no horizontal overflow
- FAQ native details/summary interaction
- No browser runtime errors
- Reduced-motion preference supported

Created for Bilal_tradess.
