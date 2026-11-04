# HouseKit-Site

The website for HouseKit, served by GitHub Pages at **https://housekitapp.com**
(myhousekit.com redirects here from `CrankyNerd24/myhousekit-redirect`).

| Page | File |
|---|---|
| About (home) | `housekit.html` (`index.html` forwards to it) |
| User Manual | `manual.html` |
| Support | `support.html` |
| Privacy Policy | `privacy.html` |
| Not found | `404.html` |

`favicon.svg`, `favicon-32.png` and `apple-touch-icon.png` are the app icon; the
logo in each page's header is drawn from the same icon. `CNAME` holds the custom domain and `.nojekyll` serves the files as they are.
Pages: Settings ▸ Pages ▸ Source: **GitHub Actions**. `.github/workflows/pages.yml`
publishes on every push to `main`; to republish by hand, open Actions ▸ Publish site ▸
Run workflow.

The app's source lives in a separate private repository; App Store Connect's
Support and Privacy URLs point at this site, so keep it public.
