# Gülçin Uras

Frontend engineer, Barcelona (CET) · remote.

Five years building and owning production React and TypeScript applications, most of it on open, community-driven blockchain platforms. I worked across two chain architectures - Algorand (algosdk, ASA, atomic transaction groups, opt-ins) and EVM (ethers, wagmi, viem, ERC-721, Chainlink VRF).

Most of my production work lives in private repositories, so the links below are split between code you can read and products you can use.

## Public code

**[@tinymanorg/tinyman-js-sdk](https://github.com/tinymanorg/tinyman-js-sdk)** · [npm](https://www.npmjs.com/package/@tinymanorg/tinyman-js-sdk)
Tinyman's open-source TypeScript SDK, consumed by third-party developers building on the protocol. I'm the third-largest contributor and co-maintain it. I own the Limit&DCA orders and the governance functions, the Folks Lending Pools integration (pool state reads, deposit and withdraw return calculations, transaction generation with wrapper app opt-ins), swap router v3 support, a bigint migration for amount safety, the algosdk v2 → v3 migration, and the npm release workflow.

**[@tinymanorg/tinyman-swap-widget-sdk](https://github.com/tinymanorg/tinyman-swap-widget-sdk)** · [npm](https://www.npmjs.com/package/@tinymanorg/tinyman-swap-widget-sdk)
Drop-in swap widget SDK for dApps integrating Tinyman. Contributed swap router v3 support and the algosdk v2 → v3 migration.

## Production work

**[tinyman.org](https://tinyman.org)** — Algorand decentralised exchange. Lead frontend. I led the v2 migration, delivering an entirely new interface while keeping v1 users functional throughout, and built limit orders and DCA end to end — order construction, partial fills and claims, cancellation, expiry, and paginated history with derived status — plus swap router v3 with multi-hop route visualisation, liquid staking and governance, and a TradingView Advanced Charts integration with a real-time streaming datafeed.

**[silkarthouse.com](https://silkarthouse.com)** — Next.js 15 editorial, commerce and NFT platform. Lead frontend, and sole engineer on the Node/Strapi backend. I built the EVM surface with wagmi, viem and ethers: Manifold auctions with live bid history, an IPFS pipeline via Pinata, and an artist dice experience running on a Manifold mint-extension contract wired to Chainlink VRF 2.5, where each rolled face mints to the collector's wallet and a complete set of 6,666 burns for an exclusive silver die. I also designed the caching and revalidation architecture behind a full static-to-CMS migration, and cut media delivery weight 78%.

## Contributions

Most of my commits land in private and organisation repositories, so this counts work you can't browse here.

- `tinymanorg/tinyman-web-client` — lead frontend
- `tinymanorg/tinyman-js-sdk` — co-maintainer of the public SDK
- `silkarthouse/silk-web` — lead frontend
- `silkarthouse/silk-cms` — sole engineer
- `silkarthouse/silk-ai` — in progress: an AI search engine specialised for art questions, built to integrate with Silk

<img src="github-metrics.svg" alt="Notable contributions and language breakdown">

## Elsewhere

- LinkedIn — [gulcin-uras](https://www.linkedin.com/in/gulcin-uras)
- Email — gulcin_uras@hotmail.com

BSc Computer Science and Engineering, Sabancı University. Minor in Art Theory and Criticism.
