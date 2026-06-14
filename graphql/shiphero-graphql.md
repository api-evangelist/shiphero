# ShipHero GraphQL API

ShipHero exposes a single GraphQL endpoint that provides programmatic access to warehouse management and fulfillment operations. The API covers inventory, orders, shipments, purchase orders, returns, wholesale orders, locations, totes, labor metrics, and billing. It includes 69 queries and 120 mutations spanning 599 types, and enforces a credit-based complexity system that lets callers analyze query cost before execution.

**Endpoint:** https://public-api.shiphero.com/graphql

**Authentication:** JWT bearer token. Obtain an access token by posting your username and password credentials to the authentication endpoint. Tokens are valid for 28 days and can be renewed using a refresh token. Include the token in the `Authorization: Bearer <token>` header on every request.

**Rate Limiting:** Credit-based system. Each query or mutation has a complexity cost; accounts are allotted a credit budget per period. Use the `analyze: true` argument on any query to retrieve the complexity score before execution.

**Webhooks:** 18 event types supported for real-time notifications on fulfillment workflow changes.

**Documentation:** https://developer.shiphero.com/

**References:**
- Documentation: https://developer.shiphero.com/
- GettingStarted: https://developer.shiphero.com/getting-started/
- GraphQLPrimer: https://developer.shiphero.com/graphql-primer/
- GraphQLSchema: https://developer.shiphero.com/schema/
- Webhooks: https://developer.shiphero.com/webhooks/
