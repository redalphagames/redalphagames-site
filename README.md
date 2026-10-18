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
- Games: https://redalphagames.com/games.html
- Privacy Policy: https://redalphagames.com/privacy.html
- Account deletion: https://redalphagames.com/delete-account.html
- Terms and Conditions: https://redalphagames.com/terms.html

The custom domain must be connected to GitHub Pages through its DNS records.
Until then, the site is available through its `github.io` project URL.

## Updating the site

Push changes to `main`; GitHub Pages deploys them automatically. Review the
legal documents whenever company details, providers, governing law, or data
practices change. The deletion page is shared across supported RedAlpha Games
titles; verify its instructions and retention details against each shipped app.

This repository is the source of truth for the studio website and its privacy
and account-deletion pages. Do not maintain duplicate website files inside game
repositories. The account-deletion page documents in-app and support-email
request routes, background cleanup, temporary deletion-record retention, and
backup/log retention disclosures. Verify the public URLs after deployment before
submitting the associated Google Play declarations.
