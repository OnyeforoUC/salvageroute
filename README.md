# SalvageRoute

A deal calculator for buying damaged cars at US salvage auctions (Copart, IAAI), shipping them abroad, repairing them and reselling.

Pick a car, damage level, auction, export port, towing distance, shipping method and destination. The app shows:

- Import taxes, line by line, for each destination
- Total landed cost, resale value, profit/loss and ROI
- Break-even selling price in local currency
- Principal needed, with a contingency buffer
- Import eligibility checks (age limits, salvage bans, left-hand-drive bans)
- A side-by-side ranking of every destination for the same car
- Saved deals (stored in the browser)

## Destinations

Nigeria, Ghana, Ukraine, Georgia, Poland (EU), Dominican Republic, UAE, plus a Custom option for any country. Jamaica and Kenya are listed as blocked.

Tax rules and exchange rates reflect October 2026. Rates change often; confirm with a licensed customs broker before buying. Not financial, legal or tax advice.

## Run it

It is a single static file. Open `index.html` in a browser, or serve it with any static host (GitHub Pages, Netlify, Vercel).

## Roadmap to SaaS

- User accounts and cloud-saved deals (e.g. Supabase)
- Live exchange-rate API
- Admin-editable tax-rule database per country
- Stripe subscriptions (free tier + Pro)
- Auction listing import and clearing-agent marketplace
