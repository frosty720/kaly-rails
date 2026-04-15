# KalyRails

**Private blockchain infrastructure for banks and fintechs — built and operated by the team that runs KalyChain.**

KalyRails is a two-product infrastructure offering targeting regulated financial institutions in Africa and beyond. One team, one operational foundation, two purpose-built products that solve different problems for different buyers.

This repository contains the source for the KalyRails marketing site ([rails.kalychain.io](https://rails.kalychain.io)).

---

## The two products

### KalyRails L2 — ZK Rollups for Fintech

Private ZK Layer 2 chains for mobile money operators, remittance companies, payment aggregators, and microfinance institutions. Each customer gets a dedicated ZK rollup that settles on KalyChain, with zero user-visible gas, wallet-less custodial UX, and KUSD-denominated settlement. Built on open-source ZK Stack — the same proving system powering production ZK chains on Ethereum mainnet.

- **Buyer:** Mobile money operators, fintechs, payment processors
- **Technology:** ZK Stack (validity-proof rollup)
- **Settlement:** KalyChain L1
- **UX:** Invisible to end users
- **Product page:** [`fintech.html`](fintech.html)

### KalyRails Bank — Private Besu Chains for Banks

Permissioned Hyperledger Besu Proof-of-Authority networks that sit alongside a bank's existing core banking system (Temenos, Flexcube, Finacle) as an invisible fraud-prevention and settlement layer. Smart contracts enforce withdrawal limits, velocity checks, multi-sig thresholds, and branch-level caps in code — making silent mass fraud mathematically impossible even in the face of a full database breach.

Built on the same Hyperledger Besu technology powering SWIFT's 2026 shared settlement ledger, Nigeria's eNaira CBDC, Brazil's DREX, and Citi Token Services.

- **Buyer:** Commercial banks, central banks, regulated financial institutions
- **Technology:** Hyperledger Besu (IBFT 2.0 / QBFT PoA)
- **Crypto exposure:** None — zero token, zero gas, customer PII stays off-chain
- **Integration:** Drop-in alongside existing core banking
- **Product page:** [`banking.html`](banking.html)

## Why KalyRails

- **Production operators, not theoretical consultants.** We run KalyChain — a live Layer 1 blockchain — in production every day. Validators, RPC nodes, block explorer, DEX, bridge, stablecoin, on-chain DAO.
- **Built for Africa.** Headquartered in-region, aligned to BCEAO regulatory requirements, existing customer base on the continent.
- **Regulator-ready by design.** Every deployment ships with a dedicated block explorer and optional regulator node.
- **Zero crypto exposure for both products.** No tokens held by customers, no speculative assets, no market volatility touching your balance sheet.
- **Full-stack capability.** Consensus, smart contracts, APIs, frontends, monitoring, DevOps — end-to-end ownership.

## About this repository

This is a plain HTML/CSS marketing site with no build step. Open `index.html` in a browser, or deploy the directory directly to any static host (Nginx, Cloudflare Pages, Netlify, S3, etc.).

```
site/
├── index.html          # Umbrella landing — dual-product showcase
├── fintech.html        # KalyRails L2 product page (ZK rollups)
├── banking.html        # KalyRails Bank product page (private Besu)
├── about.html          # About KalyChain — the settlement layer
├── technology.html     # ZK Stack architecture deep-dive
├── integrate.html      # Integration guide for fintechs
├── styles.css          # Shared styles (KUSD design system)
├── globals.css         # Reset / base styles
└── public/             # Logos, favicon, static assets
```

## Contact

- Fintech enquiries (KalyRails L2): **[info@kalychain.io](mailto:info@kalychain.io?subject=KalyRails%20L2%20Enquiry)**
- Banking enquiries (KalyRails Bank): **[info@kalychain.io](mailto:info@kalychain.io?subject=KalyRails%20Bank%20Enquiry)**

Learn more:

- Parent chain — [kalychain.io](https://kalychain.io)
- Stablecoin — [kusd.kalychain.io](https://kusd.kalychain.io)
- Web 2.5 infrastructure — [kalyssi.com](https://kalyssi.com)

---

© 2026 KalyChain. KalyRails L2 is powered by open-source ZK Stack. KalyRails Bank is powered by Hyperledger Besu. Both settle on KalyChain — a Hyperledger Besu QBFT Layer 1.
