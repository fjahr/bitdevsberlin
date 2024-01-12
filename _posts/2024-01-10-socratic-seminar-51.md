---
layout: post
title: "Socratic Seminar #51"
---

[Meetup](https://www.meetup.com/bitcoin-lab-berlin/events/297822131/)

Thanks to [Ordimint](https://ordimint.com) for sponsoring food and drinks for this meetup!

## Security/CVEs/InfoSec/Research

- [Statistical and clustering analysis of attributes of Bitcoin backbone nodes](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10631630/)
- [Terrapin Attack: Breaking SSH Channel Integrity By Sequence Number Manipulation](https://arxiv.org/abs/2312.12422)
- [Node Performance Tests 2023](https://blog.lopp.net/2023-bitcoin-node-performance-tests/)
- [V3 Transactions Review](https://petertodd.org/2023/v3-transactions-review)
- [Maypoles: Lightning Striking Twice](https://eprint.iacr.org/2023/1964.pdf)
- [Decentralized Opinion Leadership: A Study of Crypto Influencers in the Twitter Discourse on Bitcoin](https://scholarspace.manoa.hawaii.edu/items/3f6dd151-5557-48bd-91e6-26ed1fc5a646)
- [Non-Intrusive Balance Tomography Using Reinforcement Learning in the Lightning Network](https://dl.acm.org/doi/abs/10.1145/3639366)
- [Rational Economic Behaviours in the Bitcoin Lightning Network](https://arxiv.org/pdf/2312.16496.pdf)
- [CPU usage of peers](https://delvingbitcoin.org/t/cpu-usage-of-peers/196/2)
- [Comparing the Lightning Network to validia chains and validity rollups](https://lightco.in/2023/12/13/lightning-validia-rollups/)
- [AI generated Bitcoin Core Wiki-style documentation](https://wiki.mutable.ai/bitcoin/bitcoin)
- [Mercury Layer](https://mercurylayer.com/)
- [Bitcoin Layer Two Scaling Solutions:Lightening Payment Channels Network Comprehensive Review, Mechanisms, Challenges, Open Issues and Future Research Directions](https://journal.esj.edu.iq/index.php/IJCM/article/view/873/332)
- [Feldman’s Verifiable Secret Sharing for a Dishonest Majority](https://eprint.iacr.org/2024/031.pdf)

## Miscellaneous

- [PlebLab Top Builder Hackathon](https://www.topbuilder.dev/)
- [OpenSats Grants](https://opensats.org/blog/bitcoin-grants-december-2023)
- [HRF grants 500k$](https://bitcoinmagazine.com/business/human-rights-foundation-grants-500000-to-18-bitcoin-projects-worldwide?ref=nobsbitcoin.com)
- [The Genesis Book: The Story of the People and Projects That Inspired Bitcoin](https://www.amazon.com/gp/product/B0CQLMQRH7)
- [Lampo - LDK based Lightning Node](https://lampo.devcrew.cc/blog/v23.12/)
- [JAN3 Aqua wallet](https://aquawallet.io/)
- [BitVaulty wallet](https://www.bitvaulty.com/)
- [LN Symetry Recap](https://delvingbitcoin.org/t/ln-symmetry-project-recap/359)
- [Bitcoin Elftrace](https://github.com/halseth/elftrace)
- [Ark Developer Hub](https://arkdev.info/)
- [Introduce sCrypt: a Layer-1 Smart Contract Framework for BTC](https://xiaohuiliu.medium.com/introduce-scrypt-a-layer-1-smart-contract-framework-for-btc-b8b39c125c1a)

## Europe/Germany/Berlin

- [Was haben Bitcoiner eigentlich von Cotar](https://yeolddoc.substack.com/p/was-haben-bitcoiner-eigentlich-von)

## Mailing Lists

### bitcoin-dev

- [V3 Transactions are still vulnerable to significant tx pinning griefing attacks](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-December/022211.html)
- [Follow-up on Delving Bitcoin](https://delvingbitcoin.org/t/v3-transaction-policy-for-anti-pinning/340)

### lighting-dev

- [Scaling Lightning Safely With Feerate-Dependent Timelocks](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-December/004254.html)

### Delving Bitcoin

- [Denial-of-service bugs in LND’s channel update gossip handling](https://delvingbitcoin.org/t/denial-of-service-bugs-in-lnds-channel-update-gossip-handling/314/1)
- [Package aware Fee estimator post cluster mempool](https://delvingbitcoin.org/t/package-aware-fee-estimator-post-cluster-mempool/312)
- [GutterGuard and CoinGrinder Simulation results](https://delvingbitcoin.org/t/gutterguard-and-coingrinder-simulation-results/279)
- [Aggregate delegated exit for L2 pools](https://delvingbitcoin.org/t/aggregate-delegated-exit-for-l2-pools/297)
- [Unspendable keys in descriptors](https://delvingbitcoin.org/t/unspendable-keys-in-descriptors/304)

## Pull requests

### Bitcoin Core

- [wallet: skip BnB when SFFO is enabled #28994](https://github.com/bitcoin/bitcoin/pull/28994)
- [doc: Add multiprocess design doc #28978](https://github.com/bitcoin/bitcoin/pull/28978)

### LND

- [missioncontrol: add invalid onion blinding handling for blinded paths #8095](https://github.com/lightningnetwork/lnd/pull/8095)
- [routing: Add Validation for Decoding Blinded Paths #8142](https://github.com/lightningnetwork/lnd/pull/8142)

### Eclair

- [Use bitcoinheaders.net v2 format #2787](https://github.com/ACINQ/eclair/pull/2787)

### BDK & LDK

- [Support receiving to multi-hop blinded paths #2688](https://github.com/lightningdevkit/rust-lightning/pull/2688)

### Core Lightning

- [Force cltv field inclusion in BOLT 11 invoice #6957](https://github.com/ElementsProject/lightning/pull/6957)
- [Gossip cleanup part 1: Removing reliance on private gossip messages #6869](https://github.com/ElementsProject/lightning/pull/6869)

### BTCPayServer

- [Use Mempoolspace fees #5490](https://github.com/btcpayserver/btcpayserver/pull/5490)
