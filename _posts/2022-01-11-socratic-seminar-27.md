---
layout: post
title: "Socratic Seminar #27"
---

[Meetup](https://www.meetup.com/Bitcoin-Lab-Berlin/events/rkzdqsydccbpb/)

## Security/CVEs/InfoSec/Research

- [Disclosing Shamir’s Secret Sharing vulnerabilities and announcing ZKDocs](https://blog.trailofbits.com/2021/12/21/disclosing-shamirs-secret-sharing-vulnerabilities-and-announcing-zkdocs/)
  - [tbast comment](https://twitter.com/realtbast/status/1473323288759787524)
- [Financial Cryptography and Data Security 2022](https://fc22.ifca.ai/program.html)
- [Short Paper: What Peer Announcements Tell Us About the Size of the Bitcoin P2P Network](https://fc22.ifca.ai/preproceedings/114.pdf)
- [Analysis and Probing of Parallel Channels in the Lightning Network](https://fc22.ifca.ai/preproceedings/132.pdf)
- [Short Paper: On the Claims of Weak Block Synchronization in Bitcoin](https://fc22.ifca.ai/preproceedings/183.pdf)
- [Security and performance evaluation of master node protocol based reputation blockchain in the bitcoin network](https://www.sciencedirect.com/science/article/pii/S2096720921000439)
- [Short Paper: A Centrality Analysis of the Lightning Network](http://eprints.cs.univie.ac.at/7191/1/fc22_39.pdf)

## Miscellaneous

- [Learning Bitcoin from the Commandline translations Portuguese and Spanish](https://github.com/BlockchainCommons/Learning-Bitcoin-from-the-Command-Line)
- [Podcast: Bitcoin Explained Compact Blocks](https://nadobtc.libsyn.com/bitcoin-explained-51-compact-blocks)
- [Nostr](https://github.com/fiatjaf/nostr)
- [A Bitcoiner's Vision for the Web 3.0](https://gist.github.com/elsirion/0d0c5ad6460745d726c7f1953b6667c4)
- [Writing a Bitcoin Book for Policymakers](https://www.kickstarter.com/projects/bitcoinamericandream/help-us-publish-our-bitcoin-book)
- [Krux](https://jreesun.github.io/krux/)
- [Lightning Jet Rebalancer](https://github.com/itsneski/lightning-jet)
- [The Bitcoin Machine](https://thebitcoinmachines.com/)
- [HRF Lightning Grants](https://bitcoinmagazine.com/business/hrf-strike-launch-lightning-bounty-in-bitcoin)
- [CardCoins Enables LN Support for Users Buying Bitcoin with Cash](https://twitter.com/cardcoinsco/status/1471162591229657095)
- [Hundreds Of El Salvador Citizens Report Their Bitcoins Are disappearing From State Owned Chivo Wallet](https://thecryptobasic.com/2021/12/25/hundreds-of-el-salvador-citizens-report-their-bitcoins-are-disappearing-from-stated-owned-chivo-wallet/)
- [Binance converts taproot->segwit. User loses funds.](https://bitcoin.stackexchange.com/questions/111440/is-it-possible-to-convert-a-taproot-address-into-a-native-segwit-address)

## Europe/Germany/Berlin

- [Pressespiegel - Delegationsreise El Salvador](https://docs.google.com/spreadsheets/d/1ZmXU6Ug0zURvh9FWe4gWqzOZmxh2l619pu9WQkyCLqY/preview)
- [CRE224 Elektronisches Geld 2](https://cre.fm/cre224-elektronisches-geld-2)

## Mailing Lists

### bitcoin-dev

- [Proposal: Full-RBF in Bitcoin Core 24.0](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2021-December/019696.html)
- [Pre-BIP: Fee Accounts](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2022-January/019724.html)
- [Bitcoin Advent Calendar: Decentralized Coordination Free Mining Pools](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2021-December/019662.html)
- [BIP-119 Deployment and Review Workshops](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2021-December/019719.html)
- [Stumbling into a contentious soft fork activation attempt](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2022-January/019728.html)

### lighting-dev

- [Split payments within one LN invoice](https://lists.linuxfoundation.org/pipermail/lightning-dev/2021-December/003410.html)
- [Payment sender authentication](https://lists.linuxfoundation.org/pipermail/lightning-dev/2021-December/003422.html)

## Pull requests

### BIPs, BOLTs and Proposals

- [BOLT-02+09: introduce feature bit to gate new channel_type feature - 44/45 #906](https://github.com/lightning/bolts/pull/906)
- [BIP 52: Durable, Low Energy Bitcoin PoW #1126](https://github.com/bitcoin/bips/pull/1126)
- [Add BIP nsequence anti-fee-snipe #1269](https://github.com/bitcoin/bips/pull/1269)

### Bitcoin Core

- [validation: mempool validation and submission for packages of 1 child + parents #22674](https://github.com/bitcoin/bitcoin/pull/22674)
- [docs: RBF policy and mempool limit exemptions #23711](https://github.com/bitcoin/bitcoin/pull/23711)
- [BIP 174: PSBT version, proprietary, and xpub fields #17034](https://github.com/bitcoin/bitcoin/pull/17034)
- [Expose block filters over REST #17631](https://github.com/bitcoin/bitcoin/pull/17631)
- [Address type dropdown, add Taproot (Receive tab) #459](https://github.com/bitcoin-core/gui/pull/459)
- [Update libsecp256k1 subtree to current master #23383](https://github.com/bitcoin/bitcoin/pull/23383)
- [build, qt: Use Android NDK r23 LTS #23677](https://github.com/bitcoin/bitcoin/pull/23677)
- [tracing: utxocache tracepoints #22902](https://github.com/bitcoin/bitcoin/pull/22902)
- [test: Let test_runner.py start multiple jobs per timeslot #23799](https://github.com/bitcoin/bitcoin/pull/23799)
- [Add warnings to createmultisig and addmultisig if using uncompressed keys #23113](https://github.com/bitcoin/bitcoin/pull/23113)
- [test: replace hashlib.ripemd160 with an own implementation #23716](https://github.com/bitcoin/bitcoin/pull/23716)
- [PSBT: hash preimages fields by darosior #23718](https://github.com/bitcoin/bitcoin/pull/23718)
- [build, Android: fix GUI not loading on Qt 5.15 #23757](https://github.com/bitcoin/bitcoin/pull/23757)

### BTCD

- [multi: implement BIP 341 and 342 a.k.a complete taproot and tapscript consensus verification logic #1787](https://github.com/btcsuite/btcd/pull/1787)

### secp256k1
 
- [MuSig2 merged into secp256k1-zkp](https://github.com/ElementsProject/secp256k1-zkp/pull/131)
- [Add release-process.md #964](https://github.com/bitcoin-core/secp256k1/pull/964)

## Newsletters

- [Bitcoin Optech #179](https://bitcoinops.org/en/newsletters/2021/12/15/)
- [Bitcoin Optech #180: 2021 Year-in-Review Special](https://bitcoinops.org/en/newsletters/2021/12/22/)
- [Bitcoin Optech #181](https://bitcoinops.org/en/newsletters/2022/01/05/)
