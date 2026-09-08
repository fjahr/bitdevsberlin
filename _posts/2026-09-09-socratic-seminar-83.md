---
layout: post
title: "Socratic Seminar #83"
---

[Meetup](https://www.meetup.com/bitcoin-lab-berlin/events/fbqgptyjcmbfb/)

Thanks to [Ordimint](https://ordimint.com) for sponsoring food and drinks for this meetup!


## Special: Liquid Hack

- [Liquid got got!](https://x.com/ErgoBTC/status/2096665561392361473)
- [Current understanding of the Liquid hack](https://x.com/OrangeSurfBTC/status/2096765508431294843?s=20)
- [More details](https://x.com/mononautical/status/2096928595432374706?s=20)
- [Liquid hack explanation by Amboss](https://drop.amboss.tech/liquid-rangeproof-explainer.html)
- [Liquid/Blockstream chat history](https://x.com/intangiblecoins/status/2096996527822553307)

## Special: CISA

- [BIP458: Half-Aggregation of BIP 340 Signatures](https://github.com/bitcoin/bips/pull/2205)
- [BIP459: DahLIAS fully aggregated signatures for secp256k1](https://github.com/bitcoin/bips/pull/2210)
- [BIP460: CISA for Taproot Key Path Spends](https://github.com/bitcoin/bips/pull/2212)
- [CISA in Bitcoin Core](https://github.com/bitcoin/bitcoin/pull/36122)
- [CISA and PQC](https://delvingbitcoin.org/t/pqc-output-type-discussion/2749/15)
- [CISA companion bip drafts](https://github.com/fjahr/cisa-playground/)

## Security/CVEs/InfoSec/Research

- [Enabling Threshold Custody for the Lightning Network with Nested Threshold Multi-Signatures](https://eprint.iacr.org/2026/1757)
- [Crashing a lightning node with a flood of pings](https://erickcestari.dev/blog/ping-flood-oom/)
- [CLN vulnerability fix rollout](https://[118;1:3ux.com/Snyke/status/2092989040098181170)
- [RosettaBitcoin: An Artifact-Backed Experience Report on Verification Infrastructure for Agent-Assisted Consensus Validators](https://arxiv.org/abs/2609.01702)
- [Cryptocurrencies in the Quantum Age: Migration Paths to PQC](https://arxiv.org/abs/2608.22924)
- [BMuSig2: Schnorr-Compatible Blind Multi-Signatures](https://eprint.iacr.org/2026/1888)
- [Extracting and Verifying Illicit Bitcoin Addresses from Underground Forum Discussions](https://arxiv.org/abs/2608.13930)
- [Non-Interactive Translation of Winternitz Signatures to Lamport Signatures via Secret Sharing](https://eprint.iacr.org/2026/1684)
- [Scalable Exact Path Selection via Structure-Aware Search for Virtual Payment Channels](https://arxiv.org/abs/2608.22276)
- [Improved Collision Attack on RIPEMD-160](https://eprint.iacr.org/2026/1744)
- [A General Approach to Adaptor Signatures](https://eprint.iacr.org/2026/1889)
- [Scaling the Lightning Network with Practical Set Reconciliation](https://arxiv.org/abs/2608.15921)


## Network Data

- [Address Relay under stress](https://bnoc.xyz/t/address-relay-under-stress/163)
- [Address Relay under stress: Attack Characteristics and Measuring Its Effects](https://bnoc.xyz/t/address-relay-under-stress-attack-characteristics-and-measuring-its-effects/164)
- [Passive Traffic Analysis of Bitcoin P2P v2](https://bnoc.xyz/t/passive-traffic-analysis-of-bitcoin-p2p-v2/161)
- [Unreachable addresses in Bitcoin GETADDR responses](https://bnoc.xyz/t/unreachable-addresses-in-bitcoin-getaddr-responses/155)
- [Pesquisa Dashboard](https://pesquisa.hacknodes.xyz/)

## Local/Legal

- [Museum of Satoshi](https://mos.satoshiskids.org/)

## Miscellaneous

- [BIP300/Ecash fork keeps getting postponed](https://ecash.com/)
- [rBitcoin](https://rbitcoin.org/)
- [Another Coldcard analysis](https://praveenperera.com/blog/coldcard-mk3-weak-rng-wave1)
- [HRF grants 5 BTC to 16 freedom tech projects](https://hrf.org/latest/hrf-grants-500m-satoshis-to-16-freedom-tech-projects-worldwide/)
- [Test Bitcoin Core App preview](https://bitcoincore.app/)
- [Self-custody trilemma](https://lu.ke/self-custody-trilemma)
- [Trezor shipping provider data breach](https://trezor.io/blog/news/recent-customer-data-exposed-in-shipping-provider-incident)
- [PDK 1.0](https://payjoin.org/blog/2026/08/12/announcing-payjoin-1-0/)
- [Nation State Bitcoin Adoption report](https://jan3.com/blog/nation-state-bitcoin-adoption-report-2025)
- [Conduition on mapping Bitcoin's post-quantum landscape](https://brink.dev/blog/2026/08/17/eng-call-conduition-post-quantum/)
- [BIP110 post mortem](https://blog.lopp.net/bip-110-post-mortem/)
- [Peach is at a crossroads](https://peachbitcoin.com/blog/peach-at-a-crossroads/)
- [nix-bitcoin final version](https://x.com/nixbitcoinorg/status/2087880779892158679)
- [Bitcoin at Block open roadmap](https://block.xyz/bitcoin/roadmap)

## Mailing Lists

### bitcoin-dev

- [DropKick ⚽️ - A minimal commit/reveal PQ rescue protocol](https://groups.google.com/g/bitcoindev/c/6SqWPfBf-p0?pli=1)
- [static-pie release binaries available for testing](https://groups.google.com/g/bitcoindev/c/UgGHs-_YGvw)


### Delving Bitcoin

- [Universal opt-in replay protection?](https://delvingbitcoin.org/t/universal-opt-in-replay-protection/2792)
- [Transaction rate-limiting](https://delvingbitcoin.org/t/transaction-rate-limiting/2744)

## Pull requests

### BIPs, BOLTs and Proposals

- [BIP ???: SHRINCS: A Compact Hash-Based Signature Scheme](https://github.com/SHRINCS/shrincs-bip/blob/main/SHRINCS.md)

### Bitcoin Core

- [txindex: hash keys and pack positions to reduce disk usage #35531](https://github.com/bitcoin/bitcoin/pull/35531)
- [wallet: derivehdkey RPC to get xpub at arbitrary path #32784](https://github.com/bitcoin/bitcoin/pull/32784)
- [fees: Introduce Mempool Based Fee Estimation to reduce overestimation #34075](https://github.com/bitcoin/bitcoin/pull/34075)
- [wallet: store all witness variants of a transaction #35501](https://github.com/bitcoin/bitcoin/pull/35501)
- [wallet: avoid a crash when creating a wallet with -nosettings #36176](https://github.com/bitcoin/bitcoin/pull/36176)
- [miner: Enforce Murch-Zawy rule (BIP54) #35949](https://github.com/bitcoin/bitcoin/pull/35949)

### LND

- [peer: bound peer-controlled resource growth #11090](https://github.com/lightningnetwork/lnd/pull/11090)
- [Add Outbound Remote Signer implementation #8754](https://github.com/lightningnetwork/lnd/pull/8754)

### Core Lightning

- [Askrene and xpay improve #9150](https://github.com/ElementsProject/lightning/pull/9150)
- [wallet: add bwatch-backed output and transaction tables #9298](https://github.com/ElementsProject/lightning/pull/9298)

### Eclair

- [Fix several on-the-fly-funding bugs #3351](https://github.com/ACINQ/eclair/pull/3351)
- [Reject messages that include the wrong type of signatures #3368](https://github.com/ACINQ/eclair/pull/3368)

### BDK/rust-bitcoin & LDK/rust-lightning

- [primitives: Apply the witness item size limit to every element #6642](https://github.com/rust-bitcoin/rust-bitcoin/pull/6642)

### Others

- [HWI: Future of this repo #850](https://github.com/bitcoin-core/HWI/issues/850)
