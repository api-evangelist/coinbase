# Coinbase

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

Coinbase is a leading cryptocurrency platform providing trading, custody, and payment infrastructure for individuals, businesses, and institutions. The Coinbase Developer Platform (CDP) exposes a wide product surface across retail trading (Advanced Trade), professional and institutional trading (Exchange and Prime), merchant payments (Commerce), fiat onboarding (Onramp), developer wallet integration (Wallet SDK), market and on-chain data (Data API), and AI agent toolkits (AgentKit). Authentication is performed using API keys with HMAC-SHA256 signatures (Advanced Trade, Exchange) or JWT bearer tokens (Prime, CDP), with WebSocket and FIX feeds available for low-latency market data and order management.

**Areas:** Blockchain · Cryptocurrency · Custody · Exchange · On-Ramp · Payments · Trading · Wallets · Web3 · Agentic Commerce · x402 · Real-Time

## Coinbase on APIs.io

Everything profiled for Coinbase is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/coinbase/](https://apis.io/providers/coinbase/)** — or go straight to one of the APIs or properties below.

### APIs (35)

- [Coinbase Wallet SDK](https://apis.io/apis/coinbase/wallet-sdk/) — The Coinbase Wallet SDK allows developers to integrate Coinbase Wallet connectivity into decentralized applications. It provides a streamlined interface for…
- [Coinbase Data API](https://apis.io/apis/coinbase/data-api/) — The Coinbase Data API provides developers with access to cryptocurrency market data, blockchain analytics, and pricing information. It delivers real-time…
- [Coinbase AgentKit](https://apis.io/apis/coinbase/agentkit/) — Coinbase AgentKit is a toolkit that enables AI agents to interact with blockchain networks through secure wallet management and comprehensive onchain…
- [Coinbase Accounts API](https://apis.io/apis/coinbase/coinbase-accounts-api/) — Manage user accounts and retrieve account information including balances and holds.
- [Coinbase Activities API](https://apis.io/apis/coinbase/coinbase-activities-api/) — View activity history for portfolios including trades, transfers, and other events.
- [Coinbase Address Book API](https://apis.io/apis/coinbase/coinbase-address-book-api/) — Manage approved withdrawal addresses in the address book.
- [Coinbase Allocations API](https://apis.io/apis/coinbase/coinbase-allocations-api/) — View and manage order allocations across sub-portfolios.
- [Coinbase Assets API](https://apis.io/apis/coinbase/coinbase-assets-api/) — Retrieve information about supported assets and products.
- [Coinbase Balances API](https://apis.io/apis/coinbase/coinbase-balances-api/) — Retrieve portfolio balance information across all assets.
- [Coinbase Buy API](https://apis.io/apis/coinbase/coinbase-buy-api/) — Endpoints for discovering buy options, generating buy quotes, and retrieving buy configuration for fiat-to-crypto purchases.
- [Coinbase Charges API](https://apis.io/apis/coinbase/coinbase-charges-api/) — Create and manage payment charges. A charge represents a request for cryptocurrency payment from a customer.
- [Coinbase Checkouts API](https://apis.io/apis/coinbase/coinbase-checkouts-api/) — Create and manage reusable checkout pages for accepting recurring or standardized payments.
- [Coinbase Conversions API](https://apis.io/apis/coinbase/coinbase-conversions-api/) — Convert between stablecoin currencies on the exchange.
- [Coinbase Currencies API](https://apis.io/apis/coinbase/coinbase-currencies-api/) — Retrieve information about supported currencies on the exchange.
- [Coinbase Deposits API](https://apis.io/apis/coinbase/coinbase-deposits-api/) — View deposit information and payment methods for funding exchange accounts.
- [Coinbase Events API](https://apis.io/apis/coinbase/coinbase-events-api/) — Retrieve webhook events that track the lifecycle of charges, checkouts, and invoices.
- [Coinbase Fees API](https://apis.io/apis/coinbase/coinbase-fees-api/) — Retrieve transaction summary and fee information for the authenticated user.
- [Coinbase Invoices API](https://apis.io/apis/coinbase/coinbase-invoices-api/) — Create and manage invoices for billing customers with cryptocurrency payment options.
- [Coinbase Market Data API](https://apis.io/apis/coinbase/coinbase-market-data-api/) — Access public market data including products, order books, trades, and candles without authentication.
- [Coinbase Orders API](https://apis.io/apis/coinbase/coinbase-orders-api/) — Create, cancel, and manage trading orders including market, limit, and stop-limit order types.
- [Coinbase Portfolios API](https://apis.io/apis/coinbase/coinbase-portfolios-api/) — Create and manage portfolios for organizing trading activity and asset allocation.
- [Coinbase Products API](https://apis.io/apis/coinbase/coinbase-products-api/) — Retrieve product information, market trades, product books, and candle data for trading pairs.
- [Coinbase Profiles API](https://apis.io/apis/coinbase/coinbase-profiles-api/) — Manage exchange profiles and transfer funds between them.
- [Coinbase Sell API](https://apis.io/apis/coinbase/coinbase-sell-api/) — Endpoints for discovering sell options and generating sell quotes for crypto-to-fiat transactions.
- [Coinbase Session API](https://apis.io/apis/coinbase/coinbase-session-api/) — Manage session tokens for embedded onramp widget authentication.
- [Coinbase Transactions API](https://apis.io/apis/coinbase/coinbase-transactions-api/) — View and create transactions including withdrawals and transfers.
- [Coinbase Users API](https://apis.io/apis/coinbase/coinbase-users-api/) — Manage users associated with a portfolio.
- [Coinbase Wallets API](https://apis.io/apis/coinbase/coinbase-wallets-api/) — Manage wallets within a portfolio for different asset types.
- [Coinbase Withdrawals API](https://apis.io/apis/coinbase/coinbase-withdrawals-api/) — Manage crypto withdrawals from exchange accounts to external addresses or Coinbase accounts.
- [Coinbase Developer Platform (CDP) API](https://apis.io/apis/coinbase/coinbase-developer-platform-cdp-api/) — Core CDP API v2 for onchain wallets, payments, trading, faucets, policies, and JSON-RPC access, authenticated with short-lived JWTs.
- [Coinbase Advanced Trade API](https://apis.io/apis/coinbase/coinbase-advanced-trade-api/) — Programmatic spot trading, order management, and market data for the Coinbase retail exchange (Advanced Trade).
- [Coinbase App API (Sign in with Coinbase)](https://apis.io/apis/coinbase/coinbase-app-api-sign-in-with-coinbase/) — Retail Coinbase App API v2 for accounts, addresses, transactions, buys/sells, with OAuth2 and API-key HMAC authentication.
- [Coinbase Exchange API](https://apis.io/apis/coinbase/coinbase-exchange-api/) — Institutional/pro exchange REST and WebSocket API for order books, trading, and market data.
- [Coinbase Prime API](https://apis.io/apis/coinbase/coinbase-prime-api/) — Institutional trading, custody, and portfolio management API for Coinbase Prime.
- [Coinbase Commerce API](https://apis.io/apis/coinbase/coinbase-commerce-api/) — Crypto payments/checkout API for accepting cryptocurrency payments.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (4)

Event-driven and webhook contracts.

- [Coinbase Advanced Trade WebSocket](https://apis.io/asyncapis/coinbase/coinbase-advanced-trade-asyncapi/)
- [Coinbase Commerce Webhooks](https://apis.io/asyncapis/coinbase/coinbase-commerce-webhooks-asyncapi/)
- [Coinbase Exchange WebSocket Feed](https://apis.io/asyncapis/coinbase/coinbase-exchange-asyncapi/)
- [Coinbase Webhooks](https://apis.io/asyncapis/coinbase/coinbase-webhooks/)

#### Event channels (15)

Individual events and webhooks the provider emits.

- [/candles](https://apis.io/channels/coinbase/candles/)
- [/level2](https://apis.io/channels/coinbase/coinbase-exchange-websocket-feed-level2/)
- [/ticker](https://apis.io/channels/coinbase/coinbase-exchange-websocket-feed-ticker/)
- [/full](https://apis.io/channels/coinbase/full/)
- [/heartbeat](https://apis.io/channels/coinbase/heartbeat/)
- [/heartbeats](https://apis.io/channels/coinbase/heartbeats/)
- [/level2](https://apis.io/channels/coinbase/level2/)
- [/level2_batch](https://apis.io/channels/coinbase/level2-batch/)
- [/market_trades](https://apis.io/channels/coinbase/market-trades/)
- [/matches](https://apis.io/channels/coinbase/matches/)
- [/status](https://apis.io/channels/coinbase/status/)
- [/ticker](https://apis.io/channels/coinbase/ticker/)
- [/ticker_batch](https://apis.io/channels/coinbase/ticker-batch/)
- [/user](https://apis.io/channels/coinbase/user/)
- [/webhook](https://apis.io/channels/coinbase/webhook/)

#### GraphQL (1)

GraphQL schemas.

- [Moved to /providers/coinbase/](https://apis.io/graphqls/coinbase/coinbase-graphql/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [coinbase](https://apis.io/servers/coinbase/coinbase/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Coinbase Agentic Access](https://apis.io/agentic-access/coinbase/coinbase-agentic-access/)

#### JSON Schema (65)

The data models the API reads and writes.

- [Account](https://apis.io/schemas/coinbase/coinbase-account/)
- [Activity](https://apis.io/schemas/coinbase/coinbase-activity/)
- [AddressBookEntry](https://apis.io/schemas/coinbase/coinbase-address-book-entry/)
- [AddressBookEntry](https://apis.io/schemas/coinbase/coinbase-addressbookentry/)
- [Allocation](https://apis.io/schemas/coinbase/coinbase-allocation/)
- [Balance](https://apis.io/schemas/coinbase/coinbase-balance/)
- [BuyConfig](https://apis.io/schemas/coinbase/coinbase-buy-config/)
- [BuyQuote](https://apis.io/schemas/coinbase/coinbase-buy-quote/)
- [BuyQuoteRequest](https://apis.io/schemas/coinbase/coinbase-buy-quote-request/)
- [BuyConfig](https://apis.io/schemas/coinbase/coinbase-buyconfig/)
- [BuyQuote](https://apis.io/schemas/coinbase/coinbase-buyquote/)
- [BuyQuoteRequest](https://apis.io/schemas/coinbase/coinbase-buyquoterequest/)
- [Candle](https://apis.io/schemas/coinbase/coinbase-candle/)
- [Coinbase Commerce Charge](https://apis.io/schemas/coinbase/coinbase-charge/)
- [Checkout](https://apis.io/schemas/coinbase/coinbase-checkout/)
- [Conversion](https://apis.io/schemas/coinbase/coinbase-conversion/)
- [CreateChargeRequest](https://apis.io/schemas/coinbase/coinbase-create-charge-request/)
- [CreateCheckoutRequest](https://apis.io/schemas/coinbase/coinbase-create-checkout-request/)
- [CreateInvoiceRequest](https://apis.io/schemas/coinbase/coinbase-create-invoice-request/)
- [CreateOrderRequest_3](https://apis.io/schemas/coinbase/coinbase-create-order-request-3/)
- [CreateChargeRequest](https://apis.io/schemas/coinbase/coinbase-createchargerequest/)
- [CreateCheckoutRequest](https://apis.io/schemas/coinbase/coinbase-createcheckoutrequest/)
- [CreateInvoiceRequest](https://apis.io/schemas/coinbase/coinbase-createinvoicerequest/)
- [CreateOrderRequest](https://apis.io/schemas/coinbase/coinbase-createorderrequest/)
- [Currency](https://apis.io/schemas/coinbase/coinbase-currency/)
- …and 40 more published on APIs.io

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Coinbase Structure](https://apis.io/json-structure/coinbase/coinbase-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Coinbase Context](https://apis.io/jsonld/coinbase/coinbase-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Coinbase Domain Vocabulary](https://apis.io/vocabularies/coinbase/coinbase-vocabulary/)

#### Collections (57)

Postman and Open Collection request collections.

- [Coinbase Advanced Trade Accounts API](https://apis.io/collections/coinbase/open-coinbase-accounts-api/)
- [Coinbase Advanced Trade Accounts Activities API](https://apis.io/collections/coinbase/open-coinbase-activities-api/)
- [Coinbase Advanced Trade Accounts Address Book API](https://apis.io/collections/coinbase/open-coinbase-address-book-api/)
- [Coinbase Advanced Trade API](https://apis.io/collections/coinbase/open-coinbase-advanced-trade/)
- [Coinbase Advanced Trade Accounts Allocations API](https://apis.io/collections/coinbase/open-coinbase-allocations-api/)
- [Coinbase Advanced Trade Accounts Assets API](https://apis.io/collections/coinbase/open-coinbase-assets-api/)
- [Coinbase Advanced Trade Accounts Balances API](https://apis.io/collections/coinbase/open-coinbase-balances-api/)
- [Coinbase Advanced Trade Accounts Buy API](https://apis.io/collections/coinbase/open-coinbase-buy-api/)
- [Coinbase Advanced Trade Accounts Charges API](https://apis.io/collections/coinbase/open-coinbase-charges-api/)
- [Coinbase Advanced Trade Accounts Checkouts API](https://apis.io/collections/coinbase/open-coinbase-checkouts-api/)
- [Coinbase Commerce API](https://apis.io/collections/coinbase/open-coinbase-commerce/)
- [Coinbase Advanced Trade Accounts Conversions API](https://apis.io/collections/coinbase/open-coinbase-conversions-api/)
- [Coinbase Advanced Trade Accounts Currencies API](https://apis.io/collections/coinbase/open-coinbase-currencies-api/)
- [Coinbase Advanced Trade Accounts Deposits API](https://apis.io/collections/coinbase/open-coinbase-deposits-api/)
- [Coinbase Advanced Trade Accounts Events API](https://apis.io/collections/coinbase/open-coinbase-events-api/)
- [Coinbase Exchange API](https://apis.io/collections/coinbase/open-coinbase-exchange/)
- [Coinbase Advanced Trade Accounts Fees API](https://apis.io/collections/coinbase/open-coinbase-fees-api/)
- [Coinbase Advanced Trade Accounts Invoices API](https://apis.io/collections/coinbase/open-coinbase-invoices-api/)
- [Coinbase Advanced Trade Accounts Market Data API](https://apis.io/collections/coinbase/open-coinbase-market-data-api/)
- [Coinbase Onramp API](https://apis.io/collections/coinbase/open-coinbase-onramp/)
- [Coinbase Advanced Trade Accounts Orders API](https://apis.io/collections/coinbase/open-coinbase-orders-api/)
- [Coinbase Advanced Trade Accounts Portfolios API](https://apis.io/collections/coinbase/open-coinbase-portfolios-api/)
- [Coinbase Prime API](https://apis.io/collections/coinbase/open-coinbase-prime/)
- [Coinbase Advanced Trade Accounts Products API](https://apis.io/collections/coinbase/open-coinbase-products-api/)
- [Coinbase Advanced Trade Accounts Profiles API](https://apis.io/collections/coinbase/open-coinbase-profiles-api/)
- …and 32 more published on APIs.io

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [Coinbase — asyncapi rules](https://apis.io/rules/coinbase/coinbase-asyncapi-spectral-rules/)
- [Coinbase — jsonschema rules](https://apis.io/rules/coinbase/coinbase-jsonschema-spectral-rules/)
- [Coinbase API Rules](https://apis.io/rules/coinbase/coinbase-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Coinbase Authentication](https://apis.io/security/coinbase/coinbase-authentication/)
- [Coinbase Domain Security](https://apis.io/security/coinbase/coinbase-domain-security/)
- [Coinbase Vulnerability Disclosure](https://apis.io/security/coinbase/coinbase-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Coinbase Plans Pricing](https://apis.io/plans/coinbase/coinbase-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Coinbase Rate Limits](https://apis.io/rate-limits/coinbase/coinbase-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Coinbase Finops](https://apis.io/finops/coinbase/coinbase-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.coinbase.com/)
- [Documentation](https://docs.cdp.coinbase.com/)
- [Support](https://help.coinbase.com/)
- [Blog](https://www.coinbase.com/blog)
- [Terms of service](https://www.coinbase.com/legal/user-agreement)
- [Privacy policy](https://www.coinbase.com/legal/privacy)

## API Evangelist rating

**Kin Score 54.8** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.7 |
| Contract quality | 71.4 |
| Contract governance | 31.8 |
| Operational transparency | 31.6 |
| Developer ergonomics | 67.9 |
| Access clarity | 25.0 |

**Agent readiness 48.8** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | platform (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | verified |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | yes |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | mostly |

**Regulatory alignment 27.7** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/coinbase/](https://apis.io/providers/coinbase/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Coinbase: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/coinbase/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
