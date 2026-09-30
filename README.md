# RedAlpha Games website

The official static website for RedAlpha Games. It contains the studio landing
page, Privacy Policy, Terms and Conditions, and a custom 404 page.

The site has no build step, framework, cookies, external fonts, or trackers.
GitHub Pages publishes the files directly from the root of the `main` branch.

## Preview locally

```powershell
python -m http.server 8080
```

Then open `http://localhost:8080`.

## Public URLs

- Website: https://redalphagames.com
- Privacy Policy: https://redalphagames.com/privacy.html
- Terms and Conditions: https://redalphagames.com/terms.html

The custom domain must be connected to GitHub Pages through its DNS records.
Until then, the site is available through its `github.io` project URL.

## Updating the site

Push changes to `main`; GitHub Pages deploys them automatically. Review the
legal documents whenever company details, providers, governing law, or data
practices change.
