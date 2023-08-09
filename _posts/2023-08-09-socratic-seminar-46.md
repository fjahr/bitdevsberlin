---
layout: post
title: "Socratic Seminar #46"
---

[Meetup](https://www.meetup.com/bitcoin-lab-berlin/events/294929494/)

Thanks to [Wasabi Wallet](https://wasabiwallet.io/) for sponsoring food and drinks for this meetup!

## Security/CVEs/InfoSec/Research

- [LN Metrics - Open Source LN data collection initiative](https://github.com/LNOpenMetrics/lnmetrics.rfc)
- [Manually (on paper) calculating a public key from a private key](https://bitcoin.stackexchange.com/questions/118933/how-can-i-manually-on-paper-calculate-a-bitcoin-public-key-from-a-private-key/118939#118939)
- [Waiting for confirmation: a series about mempool and relay policy](https://bitcoinops.org/en/blog/waiting-for-confirmation/)
- [Anatomy of a Bitcoin Heist: The Electrum Atom Malware Saga](https://medium.com/@nbax/anatomy-of-a-bitcoin-heist-the-electrum-atom-malware-saga-1685abf7c903)
- [Lightning Creation Games](https://arxiv.org/abs/2306.16006v1)
- [Towards a Formal Verification of the Lightning Network with TLA+](https://arxiv.org/abs/2307.02342v1)
- [How the Great Firewall of China Detects and Blocks Fully Encrypted Traffic](https://gfw.report/publications/usenixsecurity23/en/)
- [Covenants in Bitcoin: A Useful Review Taxonomy](https://rusty.ozlabs.org/2023/07/09/covenant-taxonomy.html)
- [Towards a trustless bitcoin wallet with miniscript](https://www.ledger.com/blog/towards-a-trustless-bitcoin-wallet-with-miniscript)
- [PHD thesis about new watchtower FPPW and new payment channel Daric](https://bridges.monash.edu/articles/thesis/Layer-2_Solutions_for_Bitcoin_Scalability/23788107)
- [TeleBTC: Trustless Wrapped Bitcoin](https://arxiv.org/abs/2307.13848)
- [Temporal and Geographical Analysis of Real Economic Activities in the Bitcoin Blockchain](https://arxiv.org/abs/2307.08616)
- [Entropy bug in Libbitcoin Explorer: Milk Sad](https://milksad.info/)

## Miscellaneous

- [HRF Bitcoin Bounty Challenge](https://hrfbounties.org/)
- [Chris Belcher health situation](https://gist.github.com/chris-belcher/ca5051285c6f8d38693fd127575be44d#update)
- [Royllo.org - Taproot Assets Explorer](https://twitter.com/royllo_org/status/1680910896569229312)
- [ChatBTC](https://chat.bitcoinsearch.xyz/#chat)
- [Frostsnap](https://frostsnap.com/introducing-frostsnap.html)
- [War and Lightning Network](https://notgeld.medium.com/war-and-lightning-network-86f30cdc5c09)
- [Mutiny Wallet beta release](https://blog.mutinywallet.com/mutiny-wallet-open-beta/)
- [Matador: A Bitcoin-Powered Passthrough Server](https://github.com/Kodylow/matador)
- [Bitmex: Drivechains](https://blog.bitmex.com/drivechains/)
- [Galaxy Mining: 2023 Bitcoin Mining Mid-Year Report](https://www.galaxy.com/insights/research/2023-mid-year-mining/)

## Network Data

- [Revisiting Bitcoin Network Bandwidth Issues](https://blog.lopp.net/revisiting-bitcoin-network-bandwidth-issues/)

## Europe/Germany/Berlin

- [Bitcoin im Bundestag](https://bitcoin-im-bundestag.de/)

## Mailing Lists

### bitcoin-dev

- [Pull-req to enable Full-RBF by default](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-July/021823.html)
- [Blinded 2-party Musig2](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-July/021792.html)
- [BIP-352 Silent Payments addresses should have an expiration time](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-August/021849.html)

### lighting-dev

- [Jamming Mitigation Dry Run](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-August/004034.html)

## Pull requests

### Bitcoin Core

- [p2p: Restrict self-advertisements with privacy networks to avoid fingerprinting #27411](https://github.com/bitcoin/bitcoin/pull/27411)
- [bumpfee: Allow the user to choose which output is change #26467](https://github.com/bitcoin/bitcoin/pull/26467)
- [Rework validation logic for assumeutxo #27746](https://github.com/bitcoin/bitcoin/pull/27746)

### LND

- [funding: fund channel with selected utxos](https://github.com/lightningnetwork/lnd/pull/7516)

### Eclair

- [Add quiescence negotiation #2680](https://github.com/ACINQ/eclair/pull/2680)

### Core Lightning

- [renepay: an experimental payment plugin](https://github.com/ElementsProject/lightning/pull/6376)
- [splicing: Adds the features needed to enable collaborative splicing & resizing of active channels.](https://github.com/ElementsProject/lightning/pull/6253)
- [Taproot wallet support #6035](https://github.com/ElementsProject/lightning/pull/6035)
- [Self-pay support. #6399](https://github.com/ElementsProject/lightning/pull/6399)
- [Runes migration from commando to lightning #6403](https://github.com/ElementsProject/lightning/pull/6403)

### Secp256k1

- [ci: Test on development snapshots of GCC and Clang #1313](https://github.com/bitcoin-core/secp256k1/pull/1313)

### BTCPayServer

- [Add reporting feature #5155](https://github.com/btcpayserver/btcpayserver/pull/5155)
