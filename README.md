# KalyRails

**Private ZK rollups for mobile money and fintech — settled on KalyChain.**

KalyRails is a rollup-as-a-service offering that gives fintechs, mobile money operators, and payment processors their own dedicated ZK chain. Each customer runs an isolated, permissioned Layer 2 with zero user-visible gas, sub-second UX, and cryptographic validity proofs anchored to KalyChain — a production EVM Layer 1 already processing real payments in production.

This repository contains the source for the KalyRails marketing site ([rails.kalychain.io](https://rails.kalychain.io)).

---

## What KalyRails delivers

- **Your own chain, not a shared tenant.** One L2 per fintech customer. Your transaction throughput, your fee policy, your compliance rules — no noisy neighbors, no global gas-price shocks.
- **Zero gas for end users.** The custodial architecture means your users never hold tokens, never sign transactions, and never see a gas fee. Your backend signs on their behalf.
- **ZK validity proofs, not optimistic fraud windows.** Every batch is mathematically proven before settlement. No 7-day withdrawal delays, no trust assumptions about watchtowers.
- **KUSD-denominated settlement.** All fees and transfers clear in [KUSD](https://kusd.kalychain.io), KalyChain's over-collateralized stablecoin (a MakerDAO DSS fork). Price-stable accounting without touching volatile assets.
- **Built on open-source ZK Stack.** The same battle-tested proving system that powers production ZK chains on Ethereum mainnet — but settled on KalyChain for dramatically lower costs and payments-native infrastructure.
- **Regulator-friendly by design.** Every customer gets a dedicated block explorer for their chain. Auditors and regulators get read-only visibility into every transaction, contract state, and settlement proof.

## Why KalyChain instead of Ethereum

Ethereum ZK rollups inherit Ethereum's gas volatility, its trading-first ecosystem, and its cost floor. KalyRails settles on **KalyChain** — a Hyperledger Besu QBFT Layer 1 purpose-built for payments — which means:

- **Proof verification costs a fraction of Ethereum mainnet**, making micro-transactions economically viable at mobile-money ticket sizes.
- **The surrounding ecosystem is payments-native**: Hyperlane bridge, KalySwap DEX liquidity, on-chain DAO governance, and KUSD stablecoin — all live, all production.
- **Full-stack ownership** from L1 to L2 means no third-party dependency chain when you need a custom feature, a config change, or priority support.
- **The same cryptographic security model.** ZK validity proofs are secured by math, not by which chain's name is on the settlement layer.

## Who KalyRails is built for

- Mobile money operators in emerging markets needing cross-border settlement without correspondent-banking friction
- Fintechs building wallets, remittance flows, or merchant-payment rails that require deterministic cost and sub-second finality
- Payment processors that need per-tenant isolation, regulator visibility, and on-chain compliance enforcement
- Any operator who needs the auditability of a public blockchain with the privacy and control of a private network

## About this repository

This repo holds the static marketing site for KalyRails. It is a plain HTML/CSS site with no build step — open `index.html` in a browser, or deploy the directory directly to any static host (Nginx, Cloudflare Pages, Netlify, S3, etc.).

```
site/
├── index.html         # Landing page
├── about.html         # About KalyChain — the settlement layer
├── technology.html    # ZK Stack architecture deep-dive
├── integrate.html     # Integration guide for fintechs
├── styles.css         # Shared styles
├── globals.css        # Reset / base styles
└── public/            # Logos, favicon, static assets
```

## Contact

Interested in running a ZK rollup for your fintech? **[info@kalychain.io](mailto:info@kalychain.io)**

Learn more:

- Parent chain — [kalychain.io](https://kalychain.io)
- Stablecoin — [kusd.kalychain.io](https://kusd.kalychain.io)
- Web 2.5 infrastructure — [kalyssi.com](https://kalyssi.com)

---

© 2026 KalyChain. KalyRails L2s are powered by open-source ZK Stack, settling on KalyChain — a Hyperledger Besu QBFT Layer 1.
