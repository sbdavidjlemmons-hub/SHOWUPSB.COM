# Show Up SB

Public civic-funnel site for [showupsb.com](https://www.showupsb.com/).

## Current source

- `index.html` — warm animated homepage, five action doors, Donation Station priority, public-funding registry, and boxed Ideas library.
- `stalwart-recovery.html` — sourced provider funding/outcomes review.
- `santa-barbara-bridge.webp` — original proof-of-concept Santa Barbara artwork.
- `stalwart-report.css` — research-page visual system.
- `robots.txt` and `sitemap.xml` — search discovery files.

The public pages expose a first-party `dataLayer` event interface. No GA4, GTM, Meta Pixel, heatmap, session replay, or advertising destination is installed until an account-specific ID is verified. Help and concern actions emit only a neutral `susb_secure_route_opened` event; sensitive intake is not hosted on the public page.

The site is static and served by GitHub Pages. Production publishing must preserve the `CNAME` and `.nojekyll` files on `gh-pages`.
