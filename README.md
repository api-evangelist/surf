# Surf

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

Surf (asksurf.ai) is a crypto-focused AI research and execution platform that exposes its intelligence as a developer API. The Surf Data API ("Hermod" gateway) provides 119 typed REST endpoints across 14 domains — exchange and market data, tokens, DeFi projects, wallets, on-chain SQL, social signals, news, funds, prediction markets (Polymarket/Kalshi), Hyperliquid perps, search, and web fetch — covering 40+ blockchains and 200+ data sources. A separate OpenAI-style Chat API (surf-2.0 / surf-2.0-instant models) answers natural-language crypto research questions with citations. Access is via a single Bearer API key with credit-based billing (30 free credits/day, no signup), and the platform ships a Go CLI, an MCP server, an Agent Skill, and a TypeScript SDK. Surf is backed by Pantera Capital.

**Areas:** Company · Cryptocurrency · Blockchain · Market Data · On-Chain Analytics · Wallet Intelligence · Artificial Intelligence · DeFi · Prediction Markets · Developer API

## Surf on APIs.io

Everything profiled for Surf is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/surf/](https://apis.io/providers/surf/)** — or go straight to one of the APIs or properties below.

### APIs (16)

- [Surf Chat API](https://apis.io/apis/surf/surf-chat-api/) — OpenAI-style Chat/Research API. POST /responses with a surf-2.0 or surf-2.0-instant model and a natural-language crypto question; returns synthesized…
- [Surf DEX API](https://apis.io/apis/surf/surf-dex-api/) — The DEX API from Surf — 1 operation(s) for dex.
- [Surf Exchange API](https://apis.io/apis/surf/surf-exchange-api/) — Access real-time trading data from major exchanges including Binance, OKX, Bybit, and more. Query live ticker prices, order book depth, OHLCV candlestick…
- [Surf Fund API](https://apis.io/apis/surf/surf-fund-api/) — Explore crypto venture capital. Look up fund profiles with team info and social links, browse their full investment portfolio with round details, and rank…
- [Surf Hyperliquid API](https://apis.io/apis/surf/surf-hyperliquid-api/) — The Hyperliquid API from Surf — 9 operation(s) for hyperliquid.
- [Surf Market API](https://apis.io/apis/surf/surf-market-api/) — Get a high-level view of the crypto market. Browse token rankings by market cap or volume, track derivatives across all exchanges, monitor spot ETF fund…
- [Surf News API](https://apis.io/apis/surf/surf-news-api/) — Stay up to date with crypto news. Browse the latest articles from major crypto media outlets, read full article content, and search across all sources by…
- [Surf Prediction Market API](https://apis.io/apis/surf/surf-prediction-market-api/) — Track prediction markets on Polymarket and Kalshi. Browse events and markets, view live prices and odds, analyze trading volume and open interest history,…
- [Surf Project API](https://apis.io/apis/surf/surf-project-api/) — Research crypto projects in depth. Retrieve aggregated project profiles covering overview, team, funding rounds, tokenomics, social links, and TGE status.…
- [Surf Search API](https://apis.io/apis/surf/surf-search-api/) — Find anything across Surf's data universe. Search for crypto projects, X (Twitter) accounts and posts, news articles, wallet addresses, web pages,…
- [Surf Signal API](https://apis.io/apis/surf/surf-signal-api/) — Explore ranked project signal score snapshots, token-of-day/week highlights, and project-level signal cards with latest price, price-change, dimension…
- [Surf Social API](https://apis.io/apis/surf/surf-social-api/) — Monitor crypto social activity on X (Twitter). Look up user profiles and their posts, track project sentiment scores and follower geography, discover smart…
- [Surf Token API](https://apis.io/apis/surf/surf-token-api/) — Analyze individual tokens on-chain. Look up top holders and their share of supply, track ERC-20/SPL token transfers, browse DEX swap history, and view…
- [Surf Wallet API](https://apis.io/apis/surf/surf-wallet-api/) — Inspect any wallet on Ethereum, Base, Solana, and other chains. View token balances, NFT holdings, entity labels, transfer history, full transaction logs,…
- [Surf Web API](https://apis.io/apis/surf/surf-web-api/) — Fetch and search web content. Retrieve any URL and convert it to clean, LLM-friendly markdown, or search the internet for crypto-related articles, reports,…
- [Surf On Chain API](https://apis.io/apis/surf/surf-on-chain-api/) — Query blockchain data directly. Look up transaction details by hash, check gas prices, and run structured or raw SQL queries against indexed blockchain…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [surf](https://apis.io/servers/surf/surf/)

#### Collections (15)

Postman and Open Collection request collections.

- [Hermod DEX API](https://apis.io/collections/surf/open-surf-dex-api/)
- [Hermod DEX Exchange API](https://apis.io/collections/surf/open-surf-exchange-api/)
- [Hermod DEX Fund API](https://apis.io/collections/surf/open-surf-fund-api/)
- [Hermod DEX Hyperliquid API](https://apis.io/collections/surf/open-surf-hyperliquid-api/)
- [Hermod DEX Market API](https://apis.io/collections/surf/open-surf-market-api/)
- [Hermod DEX News API](https://apis.io/collections/surf/open-surf-news-api/)
- [Hermod DEX Onchain API](https://apis.io/collections/surf/open-surf-onchain-api/)
- [Hermod DEX Prediction Market API](https://apis.io/collections/surf/open-surf-prediction-market-api/)
- [Hermod DEX Project API](https://apis.io/collections/surf/open-surf-project-api/)
- [Hermod DEX Search API](https://apis.io/collections/surf/open-surf-search-api/)
- [Hermod DEX Signal API](https://apis.io/collections/surf/open-surf-signal-api/)
- [Hermod DEX Social API](https://apis.io/collections/surf/open-surf-social-api/)
- [Hermod DEX Token API](https://apis.io/collections/surf/open-surf-token-api/)
- [Hermod DEX Wallet API](https://apis.io/collections/surf/open-surf-wallet-api/)
- [Hermod DEX Web API](https://apis.io/collections/surf/open-surf-web-api/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Surf Data Api Overlay](https://apis.io/overlays/surf/surf-data-api-overlay/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Surf Authentication](https://apis.io/security/surf/surf-authentication/)
- [Surf Domain Security](https://apis.io/security/surf/surf-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Surf Plans Pricing](https://apis.io/plans/surf/surf-plans-pricing/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://asksurf.ai/)
- [Documentation](https://agents.asksurf.ai/docs)
- [Getting started](https://agents.asksurf.ai/docs/overview)
- [API reference](https://agents.asksurf.ai/docs/data-api/overview)
- [Pricing](https://agents.asksurf.ai/docs/pricing)
- [Sign up](https://agents.asksurf.ai/)
- [Blog](https://asksurf.ai/blog)
- [GitHub](https://github.com/asksurf-ai)

## API Evangelist rating

**Kin Score 45.0** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.7 |
| Contract quality | 47.8 |
| Contract governance | 4.5 |
| Operational transparency | 2.6 |
| Developer ergonomics | 73.8 |
| Access clarity | 55.3 |

**Agent readiness 27.0** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 19.8** — Securities & Market Data

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/surf/](https://apis.io/providers/surf/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Surf: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/surf/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
