---
layout: post
title: "Socratic Seminar #9"
---

[Meetup](https://www.meetup.com/Bitcoin-Lab-Berlin/events/bqqrrrybckbsb/)

## Optech

- [Newsletter #101](https://bitcoinops.org/en/newsletters/2020/06/10/)
- [Newsletter #102](https://bitcoinops.org/en/newsletters/2020/06/17/)
- [Newsletter #103](https://bitcoinops.org/en/newsletters/2020/06/24/)
- [Newsletter #104](https://bitcoinops.org/en/newsletters/2020/07/01/)
- [Newsletter #105](https://bitcoinops.org/en/newsletters/2020/07/08/)


## Security/CVEs/InfoSec/Research

- [This Month in Bitcoin Privacy](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/June_2020/)
- [An empirical study of availability and reliabilityproperties of the Bitcoin Lightning Network Subtleties and Security](https://blog.bitmex.com/subtleties-and-security/)
- [Bitcoin Covenants: Three Ways to Control the Future](https://arxiv.org/abs/2006.16714)
- [Tim Ruffing on Taproot and Schnorr Multisignatures](https://www.youtube.com/watch?v=8Op0Glp9Eoo)
- [MAD-HTLC: Because HTLC is Crazy-Cheap to Attack](https://ittayeyal.github.io/2020-06-22-mad-htlc/)
  - [Paper](https://arxiv.org/abs/2006.12031)

## Miscellaneous

- [Electrum Server Performance Report](https://blog.keys.casa/electrum-server-performance-report/)
- [BitMEX & OKCoin grant for Amiti Uttarwar](https://blog.bitmex.com/hdr-okcoin-join-forces-to-provide-a-us150000-grant-to-bitcoin-c%c6%92ore-developer-amiti-uttarwar/)
- [Square Crypto grant for Steve Myers/BDK](https://twitter.com/sqcrypto/status/1281269625901256718)
- [Bitcoin Dev Kit](https://bitcoindevkit.org/)
- [Bitcoin Design Slack](https://bitcoindesign.slack.com/) and second community call is set for 2020-07-22, Wed, 1800 CEST
- [Bitcoin grants tracker](https://polylunar.com/bitcoin-grants-tracker/)

## Europe/Germany/Berlin

- [German Bitcoin Week, Frankfurt, 27 Aug - 6 Sep 2020](https://bitcoinweek.de/)

## Mailing Lists

### bitcoin-dev

- Also see Research: [MAD-HTLC](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2020-June/017997.html)
- [BIP 118 and SIGHASH_ANYPREVOUT](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2020-July/018038.html)
- [BIP draft: BIP32 Path Templates](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2020-July/018024.html)
- [CoinPool, exploring generic payment pools for Fun and Privacy](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2020-June/017964.html)
- [IRC discussion on ##taproot-activation](https://lists.linuxfoundation.org/pipermail/bitcoin-daev/2020-July/018042.html)

### lightning-dev

- [Disclosure of a fee blackmail attack that can make a victim loose almost all funds of a non Wumbo channel and potential fixes](https://lists.linuxfoundation.org/pipermail/lightning-dev/2020-June/002735.html)
- [RBF Pinning with Counterparties and Competing Interest](https://lists.linuxfoundation.org/pipermail/lightning-dev/2020-June/002739.html)
- [Pinning : The Good, The Bad, The Ugly](https://lists.linuxfoundation.org/pipermail/lightning-dev/2020-June/002758.html)

## Pull requests

### BIPs

- [BIP118 becomes ANYPREVOUT](https://github.com/bitcoin/bips/pull/943)
- [BIP 339: WTXID-based transaction relay #933](https://github.com/bitcoin/bips/pull/933)

### Proposals/Technical Write-ups

- [Hardware Wallet Support in GUI and RPC, using HWI - Final user experience](https://gist.github.com/Sjors/29d06728c685e6182828c1ce9b74483d)
- [Lightning transactions: from Zero to Hero](https://gist.github.com/t-bast/22320336e0816ca5578fdca4ad824d12)

### Bitcoin Core

- ["PSBT Operations" dialog #18027](https://github.com/bitcoin/bitcoin/pull/18027)
- [sendtoaddress/sendmany: Add explicit feerate option #11413](https://github.com/bitcoin/bitcoin/pull/11413)
- [Reduce inv traffic during IBD #19204](https://github.com/bitcoin/bitcoin/pull/19204)
- [Add gettxoutsetinfo hash_type option #19328](https://github.com/bitcoin/bitcoin/pull/19328)
- [Separate repository for the gui #19071](https://github.com/bitcoin/bitcoin/pull/19071)
- [don't automatically append inputs in walletcreatefundedpsbt #16377](https://github.com/bitcoin/bitcoin/pull/16377)
- [net: Extract download permission from noban #19191](https://github.com/bitcoin/bitcoin/pull/19191)
- [test: change blacklist to blocklist #19227](https://github.com/bitcoin/bitcoin/pull/19227)

### c-lightning

- PSBT
  - [PSBT RPC calls #3775](https://github.com/ElementsProject/lightning/pull/3775)
  - [PSBTs, Meet the HSM #3762](https://github.com/ElementsProject/lightning/pull/3762)
  - [PSBT, continued #3740](https://github.com/ElementsProject/lightning/pull/3740)
- Paymod
  - [paymod: Payments reimagined (part 01) #3753](https://github.com/ElementsProject/lightning/pull/3753)
  - [paymod: Slow but steady progress (part 02) #3760](https://github.com/ElementsProject/lightning/pull/3760)
  - [paymod: Feature parity, finally (part 03) #3773](https://github.com/ElementsProject/lightning/pull/3773)

### LND

- [REST saga 2/3: Add REST endpoints to all RPCs #4251](https://github.com/lightningnetwork/lnd/pull/4251)
- [Intercept forward htlc #4018](https://github.com/lightningnetwork/lnd/pull/4018)
- [multi: add a rpc endpoint to track the recovery process #4106](https://github.com/lightningnetwork/lnd/pull/4106)
- [multi: hold keysend payments #4167](https://github.com/lightningnetwork/lnd/pull/4167)

### Eclair

- [Add a fee provider getting feerates from database #1450](https://github.com/ACINQ/eclair/pull/1450)
- [Postgresql support #1249](https://github.com/ACINQ/eclair/pull/1249)
- [Multipart FSM v2 #1439](https://github.com/ACINQ/eclair/pull/1439)
- [Find multi part route #1427](https://github.com/ACINQ/eclair/pull/1427)
