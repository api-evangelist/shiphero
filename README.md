# ShipHero (shiphero)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
