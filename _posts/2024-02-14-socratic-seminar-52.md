---
layout: post
title: "Socratic Seminar #52"
---

[Meetup](https://www.meetup.com/bitcoin-lab-berlin/events/298337243/)

Thanks to [Ordimint](https://ordimint.com) for sponsoring food and drinks for this meetup!

This time, we will have special guest: Aaron van Wirdum. Aaron is a Bitcoin-journalist and has been a key contributor to Bitcoin Magazine, holding various roles including editor-in-chief. He'll give a brief presentation of his latest work "The Genesis Book". It will be followed by a fireside chat and open discussion about the pre-history of Bitcoin and everything that lead to its inception: From Austrian economics to cryptography, from the Cypherpunks to transhumanism, from bit gold to e-gold.

This also means we will only discuss a few selected topics from the list below. If any of the topics are especially interesting to you and you want to make sure they are discussed, please come prepared and speak up if its not among the topics our presenters have selected.

## Security/CVEs/InfoSec/Research

- [Bitcoin Inscriptions: Foundations and Beyond (Tech Report)](https://arxiv.org/pdf/2401.17581.pdf)
- [A Cradle-to-Gate Life Cycle Analysis of Bitcoin Mining Equipment Using Sphera LCA and ecoinvent Databases](https://arxiv.org/pdf/2401.17512.pdf)
- [Ledger Connect Kit Exploit](https://www.ledger.com/blog/a-letter-from-ledger-chairman-ceo-pascal-gauthier-regarding-ledger-connect-kit-exploit)
- [Critical issue in BTCPayServer disclosed](https://twitter.com/BtcpayServer/status/1739669361223172448)
- [Bitcoin Clique: Channel-free Off-chain Payments using Two-Shot Adaptor Signatures](https://eprint.iacr.org/2024/025)
- [EROR: Efficient Repliable Onion Routing with Strong Provable Privacy](https://eprint.iacr.org/2024/020)
- [FlexHi: A Flexible Hierarchical Threshold](https://eprint.iacr.org/2024/024)
- [Self-Balancing Semi-Hierarchical PCNs for CBDCs](https://arxiv.org/abs/2401.11868v1)
- [Statistical and clustering analysis of attributes of Bitcoin backbone nodes](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10631630/)

## Miscellaneous

- [psst: Paper-based Secret Sharing Technique](https://github.com/Sjlver/psst)
- [egodeath.capital raises 100M$](https://egodeath.capital/blog/gjqg3b90h389ufb4y0wnzflv0wfcho)
- [Spiral grant for Payjoins](https://twitter.com/spiralbtc/status/1747663472836431925)
- [Quantum Cats BIP Land](https://www.quantumcats.xyz/bip-land)
- [BIPBounty accepts new BIPs](https://delvingbitcoin.org/t/bipbounty-org-is-open-for-your-bips/441)
- [BitVM Toy Implementation](https://github.com/chainwayxyz/toy-bitvm-rs)
- [BitVM Transaction Graph](https://twitter.com/robin_linus/status/1740012153816715507)
- [Chainways/Citrea: First Bitcoin ZK Rollup](https://chainway.xyz/projects)
- [On consensus changes in bitcoin 2024](https://delvingbitcoin.org/t/on-consensus-changes-in-bitcoin-2024/334)
- [Transaction Stacking for Covenant Fee Minimization](https://rusty.ozlabs.org/2024/01/08/txhash-tx-stacking.html)
- [OP_SEGMENT: Allowing Introspection to Check Partial Scripts](https://rusty.ozlabs.org/2024/01/04/OP_SEGMENT.html)
- [Pay-to-Tapscript: Keyless Entry For Better Future Scripting](https://rusty.ozlabs.org/2024/01/16/pay-to-tapscript.html)
- [Banco: Non-interactive swaps](https://vulpem.medium.com/banco-non-interactive-swaps-00d042791e06)

## Network Data

- [Hashrate Index 2023 Bitcoin Mining Year in Review](https://hashrateindex.com/blog/hashrate-index-2023-bitcoin-mining-year-in-review/)
- [An overview of recent non-standard transactions](https://b10c.me/observations/09-non-standard-transactions/)
- [Tracking electricity consumption from U.S. cryptocurrency mining operations](https://www.eia.gov/todayinenergy/detail.php?id=61364)

## Europe/Germany/Berlin

- [GNU Taler NGI EU project](https://taler.net/en/news/2024-02.html)
- [New(?) Paper Wallet scam](https://archive.ph/VgQ41)
- [German police seize bitcoins worth $2 billion](https://www.dw.com/en/germany-police-seize-bitcoins-worth-2-billion/a-68121384)
- [Bitcoin Position die Linke Berlin](https://dielinke.berlin/zusammenschluesse/lag-netzpolitik/detail/bitcoin-digitaler-euro/)

## Mailing Lists

### bitcoin-dev

- [BIP process frition/binana](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2024-January/022289.html)
- [Bitcoin Inquisition Numbers And Names Authority](https://github.com/bitcoin-inquisition/binana)
- [bitcoin-dev mailing list moves to google groups](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2024-February/022327.html)
- [CheckTemplateVerify Does Not Scale Due to UTXO's Required For Fee Payment](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2024-January/022309.html)

### Delving Bitcoin

- [Disclosure: Btcd consensus bugs due to usage of signed transaction version](https://delvingbitcoin.org/t/disclosure-btcd-consensus-bugs-due-to-usage-of-signed-transaction-version/455)
- [LN-Symmetry Project Recap](https://delvingbitcoin.org/t/ln-symmetry-project-recap/359)
- [DoS disclosure: Channel open race in CLN](https://delvingbitcoin.org/t/dos-disclosure-channel-open-race-in-cln/385)
- [Lightning transactions with v3 and ephemeral anchors](https://delvingbitcoin.org/t/lightning-transactions-with-v3-and-ephemeral-anchors/418)
- [Block-stalling issue in Core prior to v22.0](https://delvingbitcoin.org/t/block-stalling-issue-in-core-prior-to-v22-0/499)
- [Malleability issues when creating shared transactions with segwit v0](https://delvingbitcoin.org/t/malleability-issues-when-creating-shared-transactions-with-segwit-v0/497)
- [LNHANCE bips and implementation](https://delvingbitcoin.org/t/lnhance-bips-and-implementation/376/13)
- [Ephemeral Anchors and MEVil](https://delvingbitcoin.org/t/ephemeral-anchors-and-mevil/383)

## Pull requests

### BIPs, BOLTs and Proposals

- [64bit arithmetic op codes #1538](https://github.com/bitcoin/bips/pull/1538)
- [Add a BIP which resolves human readable names into payment info](https://github.com/bitcoin/bips/pull/1551)

### Bitcoin Core

- [v3 transaction policy for anti-pinning #28948](https://github.com/bitcoin/bitcoin/pull/28948)
- [net: enable v2transport by default #29347](https://github.com/bitcoin/bitcoin/pull/29347)
- [RFC: Deprecate libconsensus #29189](https://github.com/bitcoin/bitcoin/pull/29189)

### LND

- [lnwallet: perform mempool acceptance check before publishing #8345](https://github.com/lightningnetwork/lnd/pull/8345)
- [rpcserver+lncli: add ability to create encrypted debug information package #8188](https://github.com/lightningnetwork/lnd/pull/8188)
- [lnwallet: Introduce a fee buffer. #8096](https://github.com/lightningnetwork/lnd/pull/8096)
- [Bugfix/htlc flush shutdown #8167](https://github.com/lightningnetwork/lnd/pull/8167)
- [watchtower: support taproot channel commitments #7733](https://github.com/lightningnetwork/lnd/pull/7733)

### Eclair

- [Add a funding fee budget #2808](https://github.com/ACINQ/eclair/pull/2808)

### BDK & LDK

- [Complete route blinding support #2812](https://github.com/lightningdevkit/rust-lightning/pull/2812)

### Core Lightning

- [hsmtool: add feature to dump private keys #6985](https://github.com/ElementsProject/lightning/pull/6985)
