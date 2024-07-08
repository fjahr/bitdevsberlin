---
layout: post
title: "Socratic Seminar #57"
---

[Meetup](https://www.meetup.com/bitcoin-lab-berlin/events/298337266/)

Thanks to [Ordimint](https://ordimint.com) for sponsoring food and drinks for this meetup!

## Security/CVEs/InfoSec/Research

- [ZK Rollup on Bitcoin: Technical Whitepaper](https://github.com/alpenlabs/Technical-Whitepaper/blob/main/whitepaper_v085.pdf)
- [From Slow Propagation to Partition: Analyzing Bitcoin Over Anonymous Routing](https://par.nsf.gov/biblio/10509863)
- [DoS: LND Onion Bomb](https://morehouse.github.io/lightning/lnd-onion-bomb/)
- [Bitcoin Core Security Advisories and 10 previously unreleased disclosures](https://bitcoincore.org/en/security-advisories/)
- [The Great Script Restoration Project Talk](https://www.youtube.com/watch?v=rSp8918HLnA)
- [MixBuy: Contingent Payment in the Presence of Coin Mixers](https://eprint.iacr.org/2024/953)
- [Dynamic-FROST: Schnorr Threshold Signatures with a Flexible Committee](https://eprint.iacr.org/2024/896)
- [Concurrently Secure Blind Schnorr Signatures](https://eprint.iacr.org/2022/1676.pdf)
- [Cryptocurrency mining as a novel virtual energy storage system in islanded and grid-connected microgrids](https://www.sciencedirect.com/science/article/pii/S0142061524001364)

## Miscellaneous

- [Stratum.work](https://stratum.work/)
- [CatVM Audiobook](https://www.opcatsimulator.com/catvm)
- [Wasabi Wallet coordinator explorer](https://wasabist.io/)
- [Mining Cooling Solutions Comparison](https://braiins.com/blog/stay-cool-mine-on-exploring-bitcoin-mining-cooling-solutions)
- [Blocksize increase proposals historical review](https://x.com/ajtowns/status/1798185661570441383)
- [CoinPile](https://x.com/JeremyRubin/status/1797315646327345538)
- [Brollups](https://brqgoo.medium.com/introducing-brollups-18ec4081f6e7)
- [Definitive explanation of the weird Bitcoin transaction](https://stacker.news/items/600187)

## Network Data

- [Empty Block Report](https://research.mempool.space/empty-block-report/)

## Europe/Germany/Berlin

- [Sachsen transferiert Bitcoin](https://www.spiegel.de/netzwelt/web/bitcoin-sachsen-sitzt-auf-digitalwaehrung-im-milliardenwert-macht-es-sie-jetzt-zu-geld-a-b8aa866f-70b4-492d-9f0a-7af76aeb3701)
- [Wie Krypto-Influencer Rechten den Weg bereiten](https://krautreporter.de/politik-und-macht/5406-wie-krypto-influencer-rechten-den-weg-bereiten)

## Mailing Lists

### Delving Bitcoin

- OP_CAT Use Cases Series
    - [1. Covenants](https://delvingbitcoin.org/t/bitcoin-op-cat-use-cases-series-1-covenants/990)
    - [2. Merkle Trees](https://delvingbitcoin.org/t/op-cat-use-cases-series-2-merkle-trees/988)
    - [3. Vaults](https://delvingbitcoin.org/t/op-cat-use-cases-series-3-vaults/1006)
    - [4. Recursive Covenants](https://delvingbitcoin.org/t/bitcoin-op-cat-use-cases-series-4-recursive-covenants/1028)
- [Proposing a P2QRH BIP towards a quantum resistant soft fork](https://delvingbitcoin.org/t/proposing-a-p2qrh-bip-towards-a-quantum-resistant-soft-fork/956)
- [Estimating Likelihood for Lightning Payments to be (in)feasible](https://delvingbitcoin.org/t/estimating-likelihood-for-lightning-payments-to-be-in-feasible/973)

## Pull requests

### BIPs, BOLTs and Proposals

- [ChillDKG: Distributed Key Generation for FROST](https://github.com/BlockstreamResearch/bip-frost-dkg)
- [328, 390, 373: BIPs for MuSig2 derivation, descriptors, and PSBT fields #1540](https://github.com/bitcoin/bips/pull/1540)
- [Add BIP 353: DNS Payment Instructions #1551](https://github.com/bitcoin/bips/pull/1551)

### Bitcoin Core

- [policy: bump TX_MAX_STANDARD_VERSION to 3 #29496](https://github.com/bitcoin/bitcoin/pull/29496)
- [Cluster size 2 package rbf #28984](https://github.com/bitcoin/bitcoin/pull/28984)
- [net_processing: make any misbehavior trigger immediate discouragement #29575](https://github.com/bitcoin/bitcoin/pull/29575)
- [Introduce Mining interface #30200](https://github.com/bitcoin/bitcoin/pull/30200)
- [chainparams: Add achow101 DNS seeder #30007](https://github.com/bitcoin/bitcoin/pull/30007)

### LND

- [multi: allow min-depth of zero for non-zero conf channels #8796](https://github.com/lightningnetwork/lnd/pull/8796)

### Eclair

- [Accept onion failure without a channel_update #2854](https://github.com/ACINQ/eclair/pull/2854)

### BDK & LDK

- [Force-close channels if their feerate gets stale without any update #3037](https://github.com/lightningdevkit/rust-lightning/pull/3037)
- [BOLT 12 static invoice encoding and building #3082](https://github.com/lightningdevkit/rust-lightning/pull/3082)
- [Remove rand dependency from bdk #1395](https://github.com/bitcoindevkit/bdk/pull/1395)

### Core Lightning

- [Wait for bitcoind if it's gone backwards, don't abort. #7342](https://github.com/ElementsProject/lightning/pull/7342)

### rust-bitcoin

- [Enforce script size limit when hashing scripts #2794](https://github.com/rust-bitcoin/rust-bitcoin/pull/2794)
