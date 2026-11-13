# Dubai Gold Connect — Demo MVP

A private-concept B2B gold sourcing demonstration. **All supplier profiles are fictional.** No gold is sold, no payment is taken, no live pricing is displayed, and no real suppliers are contacted.

## Architecture

- Frontend: GitHub Pages, static `index.html`.
- Backend: Cloudflare Worker (separate read-only demo API under `api/`).
- Source: GitHub repository `zmehanna/dubai-gold-connect`.
- Stripe: disabled and not connected.
- Demo RFQs: browser localStorage only. **Never enter real confidential business or personal data.**

## Demo scope

- Landing page, sample supplier directory, supplier category filter.
- RFQ demo form, validation, local status dashboard.
- Responsive UI. English first.
- Backend health and category endpoints, no account database and no write endpoints.

## Production blockers

Before real supplier onboarding or external commercial use: legal licensing assessment, AML/sanctions/KYB, gold-origin due diligence, authenticated users, secure backend storage and audit trail, verified suppliers, consent/privacy policy, commercial terms and compliance screening.

## Development

Open `index.html` in a browser. For API deployment from `api/`, run `npx wrangler deploy` (requires Cloudflare authentication). GitHub Pages deploys the repository root of branch `main`.
