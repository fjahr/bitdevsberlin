---
layout: post
title: "Socratic Seminar #44"
---

[Meetup](https://www.meetup.com/bitcoin-lab-berlin/events/293451009/)

Thanks to [Wasabi Wallet](https://wasabiwallet.io/) for sponsoring food and drinks for this meetup!

## Security/CVEs/InfoSec/Research

- [Ledger vulnerability disclosure](https://wizardsardine.com/blog/ledger-vulnerability-disclosure/)
- [Send My: Arbitrary data transmission via Apple's Find My network](https://positive.security/blog/send-my)
- [Case study: fake hardware cryptowallet](https://www.kaspersky.com/blog/fake-trezor-hardware-crypto-wallet/48155/)
- [Mint the Future with Taproot Assets v0.2 🌿🔮](https://lightning.engineering/posts/2023-05-16-taproot-assets-v0.2/)
- [Ark - New layer 2 design](https://www.arkpill.me/)
  - [Simplest Ark Explanation](https://gist.github.com/RubenSomsen/a394beb1dea9e47e981216768e007454)
  - [BOATs](https://github.com/ark-network/boats)
- [Miner Fee Gathering Capability (Part 2) – Out of Band Fees](https://blog.bitmex.com/miner-fee-gathering-capability-part-2-out-of-band-fees/)
- [Security and Performance Analysis of Elliptic Curve Crypto System using Bitcoin Curves](https://www.researchgate.net/profile/Mdsameeruddin-Khan/publication/370939924_Security_and_Performance_Analysis_of_Elliptic_Curve_Crypto_System_using_Bitcoin_Curves/links/646b244127938813482b95d2/Security-and-Performance-Analysis-of-Elliptic-Curve-Crypto-System-using-Bitcoin-Curves.pdf)
- [BSHUNTER: Detecting and Tracing Defects of Bitcoin Scripts](https://zhengpeilin.com/research/BSHunter.pdf)
- [Amboss - Chain Surveillance Selling Your Data?](https://stacker.news/items/182218)
- [The curious case of the half-half Bitcoin ECDSA nonces](https://eprint.iacr.org/2023/841.pdf)
- [Darkpool (tarpit) concept](https://gist.github.com/moonsettler/6a214f5d01148ea204e9131b86a35382)

## Miscellaneous

- [Ledger Recover: Recover your keys using your identity](https://www.ledger.com/recover)
- [ACINQ: Securing a $100M lightning node](https://acinq.co/blog/securing-a-100M-lightning-node)
- [Mempool Accelerator](https://twitter.com/mempool/status/1659619347910803466)
- [The Genesis Book (Aaron van Wirdum)](https://twitter.com/aaronvanw/status/1659935693890547712)
- [ECB CBDC prototype summary](https://www.ecb.europa.eu/pub/pdf/other/ecb.prototype_summary20230526~71d0b26d55.en.pdf)
- [Bitcoin Core 25.0 release notes](https://github.com/bitcoin/bitcoin/blob/master/doc/release-notes/release-notes-25.0.md)

## Network Data

- [Fees retreating after peak in May 2023, higher base](https://bitcoinvisuals.com/chain-fees-day)
- [12M Inscriptions paid $45M YTD](https://dune.com/dgtl_assets/bitcoin-ordinals-analysis)

## Europe/Germany/Berlin

- [NRW tax office received bitcoin.de customer data](https://www.spiegel.de/panorama/nordrhein-westfalen-steuerermittlungen-gegen-nutzer-von-kryptowaehrungs-plattformen-a-14f68845-d9b7-44b8-832f-a120e74b6fe5?sara_ref=re-so-app-sh)
- [Binance sperrt Handel mit Privacy Coins in Teilen der EU](https://www.heise.de/news/Monero-und-Co-Binance-schraenkt-Handel-mit-Privacy-Coins-in-Teilen-der-EU-ein-9154905.html)
- [ECB CBDC prototype summary](https://www.ecb.europa.eu/pub/pdf/other/ecb.prototype_summary20230526~71d0b26d55.en.pdf)

## Mailing Lists

### bitcoin-dev

- [Standardisation of an unstructured taproot annex](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-June/021731.html)
- [ZeroSync: Introducing Validity Proofs to Bitcoin](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-May/021679.html)
- [Bitcoin Transaction Relay over Nostr](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-May/021700.html)

### lighting-dev

- [HTLC Endorsement for Jamming Mitigation](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-May/003928.html)

## Pull requests

### BIPs, BOLTs and Proposals

- [Proposal for a new mempool design #27677](https://github.com/bitcoin/bitcoin/issues/27677)
- [Silent Payments finalized BIP](https://github.com/bitcoin/bips/pull/1458/files)
- [Implementation in Bitcoin Core](https://github.com/bitcoin/bitcoin/pull/27827)

### Bitcoin Core

- [Implement Mini version of BlockAssembler to calculate mining scores #27021](https://github.com/bitcoin/bitcoin/pull/27021)
- [p2p: Avoid prematurely clearing download state for other peers #27608](https://github.com/bitcoin/bitcoin/pull/27608)
- [wallet: improve IBD sync time by skipping block scanning prior birth time #27469](https://github.com/bitcoin/bitcoin/pull/27469)
- [Parallel compact block downloads, take 3 #27626](https://github.com/bitcoin/bitcoin/pull/27626)

### LND

- [multi: accept memo note when opening channel #7668](https://github.com/lightningnetwork/lnd/pull/7668)
- [sweep+lnrpc: enforce provided fee rate is no less than relay fee #7645](https://github.com/lightningnetwork/lnd/pull/7645)

### Eclair

- [Add upper bound on fees paid during force-close #2668](https://github.com/ACINQ/eclair/pull/2668)
- [Add cpfp-bump-fees API #1783](https://github.com/ACINQ/eclair/pull/1783)

### BDK & LDK

- [Dual funding and interactive tx construction wire messages #1794](https://github.com/lightningdevkit/rust-lightning/pull/1794)
- [Disconnect peers on timer ticks to unblock channel state machine #2293](https://github.com/lightningdevkit/rust-lightning/pull/2293)
