# Dubai Gold Connect — Premium B2B Concept MVP V0.2

A responsive **private B2B gold sourcing demonstration** designed for partner discussions.

## Live architecture
- **Website:** GitHub Pages, static HTML/CSS/JavaScript.
- **Source:** GitHub `zmehanna/dubai-gold-connect`.
- **Read-only API:** Cloudflare Worker `dubai-gold-connect-api` (health and categories).
- **Stripe:** not integrated.
- **RFQs:** browser localStorage only, **not sent to any external service**.

## Demo journey
- Editorial premium landing page (dark emerald, understated gold)
- Responsive navigation and mobile menu
- Supplier catalogue with fictional sample suppliers and category filtering
- Supplier-to-RFQ preselection
- RFQ form with input validation
- Local RFQ dashboard with draft status
- Worker health status in the announcement strip

## Validation
`node --check app.js`; optional browser smoke test with `node smoke-test.cjs` (requires playwright and Microsoft Edge installed).

## Legal and technical boundaries
All supplier profiles are fictional and are marked as such. No prices, actual inventory, authenticated users, supplier contact, payments, brokerage or trades are supported. Do **not** enter real client data into the demo. Before any commercial launch: legal assessment, AML/KYB/sanctions, supply-chain due diligence, verified supplier onboarding, authentication, controlled API writes, secure persistent database, privacy and commercial terms.
