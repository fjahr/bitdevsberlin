---
layout: post
title: "Socratic Seminar #18"
---

[Meetup](https://www.meetup.com/Bitcoin-Lab-Berlin/events/hrqccsyccgbrb/)

## Newsletters

- [Optech Newsletter #139](https://bitcoinops.org/en/newsletters/2021/03/10/)
- [Optech Newsletter #140](https://bitcoinops.org/en/newsletters/2021/03/17/)
- [Optech Newsletter #141](https://bitcoinops.org/en/newsletters/2021/03/24/)
- [Optech Newsletter #142](https://bitcoinops.org/en/newsletters/2021/03/31/)
- [Optech Newsletter #143](https://bitcoinops.org/en/newsletters/2021/04/07/)
- [This month in Bitcoin privacy March](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/March_2021/)

## Security/CVEs/InfoSec/Research

- [Why I'm against Taproot](https://freicoin.substack.com/p/why-im-against-taproot)
- [Security and Privacy of Lightning Network Payments with Uncertain Channel Balances](https://arxiv.org/abs/2103.08576v1)
- [Jameson Lopp: A History of Bitcoin Transaction Dust & Spam Storms](https://blog.lopp.net/history-bitcoin-transaction-dust-spam-storms/)
- [An Overview of Lightning Network Implementations](https://medium.com/@fulgur.ventures/an-overview-of-lightning-network-implementations-d670255a6cfa)
- [Akamai: Bitcoins, Blockchains and Botnets](https://blogs.akamai.com/sitr/2021/02/bitcoins-blockchains-and-botnets.html)
- [Analysis and Probing of Parallel Channels in the Lightning Network](https://eprint.iacr.org/2021/384.pdf)
- [A repository of open Bitcoin research problems](https://bitcoin-problems.github.io/)
- [Testing Lightning Node Performance](https://bottlepay.com/blog/bitcoin-lightning-node-performance/)
- [Blockchain.com tx network impact](https://twitter.com/lopp/status/1369284238667882496)
- [Bitcoin Block Time Variance: Theory vs Reality](https://blog.lopp.net/bitcoin-block-time-variance/)

## Miscellaneous

- [Fixing UASF](http://www.erisian.com.au/wordpress/2021/03/14/fixing-uasf)
- [A Theory of Bitcoin Governance](https://ryanthegentry.medium.com/a-theory-of-bitcoin-governance-13510eff42a6)
- [The Blocksize War Book](https://www.amazon.com/dp/B08Z18GWD6)
- [The Square Crypto Book of Bitcoin Mythodology](https://bitcoinmythology.org/)
- [New Trezor hardware Wallet with Tropic Square Open Source Chip In 2022?](https://bitcoin-takeover.com/new-trezor-hardware-wallet-with-tropic-square-open-source-chip-in-2022/)
- [Bitcoin Transcripts](https://btctranscripts.com/)

## Taproot Activation Update

- [AJs PR #21377 using MTP](https://github.com/bitcoin/bitcoin/pull/21377)
- [Andrews PR #21392 using height](https://github.com/bitcoin/bitcoin/pull/21392)
- [March 23rd 2021 Taproot Activation Meeting Notes](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2021-March/018715.html)
- [Rustys NACK discussion](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2021-April/018744.html)
- [Taproot Activation Meeting Notes, April 6th: The CoinFlip](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2021-April/018742.html)
- [Update on "Speedy" Trial: The circus rolls on](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2021-April/018755.html)

## Mailing Lists

### bitcoin-dev

- [Delegated signatures in Bitcoin within existing rules, no fork required](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2021-March/018615.html)
- [Designing Bitcoin Smart Contracts with Sapio (available on Mainnet today)](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2021-April/018759.html)
- [Proposal: Bitcoin Secure Multisig Setup](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2021-April/018732.html)


### lighting-dev

- [Funding Timeout Recovery proposal](https://lists.linuxfoundation.org/pipermail/lightning-dev/2021-March/002982.html)
- [Towards more reliable payment path finding via probabilistic modeling the uncertainty of channel balance](https://lists.linuxfoundation.org/pipermail/lightning-dev/2021-March/002984.html)
- [Lightning Network Protocol Suite Diagram - Request for feedback](https://lists.linuxfoundation.org/pipermail/lightning-dev/2021-April/002990.html)

## Pull requests

### BIPs and Proposals

- [Funding Timeout Recovery proposal #854](https://github.com/lightningnetwork/lightning-rfc/pull/854)

### Bitcoin Core

- [BIP 350: Implement Bech32m and use it for v1+ segwit addresses #20861](https://github.com/bitcoin/bitcoin/pull/20861)
- [Qt: Add Android packaging support #17227](https://github.com/bitcoin/bitcoin/pull/17227)
- [p2p: protect onions in AttemptToEvictConnection(), add eviction protection test coverage #20197](https://github.com/bitcoin/bitcoin/pull/20197)
- [rpc: deprecate addresses and reqSigs from rpc outputs #20286](https://github.com/bitcoin/bitcoin/pull/20286)

### LND

- [lncli: allow PSBT to be read from file #5083](https://github.com/lightningnetwork/lnd/pull/5083)
- [Add lncli command / RPC for manually setting channel state #5033](https://github.com/lightningnetwork/lnd/pull/5033)

### c-lightning

- [c-lightning 0.10.0 released](https://github.com/ElementsProject/lightning/releases/tag/v0.10.0)
- [listpeers: add latest feerate and actual last fee amount. #4407](https://github.com/ElementsProject/lightning/pull/4407)
- [Dual-Funding Flag Day #4427](https://github.com/ElementsProject/lightning/pull/4427)

### Eclair

- [Remove Electrum support #1750](https://github.com/ACINQ/eclair/pull/1750)

### Electrum

- [Electrum 4.1.1 released](https://github.com/spesmilo/electrum/blob/master/RELEASE-NOTES)

HWI

- [HWI 2.0.0 released](https://github.com/bitcoin-core/HWI/releases/tag/2.0.0)

Sekp256k1

- [Safegcd inverses, drop Jacobi symbols, remove libgmp #831](https://github.com/bitcoin-core/secp256k1/pull/831)
