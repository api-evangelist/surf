---
name: Build a market snapshot for an asset
description: Assemble a live market snapshot for a crypto asset with the Surf Data API — spot price, candles, market sentiment, and token holder distribution.
api: openapi/surf-openapi-original.json
operations:
  - exchange-price
  - exchange-candles
  - market-fear-greed
  - token-holders
---

# Build a market snapshot for an asset

Use the Surf Data API (`https://api.asksurf.ai/gateway/v1`) to snapshot an asset (e.g. `symbol=BTC`).

## Auth
`Authorization: Bearer sk-...` on every request.

## Steps
1. **`exchange-price`** — GET the current spot price for the `symbol` (optionally scope by `exchange`).
2. **`exchange-candles`** — GET OHLC candles for the `symbol` with an `interval` and `from`/`to` range.
3. **`market-fear-greed`** — GET the current market Fear & Greed index for macro context.
4. **`token-holders`** — GET the holder distribution for the token to gauge concentration.

## Conventions
- List endpoints page with `limit`/`offset`; some accept `cursor`.
- Credit tiers: light=1, standard=2, heavy=4 credits per call (see `conventions/surf-conventions.yml`).
- Handle `RATE_LIMITED` (100 req/min per key) with backoff.
