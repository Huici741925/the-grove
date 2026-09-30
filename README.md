# The Grove

A responsive Singapore home-business discovery frontend, with customer and business-owner interfaces, an animated Grove mascot, recommendations, maps, chain rewards, appointments, finance tracking and a local assistant.

This is the restored design selected by the project owner.

## View the website

Enable GitHub Pages in **Settings → Pages → Deploy from a branch → main → /(root)**. GitHub displays the live website address once deployment finishes. Open the address with `#/landing` to visit the homepage.

## Run locally

```sh
python3 -m http.server 4173 --bind 127.0.0.1
```

Open http://127.0.0.1:4173/#/landing.

## Try the interfaces

Create a customer account with a test password. Explore customer pages, then open Settings → Sign up as business to access the business studio. Accounts and changes are stored in the visitor’s own browser, not shared between devices. Your friends create their own accounts; no account data from the developer’s browser is included in this repository.

## Files

- `index.html`: application entry point.
- `app.js`, `grove.js`, `brand-v3.js`, `motion-v4.js`: interface and local interaction logic.
- `styles.css`, `grove.css`, `brand-v3.css`, `motion-v4.css`: responsive layouts and motion.
- `assets/`: mascot artwork, logo, and vendored map/QR libraries.

## Project boundaries

This is a frontend prototype with illustrative business listings and synthetic analytics. Browser-local account checks are not production authentication. No payment processing, shared database, email reminders or external AI service is connected. Use test credentials and fictional information only. A backend is required for real customer accounts and transactions.

Maps use Leaflet and OpenStreetMap tiles; photography uses Unsplash, and fonts load from Google Fonts. These require internet access. Mascot illustrations were generated for this project. Third-party libraries retain their original notices.
