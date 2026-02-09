---
layout: post
title: "Socratic Seminar #76"
---

[Meetup](https://www.meetup.com/bitcoin-lab-berlin/events/nkkbttyjcdbpb/)

Thanks to [Ordimint](https://ordimint.com) for sponsoring food and drinks for this meetup!

## Security/CVEs/InfoSec/Research

- [Argo MAC: Garbling with Elliptic Curve MACs](https://eprint.iacr.org/2026/049)
- [Ideal group](https://ideal.group/)
- [Hardware-Friendly Robust Threshold ECDSA in an Asymmetric Model](https://eprint.iacr.org/2026/094)
- [BABE: Verifying Proofs on Bitcoin Made 1000x Cheaper](https://eprint.iacr.org/2026/065)
- [Curls, caves, and shadows: how cryptocurrencies thrive in (poly)crisis](https://www.tandfonline.com/doi/full/10.1080/13563467.2026.2619676)
- [Dakar: A CoinJoin forensic software](https://www.sciencedirect.com/science/article/pii/S2352711026000178)
- [OptiBridge: A Trustless, Cost-Efficient Bridge Between the Lightning Network and Ethereum](https://eprint.iacr.org/2026/147)
- [CVE-2026-0915: GNU C Library Fixes A Security Issue Present Since 1996](https://www.phoronix.com/news/Glibc-Security-Fix-For-1996-Bug)

## Network Data

- [Ongoing Attack on I2P Network Causing Degraded Performance](https://www.reddit.com/r/i2p/comments/1qvalmq/megathread_ongoing_attack_on_i2p_network_causing/)
- [State of Iran Blackout](https://state-of-iranblackout.whisper.security/)

## Local/Legal

- [Tagesschau: Erfüllt Bitpanda die Vorgaben der Finanzaufsicht?](https://www.tagesschau.de/investigativ/ndr-wdr/bitpanda-bafin-investmentbanking-100.html)
- [How “Bitcoin Jesus” Avoided Prison, Thanks to One of the “Friends of Trump”](https://www.propublica.org/article/bitcoin-jesus-roger-ver-tax-evasion-friends-of-trump)

## Miscellaneous

- [Spirals Flint AI Vibe code comunity](https://flints.dev/)
- [FIBRE Network resurrection](https://x.com/lclhostresearch/status/2014485397569708074?s=20)
- [BTrust BitDevs Playbook](https://blog.btrust.tech/introducing-the-bitdevs-playbook/)
- [OpenSats Year In Review](https://opensats.org/blog/2025-year-in-review)
- [Bitcoin PIPEs v2: Covenants and ZKPs on Bitcoin via Witness Encryption](https://www.allocinit.xyz/uploads/pipesv2.pdf)
- [NXP SE050 Hardware Bitcoin Wallet](https://github.com/0xdeadbeefnetwork/sigil-web)
- [Bitcoin in Epstein emails](https://www.theguardian.com/technology/2026/feb/09/jeffrey-epstein-crypto)
- [Orange Dev Tracker](https://sorukumar.github.io/orange-dev-tracker/)
- [Kompaktor](https://yakihonne.com/article/s/kukks@kukks.org/48a04323883154b2)
- [Windfish](https://github.com/portlandhodl/windfish)
- [SSB Playground](https://github.com/supertestnet/ssb_playground)
- [Magnolia DLC Oracle](https://docs.magnolia.financial/guides/dlc-loans)
- [hArk](https://x.com/2ndbtc/status/2015401100355002626)
- [Taproot Quantum Spend Paths](https://www.bitmex.com/blog/Taproot-Quantum-Spend-Paths)
- [Citrea Mainnet Launch](https://x.com/citrea_xyz/status/2016149582942495044)
- [Janusz L2 Reviews](https://www.janusz.cash/reviews)
- [Amigo](https://spacelab-ccny.github.io/research/amigo/)
- [39C3 - To sign or not to sign: Practical vulnerabilities in GPG & friends](https://www.youtube.com/watch?v=U0ZYOTHrB7I)

## Mailing Lists

### bitcoin-dev

- [Falcon Post-Quantum Signature Scheme Proposal](https://groups.google.com/g/bitcoindev/c/PsClmK4Em1E)

### Delving Bitcoin

- [Incremental mutation testing in the Bitcoin Core](https://delvingbitcoin.org/t/incremental-mutation-testing-in-the-bitcoin-core/2197)
- [A Mathematical Theory of Payment Channel Networks](https://delvingbitcoin.org/t/a-mathematical-theory-of-payment-channel-networks/2204)
- [Hornet UTXO(1): A custom, constant-time, highly parallel UTXO database](https://delvingbitcoin.org/t/hornet-utxo-1-a-custom-constant-time-highly-parallel-utxo-database/2201)
- [SHRINCS: 324-byte stateful post-quantum signatures with static backups](https://delvingbitcoin.org/t/shrincs-324-byte-stateful-post-quantum-signatures-with-static-backups/2158)

## Pull requests

### BIPs, BOLTs and Proposals

- [BIP 434: Peer Feature Negotiation#2076](https://github.com/bitcoin/bips/pull/2076)
- [BIP 433: Add P2A BIP#1982](https://github.com/bitcoin/bips/pull/1982)
- [BIP 110](https://github.com/dathonohm/bips/blob/reduced-data/bip-0110.mediawiki)
- [BIP 110 UASF](https://github.com/dathonohm/bitcoin/releases/tag/v29.2.knots20251110%2Bbip110-v0.1)
- [BIP110 Nodes](https://thebitcoinportal.com/nodes/bip110)

### Bitcoin Core

- [drop my key from trusted-keys#34517](https://github.com/bitcoin/bitcoin/pull/34517)
- [Package Relay Project Tracking](https://github.com/bitcoin/bitcoin/issues/27463)
- [Broadcast own transactions only via short-lived Tor or I2P connections](https://github.com/bitcoin/bitcoin/pull/29415)
- [p2p: Allow block downloads from peers without snapshot block after assumeutxo validation](https://github.com/bitcoin/bitcoin/pull/33604)
- [kernel: Add block header support and validation](https://github.com/bitcoin/bitcoin/pull/33822)

### LND

- [rpcserver: use protocol max for fundMax, not maxChanSize#10488](https://github.com/lightningnetwork/lnd/pull/10488)
- [multi: update close logic to handle re-orgs of depth n-1, where n is num confs - add min conf floor#10331](https://github.com/lightningnetwork/lnd/pull/10331)

### Core Lightning

- [askrene: add auto.include_fees layer#8824](https://github.com/ElementsProject/lightning/pull/8824)

### Eclair

- [Add event for failed payment relay#3244](https://github.com/ACINQ/eclair/pull/3244)

### BDK/rust-bitcoin & LDK/rust-lightning

- [primitives: reject transaction with duplicate inputs#5402](https://github.com/rust-bitcoin/rust-bitcoin/pull/5402)
- [Add median-time-past (MTP) calculation to CheckPoint#2037](https://github.com/bitcoindevkit/bdk/pull/2037)
- [primitives: reject txs with output sum > MAX_MONEY#5443](https://github.com/rust-bitcoin/rust-bitcoin/pull/5443)
- [primitives: reject transactions with 0 outputs#5470](https://github.com/rust-bitcoin/rust-bitcoin/pull/5470)

### Others

- [Silent Payments module: discussion about different scanning approaches (BIP, LabelSet, hybrid) #1799](https://github.com/bitcoin-core/secp256k1/issues/1799)
