---
layout: post
title: "Socratic Seminar #23"
---

[Meetup](https://www.meetup.com/Bitcoin-Lab-Berlin/events/nzphhsyccmbsb/)

## Security/CVEs/InfoSec/Research

- [Userspace, Statically Defined Tracing support for Bitcoin Core](https://b10c.me/blog/008-bitcoin-core-usdt-support/)
- [CheckSequenceVerify DISCOURAGE_UPGRADABLE_NOPS Defect](https://rubin.io/bitcoin/2021/09/03/upgradable-nops-flaw/)
- [eltoo with Anyprevout and Taproot](https://yakshaver.org/2021/07/26/first.html)
- [bitcoinbinary.org - reproducable builds](https://bitcoinbinary.org/)
  - [achow thread](https://mobile.twitter.com/achow101/status/1433834858015506434)
- [CISA writeup by n1ckler](https://github.com/ElementsProject/cross-input-aggregation#integration-into-the-bitcoin-protocol)

## Miscellaneous

- [Proof of Reserves & Liabilities – BitMEX Demonstration](https://blog.bitmex.com/proof-of-reserves-liabilities-bitmex-demonstration/)
- [2014 MIT Bitcoin Airdrop 7 years later](https://www.cnbc.com/2021/08/14/mit-student-gave-away-100-worth-of-bitcoin-to-all-undergrads-in-2014.html)
- [bip174.org - Bitcoin PSBT Explorer](https://bip174.org/)
- [Donnerlab changes course to lightning infrastructure](https://twitter.com/donnerlab1/status/1437020324097310720)
- [Bitcoin Smiles](https://bitcoinsmiles.org/)
- [Bitcoin Academy for Activists](https://oslofreedomforum.com/bitcoin-academy-off2021/)
- [SeedSigner](https://seedsigner.com/)
- [Blockstream raises $210M Series B](https://blockstream.com/2021/08/24/en-blockstream-secures-210m-series-b-financing/)
- [Stale Block at height #697,008](https://twitter.com/BitMEXResearch/status/1429405958850203660)
- [Lightning’s Missing Piece: A Decentralized Liquidity Market](https://medium.com/blockstream/lightnings-missing-piece-a-decentralized-liquidity-market-a0bb47534a4f)
- [More UTXO set consolidation happening at low fee rates](https://mobile.twitter.com/murchandamus/status/1428063744295309319)
- [Segwit usage crossing 80%](https://twitter.com/OneMorePeter/status/1437551267296038913)
  * [BitGo defaults to Native Segwit for Change Outputs](https://twitter.com/BitGo/status/1431296700442841089)
- [Taproot Node Support 52.58%](https://mobile.twitter.com/taproot_signal/status/1432221547574571009)
- [New Square Crypto grant: JohnCantrell97](https://twitter.com/sqcrypto/status/1432371044174778373)
- [New BitMEX grant: Sjors Provoost](https://twitter.com/BitMEXResearch/status/1423199968387608585)
- [Alex Bosworth has routed 200 BTC YTD](https://twitter.com/alexbosworth/status/1433988909600411649)
- [First Summer of Bitcoin with 51 students concludes](https://twitter.com/summerofbitcoin/status/1436371656570654720)

## Berlin/Germany/Europe

- [Kleine Anfrage der FDP an Bundestag: Besteuerung von virtuellen Währungen und Token](https://dserver.bundestag.de/btd/19/321/1932192.pdf)

## Mailing Lists

### bitcoin-dev

- [Removing the Dust Limit](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2021-August/019307.html)
- [Reorgs on SigNet - Looking for feedback on approach and parameters](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2021-September/019413.html)
- [TAPLEAF_UPDATE_VERIFY covenant opcode](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2021-September/019419.html)
- [Braidpool: Proposal for a decentralised mining pool](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2021-August/019371.html)
- [Proposal for a few IANA mime-types related to Bitcoin](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2021-August/019385.html)

### lighting-dev

- [#zerobasefee](https://lists.linuxfoundation.org/pipermail/lightning-dev/2021-August/003174.html)
- [Do we really want users to solve an NP-hard problem when they wish to find a cheap way of paying each other on the Lightning Network?](https://lists.linuxfoundation.org/pipermail/lightning-dev/2021-August/003203.html)
- [Fee Budgets: A Possible Path Towards Unified Cost Functions For Lightning Pathfinding Problems](https://lists.linuxfoundation.org/pipermail/lightning-dev/2021-August/003191.html)

## Pull requests

### BIPs, BOLTs and Proposals

- [https://bolt12.org/](Bolt12 Offers: Lightning's Native Experience, Everywhere)
- [Update closing_signed fee requirement #847](https://github.com/lightningnetwork/lightning-rfc/pull/847)
- [feature: define option_zero_htlc_tx_fee (feature 22/23) #824](https://github.com/lightningnetwork/lightning-rfc/pull/824)
- [Clean up existing and add range-based closing_signed negotiation #1011](https://github.com/rust-bitcoin/rust-lightning/pull/1011)

### Bitcoin Core

- [Bitcoin Core 22.0 released](https://bitcoincore.org/en/releases/22.0/)
  * [Bitcoin Explained - Bitcoin 22.0 explained - 32min](http://nadobtc.btc.libsynpro.com/bitcoin-core-220-explained-episode-45)
  * [Testing Bitcoin Core 22.0 Release Candidates](https://bitcoincore.reviews/v22-rc-testing)
  * [Bitcoin Core 22.0rc Testing Guide](https://github.com/bitcoin-core/bitcoin-devwiki/wiki/22.0-Release-Candidate-Testing-Guide)
- [wallet: Decide which coin selection solution to use based on waste metric #22009](https://github.com/bitcoin/bitcoin/pull/22009)
- [Add a new RPC command: restorewallet #22541](https://github.com/bitcoin/bitcoin/pull/22541)
- [wallet, rpc: add an option to list private descriptors #21500](https://github.com/bitcoin/bitcoin/pull/21500)
- [mempool/validation: mempool ancestor/descendant limits for packages #21800](https://github.com/bitcoin/bitcoin/pull/21800)

### LND

- [peer: always send latest block header as part of ping messages #5621](https://github.com/lightningnetwork/lnd/pull/5621)

### c-lightning

- [Datastore #4674](https://github.com/ElementsProject/lightning/pull/4674)

### Eclair

- [Tor support for blockchain watchdogs #1907](https://github.com/ACINQ/eclair/pull/1907)
- [Add Tor hybrid connectivity mode #5410](https://github.com/lightningnetwork/lnd/pull/5410)

### Rust Lightning

- [Add new config setting max_balance_dust_htlc_msat #1009](https://github.com/rust-bitcoin/rust-lightning/pull/1009)

## Newsletters

- [Bitcoin Optech #161](https://bitcoinops.org/en/newsletters/2021/08/11/)
- [Bitcoin Optech #162](https://bitcoinops.org/en/newsletters/2021/08/18/)
- [Bitcoin Optech #163](https://bitcoinops.org/en/newsletters/2021/08/25/)
- [Bitcoin Optech #164](https://bitcoinops.org/en/newsletters/2021/09/01/)
- [Bitcoin Optech #165](https://bitcoinops.org/en/newsletters/2021/09/08/)
- [This Month In Bitcoin Privacy - August 2021](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/August_2021/)
