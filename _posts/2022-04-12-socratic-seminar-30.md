---
layout: post
title: "Socratic Seminar #30"
---

[Meetup](https://www.meetup.com/Bitcoin-Lab-Berlin/events/rkzdqsydcfblb/)

## Security/CVEs/InfoSec/Research

- [Jameson Lopp on the evolution of Bitcoin Core performance](https://blog.lopp.net/bitcoin-core-performance-evolution/)
- [Simple Three-Round Multiparty Schnorr Signing with Full Simulatability](https://eprint.iacr.org/2022/374.pdf)
- [The evolution of mining pools and miners’ behaviors in the Bitcoin blockchain](https://hal.archives-ouvertes.fr/hal-03610424/document)
- [World Bank: Crypto-Assets Activity around the World: Evolution and Macro-Financial Drivers](https://openknowledge.worldbank.org/handle/10986/37115)
- [Usability of Cryptocurrency Wallets Providing CoinJoin Transactions](https://eprint.iacr.org/2022/285.pdf)
- [Mixing detection on Bitcoin transactions using statistical patterns](https://arxiv.org/abs/2204.02019)
- [Attacking Bitcoin anonymity: generative adversarial networks for improving Bitcoin entity classification](https://link.springer.com/content/pdf/10.1007/s10489-022-03378-7.pdf)
- [Master Thesis: Do Some Bitcoin Exchanges Lead the Others? An Empirical Analysis](http://hanyang.dcollection.net/public_resource/pdf/200000590764_20220324225259.pdf)
- [Electrical powerconsumption reduction in the bitcoinmining process using phase change material](https://fupubco.com/fuen/article/view/2/11)
- [Silent Payments](https://gist.github.com/RubenSomsen/c43b79517e7cb701ebf77eec6dbb46b8)
- [Jacob Applebaum PhD: Communication in a world of pervasive surveillance: Sources and methods: Counter-strategies against pervasive surveillance architecture](https://research.tue.nl/en/publications/communication-in-a-world-of-pervasive-surveillance-sources-and-me)
- [Coinbase announces TRUST](https://blog.coinbase.com/introducing-the-travel-rule-universal-solution-technology-trust-232774d76674)
- [Announcing Taro: A New Protocol for Multi-Asset Bitcoin and Lightning](https://lightning.engineering/posts/2022-4-5-taro-launch/)

## Miscellaneous

- [Block releases details of their open source wallet](https://wallet.build/march-update/)
- [rust-teos alpha release](https://twitter.com/sr_gi/status/1502327696134713348)
- [The Lightning Network in 2022 Panel - Meetup Transcript](https://github.com/bitcointranscripts/bitcointranscripts/blob/master/london-bitcoin-devs/2022-03-01-lightning-panel.md)
- [Wasabi Wallet’s CoinJoin Coordinator to Blacklist Certain Bitcoin Transactions](https://www.coindesk.com/tech/2022/03/14/wasabi-wallets-coinjoin-coordinator-to-blacklist-certain-bitcoin-transactions/)
- [New Electrum release](https://github.com/spesmilo/electrum/blob/master/RELEASE-NOTES)
- [Announcement of Strategic Partnership Between Seetee and Ten31](https://ten31.vc/content/seetee)
- [Bitcoin Bounties](https://bitcoinbounties.org/)
- [Change the code, not the climate](https://www.cleanupbitcoin.com/)
- [Change the climate, not the code](https://www.change.org/p/change-the-climate-not-the-code)
- [c-lightning is now Core Lightning](https://blog.blockstream.com/en-c-lightning-is-now-core-lightning/)
- [Announcing Brink's Latest Round of Developer Grants](https://brink.dev/blog/2022/04/04/grantees/)

## Europe/Germany/Berlin

- [Status MiCA](https://www.europarl.europa.eu/legislative-train/theme-a-europe-fit-for-the-digital-age/file-crypto-assets-1)
- [ARTE: Sind Kryptowährungen das bessere Geld? 42 - Die Antwort auf fast alles](https://www.youtube.com/watch?v=vOLZzlM_pG8)
- [DWP Bank plant Bitcoin-Start in 2022](https://www.wiwo.de/kryptohandel-dwp-bank-plant-bitcoin-start-in-2022/28225208.html)

## Mailing Lists

### bitcoin-dev

- [Covenants and feebumping](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2022-March/020122.html)
- [Silent Payments – Non-interactive private payments with no on-chain overhead](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2022-March/020180.html)
- [mempool transaction witness-replacement](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2022-March/020167.html)
- [Simple step one for quantum](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2022-April/020209.html)

### lighting-dev

- [Code for sub second runtime of piecewise linarization to quickly approximate the minimum convex cost flow problem (makes fast multi part payments with large amounts possible)](https://lists.linuxfoundation.org/pipermail/lightning-dev/2022-March/003510.html)
- [Taproot-aware Channel Announcements + Proof Verification](https://lists.linuxfoundation.org/pipermail/lightning-dev/2022-March/003526.html)
- [Dynamic Commitments Part 2: Taprooty Edition](https://lists.linuxfoundation.org/pipermail/lightning-dev/2022-March/003531.html)

## Pull requests

### BIPs, BOLTs and Proposals

- [MuSig2 BIP draft](https://github.com/jonasnick/bips/blob/musig2/bip-musig2.mediawiki)
- [BIP 326: Anti-fee-sniping protection with nSequence in taproot transactions to improve privacy for off-chain protocols #1269](https://github.com/bitcoin/bips/pull/1269)

### Bitcoin Core

- [doc: create initial doc/cjdns.md for CJDNS how-to documentation #24555](https://github.com/bitcoin/bitcoin/pull/24555)
- [Add 'sendall' RPC née sweep #24118](https://github.com/bitcoin/bitcoin/pull/24118)
- [Enforce Taproot script flags whenever WITNESS is set #23536](https://github.com/bitcoin/bitcoin/pull/23536)
- [net: open p2p connections to nodes that listen on non-default ports #23542](https://github.com/bitcoin/bitcoin/pull/23542)
- [Add (sorted)multi_a descriptor for k-of-n multisig inside tr #24043](https://github.com/bitcoin/bitcoin/pull/24043)
- [kernel 0/n: Introduce bitcoin-chainstate #24304](https://github.com/bitcoin/bitcoin/pull/24304)

### LND

- [lnrpc: Add destination output information (pkScript, output index, amount and if output belongs to the node) #5476](https://github.com/lightningnetwork/lnd/pull/5476)
- [Taproot: integrate btcec/v2 and btcwallet changes to support Taproot key spend paths in lnd's wallet #6263](https://github.com/lightningnetwork/lnd/pull/6263)
- [htlcswitch: add an always on mode to htlc interceptor #6232](https://github.com/lightningnetwork/lnd/issues/6232)

### Eclair

- [Add channelbalances API call #2196](https://github.com/ACINQ/eclair/pull/2196)

### LDK

- [Support for SCID Aliases #1311](https://github.com/lightningdevkit/rust-lightning/pull/1311)
- [Add random 'shadow route' CLTV delta offsets to improve privacy. #1286](https://github.com/lightningdevkit/rust-lightning/pull/1286)
- [Add low_r signature grinding #1388](https://github.com/lightningdevkit/rust-lightning/pull/1388)

### c-lightning

- [Multiple channel support. #5078](https://github.com/ElementsProject/lightning/pull/5078)
- [setchannel: new command #5103](https://github.com/ElementsProject/lightning/pull/5103)
- [cln-grpc-plugin: Secure access to your node over the network #5013](https://github.com/ElementsProject/lightning/pull/5013)
- [invoice description hash support #5121](https://github.com/ElementsProject/lightning/pull/5121)

### rust-bitcoin

- [Make TaprootBuilder able to generate Huffman Tree #909](https://github.com/rust-bitcoin/rust-bitcoin/pull/909)

### HWI

- [bitbox02: update to v6.0.0, enable sending to Taproot addresses #584](https://github.com/bitcoin-core/HWI/pull/584)
- [trezor: Remove support for external inputs #581](https://github.com/bitcoin-core/HWI/pull/581)


## Newsletters

- [Bitcoin Optech](https://bitcoinops.org/)
