---
name: Analyze a crypto wallet
description: Pull a full intelligence picture for a wallet address using the Surf Data API — balances, net worth, DeFi positions, and transfer history across 40+ chains.
api: openapi/surf-openapi-original.json
operations:
  - wallet-detail
  - wallet-net-worth
  - wallet-transfers
  - wallet-protocols
---

# Analyze a crypto wallet

Use the Surf Data API (`https://api.asksurf.ai/gateway/v1`) to profile a wallet.

## Auth
Send `Authorization: Bearer sk-...` on every request. Without a key you still get 30 free credits/day per IP.

## Steps
1. **`wallet-net-worth`** — GET the total USD net worth for the `address` (pass `chain` to scope, or omit for multi-chain).
2. **`wallet-detail`** — GET the full breakdown: EVM/Solana balances, tokens, labels, NFTs, active chains, approvals. Note that individual fields can fail independently (see `WalletDetailError` — a `field`/`message` object embedded in a 200 response); handle per-field gaps.
3. **`wallet-protocols`** — GET the wallet's DeFi protocol positions.
4. **`wallet-transfers`** — GET transfer history; page with `limit` (max 100) and `offset`.

## Conventions
- Pagination is `limit`/`offset` (see `conventions/surf-conventions.yml`).
- Errors use `{ "error": { "code", "message" } }` (see `errors/surf-error-codes.yml`); watch for `RATE_LIMITED` (429) and `PAID_BALANCE_ZERO` (402).
- Repeating the same call within 3 minutes is free (cached).
