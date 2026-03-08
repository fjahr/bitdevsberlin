---
layout: post
title: "Socratic Seminar #77"
---

[Meetup](https://www.meetup.com/bitcoin-lab-berlin/events/312473540/)

Thanks to [Ordimint](https://ordimint.com) for sponsoring food and drinks for this meetup!

## Security/CVEs/InfoSec/Research

- [Nested MuSig2](https://eprint.iacr.org/2026/223)
- [Lattice HD Wallets: Post-Quantum BIP32 Hierarchical Deterministic Wallets from Lattice Assumptions](https://eprint.iacr.org/2026/380.pdf)
- [sqisign](https://sqisign.org/)
- [Binohash: Transaction Introspection Without Softforks](https://robinlinus.com/binohash.pdf)
- [Bitcoin Under Stress: Measuring Infrastructure Resilience 2014-2025](https://arxiv.org/abs/2602.14372)
- [On the Effectiveness of Mempool-based Transaction Auditing](https://arxiv.org/abs/2601.14996)
- [Fix the money, fix the world: bitcoin as techno-libertarian religion](https://academic.oup.com/ser/advance-article/doi/10.1093/ser/mwag009/8494255?login=false)
- [GPU-Accelerated Bitcoin Key Recovery from Weak Entropy Sources](https://b4q.io/research)
- [Unfaithful Claims: Breaking 6 zkVMs](https://osec.io/blog/2026-03-03-zkvms-unfaithful-claims/)

## Network Data

- [Recent OP_RETURN output statistics](https://delvingbitcoin.org/t/recent-op-return-output-statistics/2248)

## Local/Legal

- [FAZ: Milliarden-Steuerprivileg für den Bitcoin](https://www.faz.net/aktuell/finanzen/milliarden-steuerprivileg-fuer-den-bitcoin-accg-110836920.html)
- [South Korea: National Tax Service Coins Stolen Twice After Mnemonic Code Leak](https://www.chosun.com/english/national-en/2026/03/02/RBVQV3E74FGVFEN3IL2RP7KP2I/)
- [Polis closes](https://kryptomagazin.cz/en/paralelni-polis-end-forever-2026)

## Miscellaneous

- [Proposal: Consensus rule to recover 79,956 BTC stolen from MtGox](https://bitcointalk.org/index.php?topic=5575915)
- [Knots Lies](https://knotslies.com/)
- [Knots bug](https://github.com/bitcoinknots/bitcoin/pull/238#issuecomment-3896624715)
- [Bitcoin Core Github Stats](https://dergoegge.github.io/bitcoin-core-github-metadata-stats/)
- [Proof of work: what Bitcoin mining really does](https://bennet.org/learn/proof-of-work-what-bitcoin-mining-really-does/)
- [Hierarchical determinism: how Bitcoin's HD wallets are born](https://bennet.org/learn/hierarchical-determinism-how-bitcoin-hd-wallets-are-born/)
- [Brink Fuzzing Infra Dashboard](https://dergoegge.github.io/fuzzor-dashboard/)
- [Sigbash v2](https://x.com/arbedout/status/2020885338298704253)
- [First BIP54 block](https://x.com/Chris_Stewart_5/status/2026749907684499529)
- [Mastering Taproot](https://github.com/aaron-recompile/mastering-taproot)
- [Programming Lightning](https://github.com/Beige-Coffee/programming-lightning-payment-channels)
- [River Bitcoin Adoption 2026](https://river.com/content/bitcoin-adoption-2026)
- [Mitigating The Impact Of The Quantum Freeze](https://www.bitmex.com/blog/Mitigating-The-Impact-Of-The-Quantum-Freeze)
- [L402Apps](https://www.l402apps.com/)
- [South Korean crypto exchange races to recover $40bn of bitcoin sent to customers by mistake](https://www.theguardian.com/world/2026/feb/10/bithumb-korean-crypto-exchange-sent-bitcoin-mistake)
- [Open-Source Agents Need to Get Serious About Payments](https://x.com/TheBlueMatt/status/2026667191475777727)
- [Alby Bitcoin Payments Agent Skill](https://github.com/getAlby/alby-agent-skill)
- [Lightning Agent Tools](https://github.com/lightninglabs/lightning-agent-tools)


## Mailing Lists

### bitcoin-dev

- [BIP-352: Limiting the number of per-group recipients (K_max)](https://groups.google.com/g/bitcoindev/c/tgcAQVqvzVg)
- [BIP Draft: 24 bits for nVersion nonce space instead of 16](https://groups.google.com/g/bitcoindev/c/fCfbi8hy-AE?pli=1)
- [Algorithm Agility for Bitcoin to maintain security in the face of quantum and classic breaks in the signature algorithms](https://groups.google.com/g/bitcoindev/c/7jkVS1K9WLo)
- [The limitations of cryptographic agility in Bitcoin](https://groups.google.com/g/bitcoindev/c/O6l3GUvyO7A)

### Delving Bitcoin

- [Writing Fuzz Targets for Wallets: Avoiding Known Issues](https://delvingbitcoin.org/t/writing-fuzz-targets-for-wallets-avoiding-known-issues/2316)
- [Introducing UltrafastSecp256k1: A Multi-Architecture Exploration of Secp256k1 Optimizations](https://delvingbitcoin.org/t/introducing-ultrafastsecp256k1-a-multi-architecture-exploration-of-secp256k1-optimizations/2280)
- [The future of the Bitcoin Core GUI](https://delvingbitcoin.org/t/the-future-of-the-bitcoin-core-gui/2253)

## Pull requests

### BIPs, BOLTs and Proposals

- [BIP442: OP_PAIRCOMMIT #1699](https://github.com/bitcoin/bips/pull/1699)
- [BIP128: Timelock-Recovery Storage Format #2068](https://github.com/bitcoin/bips/pull/2068)
- [BIP 360 - Pay to Merkle Root (P2MR) #1670](https://github.com/bitcoin/bips/pull/1670)
- [BIP 89: Chain Code Delegation for Private Collaborative Custody #2004](https://github.com/bitcoin/bips/pull/2004)

### Bitcoin Core

- [Add a "tx output spender" index #24539](https://github.com/bitcoin/bitcoin/pull/24539)
- [build: Embedded ASMap: Build binary dump header file #28792](https://github.com/bitcoin/bitcoin/pull/28792)
- [rpc,net: Add private broadcast RPCs #34329](https://github.com/bitcoin/bitcoin/pull/34329)
- [mining: Break compatibility with existing IPC mining clients #34568](https://github.com/bitcoin/bitcoin/pull/34568)
- [Cluster mempool: SFL cost model (take 2) #34616](https://github.com/bitcoin/bitcoin/pull/34616)

### LND

- [payments: SQL backend implementation series#10604](https://github.com/lightningnetwork/lnd/pull/10604)

### Core Lightning

- [No more legacy onion support #8772](https://github.com/ElementsProject/lightning/pull/8772)
- [Prioritize private channels when relaying payments #3248](https://github.com/ACINQ/eclair/pull/3248)

### Eclair

- [Plugin validation of interactive transactions #3258](https://github.com/ACINQ/eclair/pull/3258)

### BDK/rust-bitcoin & LDK/rust-lightning

- [Support payments for less than the total MPP value #4373](https://github.com/lightningdevkit/rust-lightning/pull/4373)
- [Add spent/created_txouts to SPK and Keychain TxOut indexes #2081](https://github.com/bitcoindevkit/bdk/pull/2081)
- [Prevent HTLC double-forwards, prune forwarded onions #4303](https://github.com/lightningdevkit/rust-lightning/pull/4303)
- [Default to anchors and remove automatic channel acceptance #4354](https://github.com/lightningdevkit/rust-lightning/pull/4354)

### Others

- [HWI: psbt: add MuSig2 fields #784](https://github.com/bitcoin-core/HWI/pull/784)
