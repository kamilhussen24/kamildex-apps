# kamildex-appsg

Static web pages for Kamildex apps, hosted on Cloudflare Pages.

## Contents

- `kbin-checker/privacy/index.html` — Privacy policy page for the **KBin Checker** Android app.
  It explains what the app sends (only the 6–8 digit BIN, over HTTPS, to a Cloudflare-hosted
  lookup service using HandyAPI), what stays on the device (history, favorites, settings), the
  single Internet permission, and contact details.
- `_headers` — Cloudflare Pages header rules applied to all routes: `X-Content-Type-Options`,
  `Referrer-Policy`, `X-Frame-Options: DENY` and a restrictive `Permissions-Policy`.

## Notes

- No build step: the files are served as-is.
- The privacy page is linked from the app's store listing, so its URL should stay stable.
- Contact: contact@kamildex.com — https://kamildex.com
