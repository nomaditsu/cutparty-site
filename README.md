# cutparty.com

Marketing site for **CutParty** (macOS app). Static HTML/CSS, served by GitHub Pages on the custom domain `cutparty.com`.

## Structure
- `index.html` — one-pager
- `support.html` — support page (App Store Support URL)
- `privacy.html` — privacy policy
- `styles.css` — shared styles (Poppins, minimalist, confetti accent)
- `assets/shots/` — App Store screenshots, resized for web
- `CNAME` — custom domain for GitHub Pages

## Local preview
Open `index.html` in a browser, or run `python3 -m http.server` in this folder.

## Deploy
Pushing to the default branch publishes via GitHub Pages. DNS for `cutparty.com`
points at GitHub Pages (apex A records + `www` CNAME).

## Notes
- The App Store button links to the CutParty listing (live once the app is approved).
- Contact email: support@cutparty.com (ensure it forwards to a monitored inbox).
