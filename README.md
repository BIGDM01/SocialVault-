# SocialVault starter website

A responsive static website starter for a social-account marketplace concept.

## Included pages
- `index.html` — homepage and platform categories
- `marketplace.html` — browse/filter sample listings
- `listing.html` — listing details and local demo offer
- `login.html`, `signup.html` — demo-only local account flow
- `sell.html` — create a local demo listing
- `dashboard.html`, `profile.html`
- `checkout.html` — demo order summary, no payment processing
- `negotiations.html` — local demo offers
- `assets/style.css`, `assets/app.js`, `assets/config.js`

## Deploy on Vercel
1. Upload the contents of this folder to the root of your GitHub repository.
2. In Vercel, import that repository.
3. For a plain HTML site, use the Other framework preset (or no framework), with no build command and output directory `.`.
4. Deploy.

## Important limitations
This is a front-end starter, not a production marketplace. Demo accounts, listings, wallet address, and offers are stored in the current browser's localStorage and are not shared between visitors. No real authentication, database, seller verification, escrow, or payment processing is enabled. Configure Supabase and create secure row-level-security policies before handling real user data. Never place a Supabase service-role key or wallet private key in frontend code.

Only facilitate account transfers where permitted by the relevant platform's terms and applicable law.