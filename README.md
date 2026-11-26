<p align="center"><img src="https://raw.githubusercontent.com/X402blockchains/x402blockchain/main/branding/github-header.svg" alt="X402blockchains" width="100%"></p>

# Awesome x402

A focused resource guide maintained by [X402blockchains](https://x402blockchains.com). Independent community curation; inclusion is not an endorsement.

## Start here

- [x402](https://x402.org/) — protocol introduction and ecosystem.
- [Protocol source and specifications](https://github.com/x402-foundation/x402) — upstream implementation, SDKs and specifications.
- [Coinbase development fork](https://github.com/coinbase/x402) — Coinbase's development fork of the protocol repository.
- [Official examples](https://github.com/x402-foundation/x402/tree/main/examples) — start from maintained upstream integrations.

## Explore the ecosystem

- [X402blockchains](https://x402blockchains.com) — project discovery and payment exploration.
- [x402scan](https://www.x402scan.com/) — ecosystem explorer.
- [Agent402](https://agent402.tools/base) — Base seller discovery and activity views.

Compare the same network, UTC time range and measurement definition. Wallet transfers, protocol settlements and API requests are different measurements; totals need not match.

## Live services

- [Farol LatAm](https://farol-latam.8qk1thp1.workers.dev) — Brazil/LatAm session intelligence (B3, ADRs, FX, Focus, Polymarket) as a pay-per-call JSON API on Base USDC via x402. Free teaser at /v1/teaser; paid session, deviation and ticker routes. [OpenAPI](https://farol-latam.8qk1thp1.workers.dev/openapi.json) · [llms.txt](https://farol-latam.8qk1thp1.workers.dev/llms.txt) · [x402](https://farol-latam.8qk1thp1.workers.dev/.well-known/x402).
- [Perps Pulse](https://perps-pulse.8qk1thp1.workers.dev) — Live cross-exchange crypto perp funding, annualized carry and basis from public Hyperliquid, Binance, OKX and Bybit data, billed per call in USDC on Base via x402. [OpenAPI](https://perps-pulse.8qk1thp1.workers.dev/openapi.json) · [llms.txt](https://perps-pulse.8qk1thp1.workers.dev/llms.txt) · [x402](https://perps-pulse.8qk1thp1.workers.dev/.well-known/x402).
- [Poly Edge](https://poly-edge.8qk1thp1.workers.dev) — Live Polymarket scanner for top markets, bid-ask spreads and mispricing flags, billed per call in USDC on Base via x402. [OpenAPI](https://poly-edge.8qk1thp1.workers.dev/openapi.json) · [llms.txt](https://poly-edge.8qk1thp1.workers.dev/llms.txt) · [x402](https://poly-edge.8qk1thp1.workers.dev/.well-known/x402).
- [Yield Radar](https://yield-radar.8qk1thp1.workers.dev) — Risk-adjusted DeFi yields on Base, Arbitrum, Ethereum and Solana from public DeFiLlama data, with low-TVL and mercenary-reward flags, billed per call in USDC on Base via x402. [OpenAPI](https://yield-radar.8qk1thp1.workers.dev/openapi.json) · [llms.txt](https://yield-radar.8qk1thp1.workers.dev/llms.txt) · [x402](https://yield-radar.8qk1thp1.workers.dev/.well-known/x402).
- [BR Intel](https://br-intel.8qk1thp1.workers.dev) — On-demand Brazil macro (Selic, IPCA, PTAX), B3 snapshot and CNPJ enrichment from official public sources, billed per call in USDC on Base via x402. [OpenAPI](https://br-intel.8qk1thp1.workers.dev/openapi.json) · [llms.txt](https://br-intel.8qk1thp1.workers.dev/llms.txt) · [x402](https://br-intel.8qk1thp1.workers.dev/.well-known/x402).
- [Site Intel](https://site-intel.8qk1thp1.workers.dev) — On-demand audit of a public domain for security headers, robots.txt, llms.txt, x402 discovery and AI-readiness, billed per call in USDC on Base via x402. [OpenAPI](https://site-intel.8qk1thp1.workers.dev/openapi.json) · [llms.txt](https://site-intel.8qk1thp1.workers.dev/llms.txt) · [x402](https://site-intel.8qk1thp1.workers.dev/.well-known/x402).

## Community repositories

- [Explorer source](https://github.com/X402blockchains/x402blockchain)
- [Listing registry](https://github.com/X402blockchains/x402-registry)
- [Integration examples](https://github.com/X402blockchains/x402-examples)

## Developer tools

- [Agent Payment Node](https://github.com/nuanu-ai/agent-payment-node) — Open-source (MIT) local CLI and stdio MCP payment runtime for AI agents. x402 purchases (EVM `exact` and Solana `exact`) run unattended only within an x402 policy the owner sets per chain and token, with per-payment and balance caps; creating or raising that policy needs the foreground terminal. Direct transfers are signed only after the owner approves them in a foreground terminal. macOS Apple Silicon with Node 24 only; Linux and Windows are unsupported. [Documentation](https://github.com/nuanu-ai/agent-payment-node/blob/main/docs/x402-any-seller.md) · [Support](https://github.com/nuanu-ai/agent-payment-node/issues) · No official X profile.

## Suggest a resource

Open a pull request with the public URL, a short factual description, category and official documentation. Prefer maintained primary sources. Disclose affiliation. No referral links, fabricated activity metrics or paid ranking.

Links checked September 27, 2026. This is a starting collection, not a complete directory.
