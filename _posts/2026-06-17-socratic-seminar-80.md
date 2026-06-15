---
layout: post
title: "Socratic Seminar #80"
---

[Meetup](https://www.meetup.com/bitcoin-lab-berlin/events/312473544/)

Thanks to [Ordimint](https://ordimint.com) for sponsoring food and drinks for this meetup!

## Security/CVEs/InfoSec/Research

- [Ark: Offchain Transaction Batching in Bitcoin](https://arxiv.org/abs/2605.20952)
- [Security Analysis of Bitcoin’s V2 Transport Protocol: Exploiting Design Implications for Sustained Eclipse and Downgrade Attacks](https://arxiv.org/abs/2605.19715)
- [Predicting Channel Closures in the Lightning Network with Machine Learning](https://arxiv.org/abs/2605.12759)
- [Probabilistic Atomic Swaps for Bitcoin and Friends](https://arxiv.org/abs/2605.04975)
- [Trezor response: TROPIC01 chip disclosure](https://trezor.io/de/blog/news/Trezor-response-TROPIC01-chip-disclosure-no-impact-to-your-funds)
- [Bitcoin Core CVE-2024-52911 - Script Interpreter Remote Crash](https://bitcoincore.org/en/2026/05/05/disclose-cve-2024-52911/)
- [Private Broadcast May Reveal Sender IP Address in Bitcoin Core 31.0](https://bitcoincore.org/en/2026/06/06/privatebroadcast-ip-leak/)
- [Zcash: The Orchard Counterfeiting Vulnerability](https://x.com/zooko/status/2062644925590900980)
- [We found a stable Firefox identifier linking all your private Tor identities](https://fingerprint.com/blog/firefox-tor-indexeddb-privacy-vulnerability/)

## Network Data

- [OP_RETURN Data Status](https://x.com/murchandamus/status/2055028624772993530)
- [What data to collect and monitor during the BIP-110 & BIP-300 forks in August 2026?](https://bnoc.xyz/t/brainstorming-what-data-to-collect-and-monitor-during-the-bip-110-bip-300-forks-in-august-2026/139)

## Local/Legal

- [Fremde Bitcoin per Gerichtsurteil? Kläger wollen Eigentum an fast 40.000 Wallets](https://www.blocktrainer.de/blog/fremde-bitcoin-per-gerichtsurteil-klaeger-wollen-eigentum-an-fast-40000-wallets)
- [Bitcoin Bundesverband: Pro Haltefrist](https://prohaltefrist.de/)

## Miscellaneous

- [Tor Internetfreedom donation](https://internetfreedom.torproject.org/)
- [Quantum Attack Game Theory](https://blog.lopp.net/quantum-attack-game-theory/)
- [Conduition funded by Brink](https://conduition.io/bitcoin/my-first-grant/)
- [CoreDev Transcripts](https://btctranscripts.com/bitcoin-core-dev-tech/2026-05)
- [2140 annual report](https://cdn.sanity.io/files/lv9xnb3x/production/185de4c02420c73921c6ae44c04fab8301f8aeeb.pdf)
- [HRF: Bitcoin for Non-Profits](https://hrf.org/wp-content/uploads/2026/05/BFN-Guide-Hyperlinked.pdf)
- [Localhost Mining Unit](https://lclhost.org/blog/mining-unit/)
- [Burak: Introducing Cube](https://medium.com/cube-bitcoin/introducing-cube-8b3702e470a5)
- [Fuzz Testing Research Interns: Dongjia Zhang and Stratos](https://brink.dev/blog/2026/05/29/fuzz-testing-research-interns/)
- [BOSS Challenge Protfolio Projects](https://bosschallenge.xyz/portfolioprojects)
- [Bark Mainnet Launch](https://blog.second.tech/bark-now-on-bitcoin-mainnet/)
- [Secure Fountain Codes](https://x.com/roasbeef/status/1973914845247594840)
- [Roulette in a Bitcoin Payment Channel](https://gist.github.com/RobinLinus/01d4f40a1d0785fd2d16f7e84f20332d)
- [Toughts on Gaming on Bitcoin](https://x.com/bramcohen/status/2063316914282410251)

## Mailing Lists

### bitcoin-dev

- [BIP Draft: Testnet 5](https://groups.google.com/g/bitcoindev/c/kGUMTxOvdJA/m/Eyx5FxQeAAAJ)
- [A Post-Quantum Path for BIP 324](https://groups.google.com/g/bitcoindev/c/n_5WuKVYqwI/m/lBooLis3AQAJ)
- [BIP Draft: P2P UTXO Set Sharing](https://groups.google.com/g/bitcoindev/c/rThmyI8ZN3Q)
- [64-Byte Transactions and Potential Legitimate Uses](https://groups.google.com/g/bitcoindev/c/iCuq6bFKt5Y/m/MCATyQ4zAAAJ)
- [Prohibit Merkle Internal Node Preimages That Encode Minimal 64-Byte Transactions](https://groups.google.com/g/bitcoindev/c/ZVDEzxG6Sq8)

### Delving Bitcoin

- [TCP hole punching for Bitcoin nodes behind home NATs?](https://delvingbitcoin.org/t/tcp-hole-punching-for-bitcoin-nodes-behind-home-nats/2497)
- [Vulnerability Disclosure: Assertion DoS in Core Lightning](https://delvingbitcoin.org/t/vulnerability-disclosure-assertion-dos-in-core-lightning/2507)

## Pull requests

### Bitcoin Core

- [net: use the proxy if overriden when doing v2->v1 reconnections #35410](https://github.com/bitcoin/bitcoin/pull/35410)
- [BIP 323: reserve version bits 5-28 as extra nonce space #34779](https://github.com/bitcoin/bitcoin/pull/34779)
- [coinselection: Optimize BnB exploration #32150](https://github.com/bitcoin/bitcoin/pull/32150)
- [mining: add submitBlock to IPC Mining interface #34644](https://github.com/bitcoin/bitcoin/pull/34644)

### LND

- [funding: require explicit taproot channel negotiation #10820](https://github.com/lightningnetwork/lnd/pull/10820)

### Core Lightning

- [Payer proofs #9116](https://github.com/ElementsProject/lightning/pull/9116)
- [neutrino: add fast initial sync via header import #10552](https://github.com/lightningnetwork/lnd/pull/10552)

### Eclair

- [Add support for zero-fee commitment format #3192](https://github.com/ACINQ/eclair/pull/3192)

### Others

- [Ensure the seed isn't leaking to user with can sign permission #7354](https://github.com/btcpayserver/btcpayserver/pull/7354)
- [feat: Add multisig wallet setup #7218](https://github.com/btcpayserver/btcpayserver/pull/7218)
