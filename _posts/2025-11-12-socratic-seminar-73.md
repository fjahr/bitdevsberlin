---
layout: post
title: "Socratic Seminar #73"
---

[Meetup](https://www.meetup.com/bitcoin-lab-berlin/events/311409292/)

Thanks to [Ordimint](https://ordimint.com) for sponsoring food and drinks for this meetup!

## Security/CVEs/InfoSec/Research

- [Beholder Signatures](https://eprint.iacr.org/2025/1900)
- [BATTLE for Bitcoin: Capital-Efficient Optimistic Bridges with Large Committees](https://arxiv.org/abs/2510.06468)
- [Assessing the Impact of Post-Quantum Digital Signature Algorithms on Blockchains](https://arxiv.org/abs/2510.09271)
- [Hard forks, hard questions: Unraveling the microstructure effects on Bitcoin’s return, volume, and volatility](https://www.sciencedirect.com/science/article/pii/S0165176525005099)
- [Analysis of Input-Output Mappings in Coinjoin Transactions with Arbitrary Values](https://arxiv.org/abs/2510.17284)
- [Cross-chain Lightning Trades: Getting the Advantages of a Custodial Exchange while Keeping Your Assets](https://eprint.iacr.org/2025/1746)
- [B-SSL: Bitocin Secure Signing Layer](https://github.com/ilghan/bssl-whitepaper)
- [Is Your Bluetooth Chip Leaking Secrets via RF Signals?](https://eprint.iacr.org/2025/559)
- [Bitcoin Research day](https://brd.chaincode.com/)
- [OTS-PC: OTS-based Payment Channels for the Lightning Network](https://arxiv.org/abs/2511.04021)
- [TEE.fail](https://tee.fail/)

## Network Data

- [Bitnod.es](https://www.bitnod.es/)
- [Gossip Observer](https://github.com/jharveyb/gossip_observer)

## Europe/Germany/Berlin

- [Gesetz zur Umsetzung der Richtlinie (EU) 2023/2226](https://www.bundestag.de/dokumente/textarchiv/2025/kw45-de-kryptowerte-1118558)
- [Berlin Freedom Week](https://berlin-freedom-week.com/en/program)
- [SPD Seeheimer Kreis wants to abolish 1-year tax free regulation](https://www.seeheimer-kreis.de/fileadmin/data/20251027_Seeheimer_Strategiepapier_Finanzen.pdf)
- [AFD-Antrag im Bundestag: Strategisches Potenzial von Bitcoin erkennen](https://dserver.bundestag.de/btd/21/023/2102301.pdf)

## Miscellaneous

- [New Trezor Safe 7 with TROPIC01, Bluetooth, bigger screen, battery](https://trezor.io/trezor-safe-7)
- [TROPIC01 repository](https://github.com/tropicsquare/tropic01)
- [Tether donates USD250k to OpenSats for operations](https://tether.io/news/tether-donates-250000-to-opensats-to-strengthen-free-and-open-source-ecosystems-supporting-bitcoin-and-freedom-tech/)
- [Bitcoin for Signal initiative](https://bitcoinforsignal.org/)
- [Lightspark Grid API](https://www.lightspark.com/grid)
- [Tether WDK](https://tether.io/news/tether-champions-global-financial-freedom-infrastructure-with-open-source-release-of-its-wallet-development-kit-wdk/)
- [$15 billion seized by US originates from Iran/China bitcoin miner "theft"](https://www.elliptic.co/blog/15-billion-us-seizure-reveals-prince-groups-connection-to-iran-china-bitcoin-mining-theft)
- [HRF grant](https://bitcoinmagazine.com/builders/human-rights-foundation-1b-satoshis)
- [LNHANCE Website](https://lnhance.org/)
- [CoreDev Transcripts October 2025](https://btctranscripts.com/bitcoin-core-dev-tech/2025-10)
- [NUT NOVEMBER A month-long hackathon for Cashu builders](https://nutnovember.org/)
- [Lawyers call Bitcoin Core v30 CSAM concerns ‘overblown’](https://protos.com/exclusive-lawyers-call-bitcoin-core-v30-csam-concerns-overblown/)
- [Arké MacOS prototype](https://community.second.tech/t/arke-macos-prototype/156)
- [Arkade.money](https://arkade.money/)
- [The State of Bitcoin Mining in Russia](https://www.hashlabs.io/blog/the-state-of-bitcoin-mining-in-russia)
- [papa-swap](https://github.com/supertestnet/papa-swap)
- [https://www.therage.co/keonne-rodriguez-samourai-sentenced/](Samourai Wallet sentence)

## Mailing Lists

### bitcoin-dev

- [Public disclosure of 4 Bitcoin Core security advisories](https://groups.google.com/g/bitcoindev/c/sBpCgS_yGws)
- [OP_CIV - Post-Quantum Signature Aggregation](https://gnusha.org/pi/bitcoindev/05195086-ee52-472c-962d-0df2e0b9dca2n@googlegroups.com/)

### Delving Bitcoin

- [Comparing the performance of ECDSA signature validation in OpenSSL vs. libsecp256k1 over the last decade](https://delvingbitcoin.org/t/comparing-the-performance-of-ecdsa-signature-validation-in-openssl-vs-libsecp256k1-over-the-last-decade/2087)
- [OP_STARK_VERIFY - Native STARK Proof Verification in Bitcoin Script](https://delvingbitcoin.org/t/proposal-op-stark-verify-native-stark-proof-verification-in-bitcoin-script/2056)
- [Determining BlockTemplate Fee Increase Using Fee Rate Diagram](https://delvingbitcoin.org/t/determining-blocktemplate-fee-increase-using-fee-rate-diagram/2052)

## Pull requests

### BIPs, BOLTs and Proposals

- [BIP-444: Reduced Data Temporary Softfork](https://github.com/bitcoin/bips/pull/2017)
- [BIP-444 Airdrop](https://github.com/mikekelly/BIP444-Airdrop)
- [BIP???: Chain Code Delegation for Private Collaborative Custody](https://github.com/bitcoin/bips/pull/2004)

### Bitcoin Core

- [wallet: Be able to receive and spend inputs involving MuSig2 aggregate keys #29675](https://github.com/bitcoin/bitcoin/pull/29675)
- [kernel: Introduce C header API #30595](https://github.com/bitcoin/bitcoin/issues/30595)
- [cluster mempool: control/optimize TxGraph memory usage #33157](https://github.com/bitcoin/bitcoin/pull/33157)
- [Fix tiebreak when loading blocks from disk (and add tests for comparing chain ties) #29640](https://github.com/bitcoin/bitcoin/pull/29640)

### LND

- [Basic structures for onion messages into LND #9868](https://github.com/lightningnetwork/lnd/pull/9868)

### Core Lightning

- [BOLT12 recurrence spec update #8398](https://github.com/ElementsProject/lightning/pull/8398)
- [Giant tx fix #8639](https://github.com/ElementsProject/lightning/pull/8639)
- [Fix injectpayonion/sendonion crash on malformed onion reply from direct peer. #8597](https://github.com/ElementsProject/lightning/pull/8597)

### Eclair/Phoenix

- [New Phoenix with Taproot](https://x.com/PhoenixWallet/status/1983524047712391445)
- [Remove support for non-anchor channels #3173](https://github.com/ACINQ/eclair/pull/3173)
- [Fix race in PeerManager read pausing. #4168](https://github.com/lightningdevkit/rust-lightning/pull/4168)

### BDK/rust-bitcoin & LDK/rust-lightning

- [bitcoin: refuse to compute block and witness merkle roots which would be ambiguous #5116](https://github.com/rust-bitcoin/rust-bitcoin/pull/5116)

### Others

- [BTCPayServer: Subscription #6922](https://github.com/btcpayserver/btcpayserver/pull/6922)
- [Sep256k1: Introduce (mini) unit test framework #1734](https://github.com/bitcoin-core/secp256k1/pull/1734)
