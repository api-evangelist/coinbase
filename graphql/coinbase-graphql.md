# Coinbase GraphQL Schema

This document describes a conceptual GraphQL schema for the Coinbase Developer Platform. Coinbase exposes its capabilities through REST APIs (Advanced Trade, Exchange, Prime, Commerce, Onramp) and WebSocket/FIX feeds; this schema unifies those surfaces into a single typed GraphQL model suitable for client tooling, code generation, and API design reference.

## Source APIs

- **Advanced Trade API** — retail trading, orders, portfolios, market data (`api.coinbase.com/api/v3/brokerage`)
- **Exchange API** — institutional REST, WebSocket, and FIX order management (`api.exchange.coinbase.com`)
- **Prime API** — institutional prime brokerage, custody, allocation (`api.prime.coinbase.com`)
- **Commerce API** — merchant payments, charges, checkouts, invoices (`api.commerce.coinbase.com`)
- **Onramp API** — fiat-to-crypto on/offramp flows (`api.developer.coinbase.com/onramp/v1`)
- **Data API** — market data, on-chain analytics, price feeds

## Schema File

[coinbase-schema.graphql](coinbase-schema.graphql)

## Type Summary

| Domain | Types |
|---|---|
| Account & Identity | Account, AccountBalance, Wallet, Address, AddressDetails, User, UserProfile, Identity, VerificationStatus, KYCDocument, APIKey, APISecret |
| Transactions | Transaction, Transfer, TransactionFee, TransactionStatus |
| Trading (Advanced Trade) | Order, OrderFill, OrderStatus, OrderConfiguration, TradeOrder, TradeExecution |
| Market Data | Product, ProductBook, Ticker, Candle, CandleData, OHLCV, Trade, BestBid, BestAsk |
| Currency & Assets | Currency, CurrencyDetails, CurrencyNetwork, Asset |
| Exchange Rates & Quotes | ExchangeRate, InstantBuyQuote, SellQuote, DepositQuote, WithdrawalQuote |
| Payment Methods | PaymentMethod, PaymentMethodLimit, FiatAccount, BankAccount, CryptoAddress, CryptoAddressDetails |
| Commerce | Commerce, Checkout, Charge, ChargeTimeline, InvoiceItem, PricingType, Settlement |
| Portfolio & Staking | PortfolioAccount, PortfolioBalance, StakingBalance, StakingTransaction, Reward, EligibleProduct |
| Webhooks & Notifications | Webhook, WebhookEvent, Notification |

## Design Notes

- All monetary amounts use a `Money` scalar carrying a string `amount` plus a `currency` code to avoid floating-point precision loss.
- `DateTime` scalars are ISO 8601 strings consistent with Coinbase REST responses.
- Enum values mirror Coinbase REST response constants (e.g., `OrderStatus`, `PricingType`).
- The `Trade` type covers both market-data trades (ticker tape) and execution fill records; a `tradeType` discriminator field distinguishes them.
- Pagination follows a cursor model with `PageInfo` and `edges`/`nodes` conventions compatible with Relay.
- This schema is a design artifact — Coinbase does not currently expose a public GraphQL endpoint.

## References

- Coinbase Developer Platform: <https://www.coinbase.com/developer-platform>
- Advanced Trade API Docs: <https://docs.cdp.coinbase.com/coinbase-app/advanced-trade-apis/rest-api>
- Exchange API Docs: <https://docs.cdp.coinbase.com/exchange/docs/welcome>
- Prime API Docs: <https://docs.cdp.coinbase.com/prime/docs/rest-requests>
- Commerce API Docs: <https://commerce.coinbase.com/docs/api>
- Onramp API Docs: <https://docs.cdp.coinbase.com/onramp/docs/welcome>
- GitHub: <https://github.com/coinbase>
