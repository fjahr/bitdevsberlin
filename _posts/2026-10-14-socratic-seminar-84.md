---
layout: post
title: "Socratic Seminar #84"
---

[Meetup](https://www.meetup.com/bitcoin-lab-berlin/events/nkkbttyjcnbsb/)

Thanks to [Ordimint](https://ordimint.com) for sponsoring food and drinks for this meetup!

## Security/CVEs/InfoSec/Research

- [Cryptanalysis of LDVR: Polynomial-Time Adaptive Attacks against Threshold Schnorr Signatures](https://eprint.iacr.org/2026/2126)
- [m0wer Gist: Ring change channels](https://gist.github.com/m0wer/ce321e9622b5a3d32c71f56fa2a80ff5)
- [Garbling Groth16 with Native Group Operations](https://eprint.iacr.org/2026/2100)
- [Shielded Bitcoin - Private Transfers on the Bitcoin L1](https://www.allocinit.xyz/uploads/shielded-bitcoin.pdf)
- [PRAWNS: Threshold Hash-Based Signatures from Threshold PRFs](https://eprint.iacr.org/2026/2142)
- [Disclosure: DoS vulnerabilities fixed in Eclair v0.14.0](https://delvingbitcoin.org/t/disclosure-dos-vulnerabilities-fixed-in-eclair-v0-14-0/2914/1)
- [Disclosure: DoS vulnerabilities fixed in Eclair v0.14.1](https://delvingbitcoin.org/t/disclosure-dos-vulnerabilities-fixed-in-eclair-v0-14-1/2928/1)
- [Blink: The September 19 Attack — The Facts, The Full Story and Announcing The 50% Bounty (up to 3.3 bitcoin)](https://www.blink.sv/blog/sept-19-attack-postmortem-and-bounty)
- [Alby vulnerability](https://x.com/getAlby/status/2097574956049498150)
- [Ledger Nano x Spy Implant](https://www.tibane.net/research/ledger-nano-x-implant)

## Network Data

- [Coinjoin Map](https://wabisator.com/map/)

## Local/Legal

- [CDU/CSU against Bitcoin tax?](https://www.blocktrainer.de/blog/laut-bild-informationen-cdu/csu-finanzpolitiker-stellen-sich-gegen-bitcoin-steuer)

## Miscellaneous

- [QED last month: BIP300 fork is always 20 days away](https://ecash.com/)
- [Glasscoins](https://glasscoins.com/)
- [Glasscoins vs. Shielded Bitcoin Whiteboard session](https://x.com/robin_linus/status/2104266654226198827)
- [Bitcoin's Quantum Migration Debate](https://blog.lopp.net/bitcoin-quantum-migration-debate)
- [The Hierarchy of Money](https://gregorygundersen.com/blog/2026/09/20/hierarchy-of-money/)
- [Payjoin in Bark](https://second.tech/blog/payjoin-boards-board-psbt/)
- [covenants.diy](https://covenants.diy/)
- [Something's been bugging me](https://www.dergoegge.de/blog/somethings-been-bugging-me.html)

## Mailing Lists

### bitcoin-dev

- [BIP324 One-Byte Message Type ID Alias Assignment](https://groups.google.com/g/bitcoindev/c/YjrkzS_Sjes)
- [Convention for tagged hash tags in BIPs](https://groups.google.com/g/bitcoindev/c/VQVNZOR3-kg)

### Delving Bitcoin

- [PQLN: Post-Quantum Security for the Bitcoin Lightning Network’s Off-Chain Surfaces ](https://delvingbitcoin.org/t/pqln-post-quantum-security-for-the-bitcoin-lightning-networks-off-chain-surfaces/2893)
- [Block-wide Signature Aggregation via SNARKs](https://delvingbitcoin.org/t/block-wide-signature-aggregation-via-snarks/2875)
- [Bounds on chain length with BIP-54 timewarp fixes](https://delvingbitcoin.org/t/bounds-on-chain-length-with-bip-54-timewarp-fixes/2899)
- [Comparing Bitcoin Covenant Proposals for Vaults](https://delvingbitcoin.org/t/comparing-bitcoin-covenant-proposals-for-vaults/2877)

## Pull requests

### BIPs, BOLTs and Proposals

- [BIP138: Compact Encryption Scheme for Non-seed Wallet Data - #1951](https://github.com/bitcoin/bips/pull/1951)
- [BIP461: Deterministic ECDSA Signatures #2224](https://github.com/bitcoin/bips/pull/2224)
- [BIP332: Stale Tip Relay #2241](https://github.com/bitcoin/bips/pull/2241)

### Bitcoin Core

- [wallet: Prepare for future upgrades by recording versions of last client to open and decrypt #32895](https://github.com/bitcoin/bitcoin/pull/32895)
- [feature: Use different datadirs for different signets #34566](https://github.com/bitcoin/bitcoin/pull/34566)
- [Wallet: Add maxfeerate wallet startup option #29278](https://github.com/bitcoin/bitcoin/pull/29278)
- [Silent Payments: Implement bip352 (take 2) #35301](https://github.com/bitcoin/bitcoin/pull/35301)
- [dergoegge steps down](https://github.com/bitcoin/bitcoin/pull/36335)

### LND

- [bolt12: add Merkle tree and BIP-340 message signatures #11061](https://github.com/lightningnetwork/lnd/pull/11061)
- [multi: stop opening legacy channels #11212](https://github.com/lightningnetwork/lnd/pull/11212)

### Core Lightning

- [Port the v26.06.8 fixes to master #9582](https://github.com/ElementsProject/lightning/pull/9582)
- [feerates: bound peer-supplied and stored values (v26.06.7 security, 1/7) #9507](https://github.com/ElementsProject/lightning/pull/9507)
- [channeld: splice, STFU and channel-open handling (v26.06.7 security, 2/7)](https://github.com/ElementsProject/lightning/pull/9508)
- [lightningd: onchain close, reorg and preimage handling (v26.06.7 security, 3/7) #9509](https://github.com/ElementsProject/lightning/pull/9509)
- [common: bound untrusted inputs and address parsing (v26.06.7 security, 4/7) #9510](https://github.com/ElementsProject/lightning/pull/9510)
- [offers, xpay, hsmd, gossipd: assorted fixes (v26.06.7 security, 7/7) #9513](https://github.com/ElementsProject/lightning/pull/9513)

### Eclair

- [More AI fixes and defense-in-depth #3376](https://github.com/ACINQ/eclair/pull/3376)
- [Harden interactive-tx funding against a malicious bitcoind #3390](https://github.com/ACINQ/eclair/pull/3390)

### BDK/rust-bitcoin & LDK/rust-lightning

- [Reject acknowledged commitment rollbacks #5057](https://git.rust-bitcoin.org/lightningdevkit/rust-lightning/pulls/5057)
- [Fix some bugs the LSPS2 JIT flow #5042](https://git.rust-bitcoin.org/lightningdevkit/rust-lightning/pulls/5042)
- [Drop since-applied blocked monitor updates before the stale-channel check #5046](https://git.rust-bitcoin.org/lightningdevkit/rust-lightning/pulls/5046)

### Others

- [Harden API key storage #7561](https://github.com/btcpayserver/btcpayserver/pull/7561)
