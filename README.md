# Coinbase (coinbase)

Coinbase is a leading cryptocurrency platform providing trading, custody, and payment infrastructure for individuals, businesses, and institutions. The Coinbase Developer Platform (CDP) exposes a wide product surface across retail trading (Advanced Trade), professional and institutional trading (Exchange and Prime), merchant payments (Commerce), fiat onboarding (Onramp), developer wallet integration (Wallet SDK), market and on-chain data (Data API), and AI agent toolkits (AgentKit). Authentication is performed using API keys with HMAC-SHA256 signatures (Advanced Trade, Exchange) or JWT bearer tokens (Prime, CDP), with WebSocket and FIX feeds available for low-latency market data and order management.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/coinbase/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
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
- **Modified:** 2026-04-28

## APIs

### Coinbase Advanced Trade API
The Coinbase Advanced Trade API provides programmatic access to advanced trading features on the Coinbase platform. Developers can automate market, limit, and stop-limit orders, manage portfolios, retrieve real-time and historical market data, and monitor fees. The REST API is available at api.coinbase.com/api/v3/brokerage and supports authenticated access using API keys with HMAC SHA-256 signatures.

**Human URL:** [https://docs.cdp.coinbase.com/coinbase-app/advanced-trade-apis/rest-api](https://docs.cdp.coinbase.com/coinbase-app/advanced-trade-apis/rest-api)

**Base URL:** `https://api.coinbase.com`

#### Tags

- Automation, Cryptocurrency, Market Data, Orders, Trading

#### Properties

- [Documentation](https://docs.cdp.coinbase.com/coinbase-app/advanced-trade-apis/rest-api)
- [OpenAPI](openapi/coinbase-advanced-trade-openapi.yml)
- [AsyncAPI](asyncapi/coinbase-advanced-trade-asyncapi.yml)

### Coinbase Exchange API
The Coinbase Exchange API provides high-throughput access to real-time market data and order management for institutional and professional traders. It supports REST APIs, FIX protocol, and WebSocket feeds for direct order placement and live market data streaming.

**Human URL:** [https://www.coinbase.com/developer-platform/products/exchange-api](https://www.coinbase.com/developer-platform/products/exchange-api)

**Base URL:** `https://api.exchange.coinbase.com`

#### Tags

- Cryptocurrency, Exchange, FIX, Market Data, Trading, WebSocket

#### Properties

- [Documentation](https://docs.cdp.coinbase.com/exchange/docs/welcome)
- [OpenAPI](openapi/coinbase-exchange-openapi.yml)
- [AsyncAPI](asyncapi/coinbase-exchange-asyncapi.yml)

### Coinbase Prime API
The Coinbase Prime API enables institutions to manage cryptocurrency trading and custody on behalf of their clients. The REST API provides endpoints for order execution, account management, transaction history, and reporting, designed for institutional-grade workflows and compliance requirements.

**Human URL:** [https://www.coinbase.com/developer-platform/products/prime-apis](https://www.coinbase.com/developer-platform/products/prime-apis)

**Base URL:** `https://api.prime.coinbase.com`

#### Tags

- Cryptocurrency, Custody, Institutional, Prime Brokerage, Trading

#### Properties

- [Documentation](https://docs.cdp.coinbase.com/prime/docs/rest-requests)
- [OpenAPI](openapi/coinbase-prime-openapi.yml)

### Coinbase Onramp API
The Coinbase Onramp API allows developers to integrate fiat-to-crypto purchasing directly into their applications. It provides a FundCard React component and REST APIs to create one-click-buy URLs that enable users to purchase cryptocurrency with minimal friction.

**Human URL:** [https://www.coinbase.com/developer-platform/products/onramp](https://www.coinbase.com/developer-platform/products/onramp)

**Base URL:** `https://api.developer.coinbase.com`

#### Tags

- Cryptocurrency, Fiat, Offramp, Onramp, Payments

#### Properties

- [Documentation](https://docs.cdp.coinbase.com/onramp/docs/welcome)
- [OpenAPI](openapi/coinbase-onramp-openapi.yml)

### Coinbase Commerce API
The Coinbase Commerce API enables merchants and developers to accept cryptocurrency payments globally. It supports payment links, payouts, invoices, and checkout flows that can be integrated into websites and applications.

**Human URL:** [https://commerce.coinbase.com/docs](https://commerce.coinbase.com/docs)

**Base URL:** `https://api.commerce.coinbase.com`

#### Tags

- Checkout, Commerce, Cryptocurrency, Invoices, Payments

#### Properties

- [Documentation](https://commerce.coinbase.com/docs/api)
- [OpenAPI](openapi/coinbase-commerce-openapi.yml)
- [AsyncAPI](asyncapi/coinbase-commerce-webhooks-asyncapi.yml)

### Coinbase Wallet SDK
The Coinbase Wallet SDK allows developers to integrate Coinbase Wallet connectivity into decentralized applications. It provides a streamlined interface for users to connect their wallets, sign transactions, and interact with smart contracts across multiple blockchain networks.

**Human URL:** [https://www.coinbase.com/developer-platform/products/wallet-sdk](https://www.coinbase.com/developer-platform/products/wallet-sdk)

#### Tags

- Cryptocurrency, DApps, SDK, Wallet, Web3

#### Properties

- [Documentation](https://docs.cdp.coinbase.com/wallet-sdk/docs/welcome)

### Coinbase Data API
The Coinbase Data API provides developers with access to cryptocurrency market data, blockchain analytics, and pricing information. It delivers real-time and historical data for a wide range of digital assets.

**Human URL:** [https://www.coinbase.com/developer-platform/products/data-api](https://www.coinbase.com/developer-platform/products/data-api)

#### Tags

- Analytics, Blockchain, Cryptocurrency, Market Data

#### Properties

- [Documentation](https://www.coinbase.com/developer-platform/products/data-api)

### Coinbase AgentKit
Coinbase AgentKit is a toolkit that enables AI agents to interact with blockchain networks through secure wallet management and comprehensive onchain capabilities. Built on the Coinbase Developer Platform SDK, it is framework-agnostic and wallet-agnostic, supporting EVM and Solana networks.

**Human URL:** [https://docs.cdp.coinbase.com/agent-kit/welcome](https://docs.cdp.coinbase.com/agent-kit/welcome)

#### Tags

- Agents, AI, Blockchain, SDK, Wallet

#### Properties

- [Documentation](https://docs.cdp.coinbase.com/agent-kit/welcome)

## Common Properties

- [Developer Portal](https://www.coinbase.com/developer-platform)
- [Documentation](https://docs.cdp.coinbase.com/)
- [Website](https://www.coinbase.com/)
- [Blog](https://www.coinbase.com/blog)
- [GitHub](https://github.com/coinbase)
- [Login](https://login.coinbase.com/)
- [Support](https://help.coinbase.com/)
- [Privacy Policy](https://www.coinbase.com/legal/privacy)
- [Terms of Service](https://www.coinbase.com/legal/user-agreement)
- [JSON-LD Context](json-ld/coinbase-context.jsonld)
- [Order JSON Schema](json-schema/coinbase-order-schema.json)
- [Charge JSON Schema](json-schema/coinbase-charge-schema.json)
- [Product JSON Schema](json-schema/coinbase-product-schema.json)
- [Spectral Ruleset](rules/coinbase-rules.yml)
- [Naftiko Capabilities](capabilities/coinbase-capabilities.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
