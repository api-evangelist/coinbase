# Coinbase (coinbase)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Coinbase is a leading cryptocurrency platform providing trading, custody, and payment infrastructure for individuals, businesses, and institutions. The Coinbase Developer Platform (CDP) exposes a wide product surface across retail trading (Advanced Trade), professional and institutional trading (Exchange and Prime), merchant payments (Commerce), fiat onboarding (Onramp), developer wallet integration (Wallet SDK), market and on-chain data (Data API), and AI agent toolkits (AgentKit). Authentication is performed using API keys with HMAC-SHA256 signatures (Advanced Trade, Exchange) or JWT bearer tokens (Prime, CDP), with WebSocket and FIX feeds available for low-latency market data and order management.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/coinbase/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/coinbase/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Blockchain
- Cryptocurrency
- Custody
- Exchange
- Onramp
- Payments
- Trading
- Wallet
- Web3

## Timestamps

- **Created:** 2026-03-20
- **Modified:** 2026-05-19

## APIs

### Coinbase Advanced Trade API

The Coinbase Advanced Trade API provides programmatic access to advanced trading features on the Coinbase platform. Developers can automate market, limit, and stop-limit orders, manage portfolios, retrieve real-time and historical market data, and monitor fees. The REST API is available at api.coinbase.com/api/v3/brokerage and supports authenticated access using API keys with HMAC SHA-256 signatures.

