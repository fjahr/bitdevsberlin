---
layout: post
title: "Socratic Seminar #59"
---

[Meetup](https://www.meetup.com/bitcoin-lab-berlin/events/298337270/)

Thanks to [Ordimint](https://ordimint.com) for sponsoring food and drinks for this meetup!

## Security/CVEs/InfoSec/Research

- [BitVM2: Bridging Bitcoin to Second Layers](https://bitvm.org/bitvm_bridge.pdf)
- [BitVM2 groth16 spec](https://github.com/fiamma-chain/BitVM2-groth16-specification/blob/main/main.pdf)
- [Engineering a backdoored bitcoin wallet](https://www.usenix.org/system/files/woot24-scott.pdf)
- [rust-miniscript vulnerability disclosure (DoS/Stack Overflow) - CVE-2024-44073](https://brunoerg.xyz/2024/08/12/rust-miniscript-vuln.html)
- [Optimizing Big Integer Multiplication on Bitcoin: Introducing w-windowed Approach](https://eprint.iacr.org/2024/1236)
- [Permissionless Verifiable Information Dispersal (Data Availability for Bitcoin Rollups)](https://eprint.iacr.org/2024/1299.pdf)
- [ArtiPACKED: Hacking Giants Through a Race Condition in GitHub Actions Artifacts](https://unit42.paloaltonetworks.com/github-repo-artifacts-leak-tokens/)

## Miscellaneous

- [OpenSats grands for Bitcoin Core](https://opensats.org/blog/caring-for-bitcoin-core)
- [Coinbase announces cbBTC](https://register-cbbtc.app/)
- [EL Tor](https://devpost.com/software/el-tor)
- [OP_CAT arguments bounty - Call for Proposals](https://starkware.co/submission-proposals/)
- [Prevent the CATastrophe](https://gist.github.com/RobinLinus/fdee133af13948b0e617f9ef4f8b8752)

## Network Data
- [Bitrefill Payment statistics](https://x.com/mattahlborg/status/1828436316930912364)

## Europe/Germany/Berlin

- [Bafin Razzia gegen Bitcoinautomaten](https://www.bafin.de/SharedDocs/Veroeffentlichungen/DE/Pressemitteilung/2024/pm_2024_08_20_Krypto_Automaten.html)
- [Kleine Anfrage Bundestag Die Linke](https://dserver.bundestag.de/btd/20/126/2012631.pdf)

## Mailing Lists

### bitcoin-dev

- [Bitcoin Mining Development Mailing List](https://groups.google.com/g/bitcoinminingdev/c/97fkfVmHWYU)

### Delving Bitcoin

- [Zawy’s Alternating Timestamp Attack](https://delvingbitcoin.org/t/zawy-s-alternating-timestamp-attack/1062)
- [Onion Messaging DoS Threat Mitigations](https://delvingbitcoin.org/t/onion-messaging-dos-threat-mitigations/1058)
- [Bolt 12 Trusted Contacts](https://delvingbitcoin.org/t/bolt-12-trusted-contacts/1046)

## Pull requests

### BIPs, BOLTs and Proposals

- [Add a PSBT per-output field for BIP 353 DNSSEC Proofs #1657](https://github.com/bitcoin/bips/pull/1657)
- [GSR preliminary budget](https://primal.net/e/note12283gne4a85aetqmkmafaudk5cmu3769rdavrsus6v05epvdvkgsvxw305)

### Bitcoin Core

- [build: Introduce CMake-based build system #30454](https://github.com/bitcoin/bitcoin/pull/30454)
- [build: Remove Autotools-based build system #30664](https://github.com/bitcoin/bitcoin/pull/30664)
- [blockstorage: XOR blocksdir *.dat files #28052](https://github.com/bitcoin/bitcoin/pull/28052)
- [validation: assumeutxo params mainnet #28553](https://github.com/bitcoin/bitcoin/pull/28553)
- [descriptors: Be able to specify change and receiving in a single descriptor string #22838](https://github.com/bitcoin/bitcoin/pull/22838)

### LND

- [discovery: implement banning for invalid channel anns #9009](https://github.com/lightningnetwork/lnd/pull/9009)

### Eclair

- [Wake up wallet nodes before relaying messages or payments #2865](https://github.com/ACINQ/eclair/pull/2865)
- [Allow selecting coins in sendcoins #8955](https://github.com/lightningnetwork/lnd/pull/8955)

### BDK & LDK

- [wallet: Enable support for single descriptor wallets #1533](https://github.com/bitcoindevkit/bdk/pull/1533)
- [tx-sync: Protect against Core's Merkle leaf node weakness #3215](https://github.com/lightningdevkit/rust-lightning/pull/3215)

### HWI

- [trezor: add Trezor Safe 5 support #742](https://github.com/bitcoin-core/HWI/pull/742)
