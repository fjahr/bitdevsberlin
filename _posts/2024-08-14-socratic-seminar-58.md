---
layout: post
title: "Socratic Seminar #58"
---

[Meetup](https://www.meetup.com/bitcoin-lab-berlin/events/298337269/)

Thanks to [Ordimint](https://ordimint.com) for sponsoring food and drinks for this meetup!

## Security/CVEs/InfoSec/Research

- [July 9th-10th 2024: Wasabi Wallet Security Incident Disclosure](https://github.com/WalletWasabi/WalletWasabi/discussions/13249)
- [Simple Logarithmic-size LSAG signature](https://eprint.iacr.org/2024/921)
- [University of Wyoming launches Bitcoin research institute](https://bitcoinmagazine.com/business/university-of-wyoming-launches-first-bitcoin-research-institute)
- [Dark Skippy: a method for a malicious signing device to leak secret keys](https://darkskippy.com/)
- [regreSSHion: Remote Unauthenticated Code Execution Vulnerability in OpenSSH server](https://blog.qualys.com/vulnerabilities-threat-research/2024/07/01/regresshion-remote-unauthenticated-code-execution-vulnerability-in-openssh-server)
- [Incident report: Rootstock peg-in / peg-out service outage on June 24th](https://blog.rootstock.io/noticia/incident-report-rootstock-peg-in-peg-out-service-outage-on-june-24th/)
- [Benchmarking GNNs Using Lightning Network Data](https://arxiv.org/pdf/2407.07916v1)
- [Bribe & Fork: Cheap Bribing Attacks via Forking Threat](https://arxiv.org/abs/2402.01363v2)
- [Adaptor Signatures: New Security Definition and A Generic Construction for NP Relations](https://eprint.iacr.org/2024/1051)
- [From Slow Propagation to Partition: Analyzing Bitcoin Over Anonymous Routing](https://par.nsf.gov/biblio/10509863)
- [RFC 9591 The Flexible Round-Optimized Schnorr Threshold (FROST) Protocol for Two‑Round Schnorr Signatures](https://www.rfc-editor.org/rfc/rfc9591.html)
- [Shared-Custodial Password-Authenticated Deterministic Wallets](https://eprint.iacr.org/2024/1118)
- [Towards a Formal Foundation for Blockchain Rollups](https://arxiv.org/pdf/2406.16219v1)
- [Unforgeability of Blind Schnorr in the Limited Concurrency Setting](https://eprint.iacr.org/2024/1100)
- [Circle STARKs](https://eprint.iacr.org/2024/278)
- [FROST Federation](https://blog.opdup.com/development-updates/2024/07/04/frost-federation.html)

## Miscellaneous

- [COPA vs CSW – Injunctions Published](https://www.bailii.org/ew/cases/EWHC/Ch/2024/1809.html)
- [Foundry Announces 'Foundry Donate' Initiative to Support Open Source Bitcoin Community](https://www.prnewswire.com/news-releases/foundry-announces-foundry-donate-initiative-to-support-open-source-bitcoin-community-302203616.html)
- [Sixth Wave of Bitcoin Grants](https://opensats.org/blog/bitcoin-grants-july-2024-6th-wave)
- [OpenSats Education Initiative](https://opensats.org/blog/announcing-the-opensats-education-initiative)
- [Maelstrom Bitcoin grant program](https://maelstrom.fund/bitcoin-grant-program/)
- [Taproot Assets Mainnet Launch](https://lightning.engineering/posts/2024-07-23-taproot-assets-LN/)
- [Mt Gox coins finally distributed](https://x.com/davidlripley/status/1815880303254323603)
- [Mempool Accelerator Launch](https://mempool.space/accelerator)
- [Proton Wallet](https://proton.me/wallet)
- [Casa: Secure your bitcoin with a YubiKey](https://blog.casa.io/secure-your-bitcoin-with-yubikey/)
- [Fedi Launch Event](https://www.fedi.xyz/fedi-launch-event)
- [Mutiny Wallet shuts down](https://blog.mutinywallet.com/mutiny-wallet-is-shutting-down/)
- [Marathon Slipstream](https://slipstream.mara.com/)
    - [Mines "OP_CAT" transaction](https://mempool.space/tx/51bae58fa9d413b86d74da60d5366987dcdeb0586d39b93b2ca22f9e40dc83de?mode=details)
- [Satsto.me](https://satsto.me/) and [TwelveC ash](https://twelve.cash/)
- [Additive RBF batcher](https://github.com/CardCoins/additive-rbf-batcher/)
- [Stable Channels website](https://stablechannels.com/)
- [ZK Proof on Signet](https://x.com/StarkWareLtd/status/1813929304209723700)
- [Bitcoin Dollar](https://blog.nicolas-dorier.com/posts/bitcoin-dollar/)
- [Block: Welcoming Core Scientific, our first mining chip customer](https://www.mining.build/blog/first-mining-chip-customer/)

## Network Data

- [Mining Pool Behavior during Forks](https://b10c.me/blog/014-mining-pool-behavior-during-forks/)

## Europe/Germany/Berlin

- [Notveräußerung von fast 50.000 Bitcoins abgeschlossen](https://www.medienservice.sachsen.de/medien/news/1077662)

## Mailing Lists

### bitcoin-dev

- [Mining pools, stratumv2 and oblivious shares](https://mailing-list.bitcoindevs.xyz/bitcoindev/Zp%2FGADXa8J146Qqn@erisian.com.au/)

### Delving Bitcoin

- [Stats on compact block reconstructions](https://delvingbitcoin.org/t/stats-on-compact-block-reconstructions/1052)
- [Introduction to cluster linearization](https://delvingbitcoin.org/t/introduction-to-cluster-linearization/1032)
- [Cluster mempool: block building with sub-chunk granularity](https://delvingbitcoin.org/t/cluster-mempool-block-building-with-sub-chunk-granularity/1044)
- [Zawy’s Alternating Timestamp Attack](https://delvingbitcoin.org/t/zawy-s-alternating-timestamp-attack/1062)

## Pull requests

### BIPs, BOLTs and Proposals

- [ChillDKG: Distributed Key Generation for FROST](https://github.com/BlockstreamResearch/bip-frost-dkg)
- [Draft: FROST signing for BIP340-compatible Threshold Signatures](https://github.com/siv2r/bip-frost-signing)
- [BIP94: Testnet4](https://github.com/bitcoin/bips/pull/1601)

### Bitcoin Core

- [Public disclosure of 2 vulnerabilities affecting Bitcoin Core before v22.0](https://bitcoincore.org/en/security-advisories/)
- [policy: Add PayToAnchor(P2A), OP_1 <0x4e73> as a standard output script for spending #30352](https://github.com/bitcoin/bitcoin/pull/30352)
- [Testnet4 including PoW difficulty adjustment fix #29775](https://github.com/bitcoin/bitcoin/pull/29775)
- [p2p: For assumeutxo, download snapshot chain before background chain #29519](https://github.com/bitcoin/bitcoin/pull/29519)
- [assumeutxo: Drop block height from metadata #30598](https://github.com/bitcoin/bitcoin/pull/30598)
- [assumeutxo: Don't load a snapshot if it's not in the best header chain #30320](https://github.com/bitcoin/bitcoin/pull/30320)
- [policy: enable full-rbf by default #30493](https://github.com/bitcoin/bitcoin/pull/30493)
- [cluster mempool: cluster linearization algorithm #30126](https://github.com/bitcoin/bitcoin/pull/30126)
- [cluster mempool: merging & postprocessing of linearizations #30285](https://github.com/bitcoin/bitcoin/pull/30285)
- [Fee Estimation: change estimatesmartfee default mode to economical #30275](https://github.com/bitcoin/bitcoin/pull/30275)
- [Wallet: Add max_tx_weight to transaction funding options (take 2) #29523](https://github.com/bitcoin/bitcoin/pull/29523)
- [wallet: Migrate legacy wallets to descriptor wallets without requiring BDB #26596](https://github.com/bitcoin/bitcoin/pull/26596)

### LND

- [2/4 Route Blinding Receives: Receive and send to a single blinded path in an invoice. #8735](https://github.com/lightningnetwork/lnd/pull/8735)

### Eclair

- [Reject new static_remote_key channels #2881](https://github.com/ACINQ/eclair/pull/2881)
- [Add HTLC endorsement/confidence #2884](https://github.com/ACINQ/eclair/pull/2884)

### BDK & LDK

- [feat(electrum)!: Update bdk_electrum to use merkle proofs #1489](https://github.com/bitcoindevkit/bdk/pull/1489)

### Core Lightning

- BOLT12 Offers implementation series
    - [Part 1: offers cleanups #7454](https://github.com/ElementsProject/lightning/pull/7454)
    - [Part 2: connectd onionmessage improvements #7455](https://github.com/ElementsProject/lightning/pull/7455)
    - [Part 3: offers with paths #7456](https://github.com/ElementsProject/lightning/pull/7456)
    - [Part 4: offers for non-public nodes, and handling self-pay #7461](https://github.com/ElementsProject/lightning/pull/7461)
    - [Part 5: experimental range #7474](https://github.com/ElementsProject/lightning/pull/7474)
    - [Part 6: final catchup to latest BOLT spec #7476](https://github.com/ElementsProject/lightning/pull/7476)

### rust-bitcoin & rust-lightning

- [Authenticate use of offer blinded paths #3139](https://github.com/lightningdevkit/rust-lightning/pull/3139)