- **Human URL:** [https://docs.cdp.coinbase.com/coinbase-app/advanced-trade-apis/rest-api](https://docs.cdp.coinbase.com/coinbase-app/advanced-trade-apis/rest-api)
- **Base URL:** `https://api.coinbase.com`

#### Tags

- Automation
- Cryptocurrency
- Market Data
- Orders
- Trading

#### Properties

- [Documentation](https://docs.cdp.coinbase.com/coinbase-app/advanced-trade-apis/rest-api)
- [OpenAPI](openapi/coinbase-advanced-trade-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/coinbase-advanced-trade.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coinbase-advanced-trade.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/coinbase-advanced-trade-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### Coinbase Exchange API

The Coinbase Exchange API provides high-throughput access to real-time market data and order management for institutional and professional traders. It supports REST APIs, FIX protocol, and WebSocket feeds for direct order placement and live market data streaming. The API enables programmatic trading at scale with low-latency execution and is designed for high-volume trading operations on the Coinbase exchange.

- **Human URL:** [https://www.coinbase.com/developer-platform/products/exchange-api](https://www.coinbase.com/developer-platform/products/exchange-api)
- **Base URL:** `https://api.exchange.coinbase.com`

#### Tags

- Cryptocurrency
- Exchange
- FIX
- Market Data
- Trading
- WebSocket

#### Properties

- [Documentation](https://docs.cdp.coinbase.com/exchange/docs/welcome)
- [OpenAPI](openapi/coinbase-exchange-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/coinbase-exchange.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coinbase-exchange.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/coinbase-exchange-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### Coinbase Prime API

The Coinbase Prime API enables institutions to manage cryptocurrency trading and custody on behalf of their clients. It supports programmatic trading strategies, automated platform processes, portfolio management, and custodial operations. The REST API provides endpoints for order execution, account management, transaction history, and reporting, designed for institutional-grade workflows and compliance requirements.

- **Human URL:** [https://www.coinbase.com/developer-platform/products/prime-apis](https://www.coinbase.com/developer-platform/products/prime-apis)
- **Base URL:** `https://api.prime.coinbase.com`

#### Tags

- Cryptocurrency
- Custody
- Institutional
- Prime Brokerage
- Trading

#### Properties

- [Documentation](https://docs.cdp.coinbase.com/prime/docs/rest-requests)
- [OpenAPI](openapi/coinbase-prime-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/coinbase-prime.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coinbase-prime.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Coinbase Onramp API

The Coinbase Onramp API allows developers to integrate fiat-to-crypto purchasing directly into their applications. It provides a FundCard React component and REST APIs to create one-click-buy URLs that enable users to purchase cryptocurrency with minimal friction. The API supports multiple fiat currencies and payment methods, making it straightforward for developers to onboard users into the crypto ecosystem from any application.

- **Human URL:** [https://www.coinbase.com/developer-platform/products/onramp](https://www.coinbase.com/developer-platform/products/onramp)
- **Base URL:** `https://api.developer.coinbase.com`

#### Tags

- Cryptocurrency
- Fiat
- Offramp
- Onramp
- Payments

#### Properties

- [Documentation](https://docs.cdp.coinbase.com/onramp/docs/welcome)
- [OpenAPI](openapi/coinbase-onramp-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/coinbase-onramp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coinbase-onramp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Coinbase Commerce API

The Coinbase Commerce API enables merchants and developers to accept cryptocurrency payments globally. It supports payment links, payouts, invoices, and checkout flows that can be integrated into websites and applications. The API provides endpoints for creating charges, managing payments, handling webhooks for payment notifications, and automating financial workflows for businesses accepting crypto as a payment method.

- **Human URL:** [https://commerce.coinbase.com/docs](https://commerce.coinbase.com/docs)
- **Base URL:** `https://api.commerce.coinbase.com`

#### Tags

- Checkout
- Commerce
- Cryptocurrency
- Invoices
- Payments

#### Properties

- [Documentation](https://commerce.coinbase.com/docs/api)
- [OpenAPI](openapi/coinbase-commerce-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/coinbase-commerce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coinbase-commerce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/coinbase-commerce-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### Coinbase Wallet SDK

The Coinbase Wallet SDK allows developers to integrate Coinbase Wallet connectivity into decentralized applications. It provides a streamlined interface for users to connect their wallets, sign transactions, and interact with smart contracts across multiple blockchain networks. The SDK supports millions of Coinbase Wallet users and enables dapp developers to offer seamless wallet-based experiences for trading assets and managing NFTs.

- **Human URL:** [https://www.coinbase.com/developer-platform/products/wallet-sdk](https://www.coinbase.com/developer-platform/products/wallet-sdk)

#### Tags

- Cryptocurrency
- DApps
- SDK
- Wallet
- Web3

#### Properties

- [Documentation](https://docs.cdp.coinbase.com/wallet-sdk/docs/welcome)
- [Postman Collection](collections/coinbase-advanced-trade.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coinbase-advanced-trade.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/coinbase-commerce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coinbase-commerce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/coinbase-exchange.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coinbase-exchange.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/coinbase-onramp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coinbase-onramp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/coinbase-prime.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coinbase-prime.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Coinbase Data API

The Coinbase Data API provides developers with access to cryptocurrency market data, blockchain analytics, and pricing information. It delivers real-time and historical data for a wide range of digital assets, enabling developers to build data-driven applications, dashboards, and research tools. The API supports queries for price feeds, trading volumes, and on-chain metrics across supported networks.

- **Human URL:** [https://www.coinbase.com/developer-platform/products/data-api](https://www.coinbase.com/developer-platform/products/data-api)

#### Tags

- Analytics
- Blockchain
- Cryptocurrency
- Market Data

#### Properties

- [Documentation](https://www.coinbase.com/developer-platform/products/data-api)
- [Postman Collection](collections/coinbase-advanced-trade.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coinbase-advanced-trade.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/coinbase-commerce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coinbase-commerce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/coinbase-exchange.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coinbase-exchange.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/coinbase-onramp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coinbase-onramp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/coinbase-prime.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coinbase-prime.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Coinbase AgentKit

Coinbase AgentKit is a toolkit that enables AI agents to interact with blockchain networks through secure wallet management and comprehensive onchain capabilities. Built on the Coinbase Developer Platform SDK, it is framework-agnostic and wallet-agnostic, supporting EVM and Solana networks.

- **Human URL:** [https://docs.cdp.coinbase.com/agent-kit/welcome](https://docs.cdp.coinbase.com/agent-kit/welcome)

#### Tags

- Agents
- AI
- Blockchain
- SDK
- Wallet

#### Properties

- [Documentation](https://docs.cdp.coinbase.com/agent-kit/welcome)
- [Postman Collection](collections/coinbase-advanced-trade.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coinbase-advanced-trade.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/coinbase-commerce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coinbase-commerce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/coinbase-exchange.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coinbase-exchange.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/coinbase-onramp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coinbase-onramp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/coinbase-prime.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/coinbase-prime.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/coinbase)
- [Developer  Portal](https://www.coinbase.com/developer-platform)
- [Documentation](https://docs.cdp.coinbase.com/)
- [Website](https://www.coinbase.com/)
- [Blog](https://www.coinbase.com/blog)
- [Git Hub](https://github.com/coinbase)
- [Login](https://login.coinbase.com/)
- [Support](https://help.coinbase.com/)
- [Privacy Policy](https://www.coinbase.com/legal/privacy)
- [Terms of Service](https://www.coinbase.com/legal/user-agreement)
- [JSON-LD](json-ld/coinbase-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/coinbase-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/coinbase-charge-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/coinbase-product-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral  Ruleset](rules/coinbase-rules.yml)
- [L L Ms Txt](https://docs.cdp.coinbase.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
