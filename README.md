# ShipHero (shiphero)

ShipHero is a warehouse management system (WMS) and fulfillment platform designed for eCommerce brands and third-party logistics (3PL) providers. The platform exposes a GraphQL public API with 69 queries, 120 mutations, and 599 types covering inventory, orders, shipments, purchase orders, returns, assembly products, and warehouse operations. Authentication uses JWT bearer tokens with a credit-based rate limiting system and support for 18 webhook event types.

APIs.json: [https://raw.githubusercontent.com/api-evangelist/shiphero/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/shiphero/refs/heads/main/apis.yml)

Naftiko: [https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=shiphero-api-evangelist&utm_content=repo](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=shiphero-api-evangelist&utm_content=repo)

## Tags

- Warehouse Management
- Fulfillment
- eCommerce
- GraphQL
- Inventory
- Orders
- Shipments
- 3PL
- Logistics

## APIs

### ShipHero GraphQL API

ShipHero's primary public API built on GraphQL, providing programmatic access to warehouse management data and operations including inventory, orders, shipments, purchase orders, returns, wholesale orders, assembly products, labor metrics, and billing.

- **Human URL:** https://developer.shiphero.com/
- **Base URL:** https://public-api.shiphero.com/graphql
- **Auth:** JWT Bearer Token (obtained via https://public-api.shiphero.com/auth/token)
- **Schema Reference:** https://developer.shiphero.com/schema/
- **Webhooks:** https://developer.shiphero.com/webhooks/

## Plans / Rate Limits / FinOps

- **Plans & Pricing:** [plans/shiphero-plans-pricing.yml](plans/shiphero-plans-pricing.yml)
- **Rate Limits:** [rate-limits/shiphero-rate-limits.yml](rate-limits/shiphero-rate-limits.yml)
- **FinOps:** [finops/shiphero-finops.yml](finops/shiphero-finops.yml)

Pricing tiers: Brand ($1,850/mo), 3PL ($1,995/mo), Enterprise+ ($2,750/mo). No free tier. API access is included in all subscription plans.

Rate limits: 4,004 credits per account (60 credits/second restore rate), 7,000 max requests per 5-minute window.

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://shiphero.com/ |
| Documentation | https://developer.shiphero.com/ |
| Getting Started | https://developer.shiphero.com/getting-started/ |
| GitHub Organization | https://github.com/Shiphero |
| LinkedIn | https://www.linkedin.com/company/shiphero |
| Blog | https://shiphero.com/blog |
| X (Twitter) | https://x.com/weareshiphero |
| Status Page | https://status.shiphero.com/ |

## Maintainers

- **Kin Lane** — kin@apievangelist.com
