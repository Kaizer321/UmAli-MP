# UmAli redesign preview

UmAli is a static front-end prototype for a premium gaming marketplace. The current design intentionally contains no products, offers, sellers, prices, ratings, orders, reviews or sales metrics.

## Run locally

Open `index.html` directly, or serve this folder with any static file server. No Node.js installation is required for the pages themselves.

## Main surfaces

- `index.html` — original UmAli homepage and empty-market positioning
- `shop.html` — marketplace hub with search, filters and category entry points
- `category.html?type=currency` — category template for currency, accounts, top ups, items, boosting and gift cards
- `product.html` — future offer details empty state
- `storefront.html` — seller storefront shell with Shop, Reviews and About tabs
- `dashboard.html` — buyer workspace empty state
- `messages.html` — buyer/seller messaging shell
- `admin.html` — seller studio shell
- `admin-panel.html` — protected operations console shell
- `login.html` and `register.html` — account entry previews
- `about.html`, `contact.html`, `faq.html` — public brand and support pages
- `policies.html`, `returns.html`, `shipping.html` — protection and policy pages
- `track.html`, `cart.html`, `checkout.html` — future order flow empty states

## Data boundary

`data.js` contains empty arrays for future listings, sellers, orders and reviews. The UI is intentionally not populated with fictional marketplace activity. Forms and filters are visual previews only and do not store credentials, process payments, create orders or connect to a database.

Before launch, add a real backend, authentication, payment provider, moderation workflow, secure admin authorization, privacy policy and production legal review.
