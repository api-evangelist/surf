---
name: Query on-chain data with SQL
description: Run analytical SQL over Surf's on-chain data warehouse (58 tables) using the Surf Data API's Onchain domain.
api: openapi/surf-openapi-original.json
operations:
  - onchain-schema
  - onchain-sql
  - onchain-structured-query
---

# Query on-chain data with SQL

Use the Surf Data API (`https://api.asksurf.ai/gateway/v1`) Onchain domain to query raw chain data.

## Auth
`Authorization: Bearer sk-...`. On-chain SQL is a **heavy** endpoint (4 credits/call).

## Steps
1. **`onchain-schema`** — GET the catalog of available on-chain tables and columns (58 tables) before writing a query.
2. **`onchain-sql`** — Submit a SQL query against the on-chain warehouse. Filter and `limit` aggressively — heavy scans cost more.
3. **`onchain-structured-query`** — For non-SQL callers, submit a structured (typed) query instead of raw SQL.

## Conventions
- These are POST query endpoints; the rest of the Data API is GET.
- Errors follow `{ "error": { "code", "message" } }`; a bad query yields a 400.
- Results within a 3-minute window are cached (free re-fetch).
- See `data-model/surf-data-model.yml` for entity/identifier relationships.
