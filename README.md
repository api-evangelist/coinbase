# Coinbase (coinbase)

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
