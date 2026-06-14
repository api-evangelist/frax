# Frax Finance

Frax Finance is a fractional-algorithmic stablecoin protocol. It produces FRAX (a USD-pegged stablecoin), FPI (Frax Price Index, pegged to a consumer goods basket), and frxETH (a liquid ETH staking derivative). The protocol operates Algorithmic Market Operations (AMOs) to deploy collateral into DeFi yield positions and exposes public REST APIs for querying protocol data.

## Public APIs

Base URL: `https://api.frax.finance`

| Endpoint | Description |
|---|---|
| `GET /combineddata/` | Aggregated protocol data: core token metrics (FRAX, FXS, FPI, FPIS, frxETH, sfrxETH, veFXS), 100+ liquidity staking pool positions, AMO sub-system holdings, collateral ratio, and decentralization ratio |
| `GET /pools` | Array of 270+ liquidity pool and farm objects with chain, platform, APY, max APY, liquidity locked (USD), and per-token reward breakdowns |
| `GET /v1/docs` | Swagger/OpenAPI interactive documentation for API v1 |
| `GET /v2/docs` | Swagger/OpenAPI interactive documentation for API v2 |

GraphQL subgraphs are available via The Graph at:
https://thegraph.com/explorer/profile/0x6e74053a3798e0fc9a9775f7995316b27f21c4d2?view=Subgraphs

## Key Data Points Available

- FRAX, FXS, FPI, FPIS, frxETH, sfrxETH price, supply, and market cap
- veFXS locked supply, average lock duration, and APR
- AMO positions across Curve, Convex, StakeDAO, lending platforms
- Protocol collateral ratio (CR) and decentralization ratio (DR)
- Per-pool APY, max APY, reward tokens, and USD liquidity across Arbitrum, Avalanche, BSC, and Ethereum

## Authentication

No authentication required. All endpoints are publicly accessible.

## Links

- Website: https://frax.finance
- Documentation: https://docs.frax.finance
- API Documentation: https://docs.frax.finance/smart-contracts/api
- GitHub: https://github.com/FraxFinance
- Governance: https://gov.frax.finance
- Discord: https://discord.com/invite/fraxfinance
- Twitter: https://twitter.com/fraxfinance
