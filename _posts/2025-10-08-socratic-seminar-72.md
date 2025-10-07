---
layout: post
title: "Socratic Seminar #72"
---

[Meetup](https://www.meetup.com/bitcoin-lab-berlin/events/dtbxqtyhcnblb/)

Thanks to [Ordimint](https://ordimint.com) for sponsoring food and drinks for this meetup!

## Security/CVEs/InfoSec/Research

- [WISCH: Efficient data signing via correlated signatures](https://eprint.iacr.org/2025/1650)
- [An empirical evaluation of fuzz targets using mutation testing](https://sol.sbc.org.br/index.php/sast/article/view/36885)
- [Bitcoin reimagined: A comprehensive study of ordinals and inscriptions protocols for Web3 asset innovation](https://www.sciencedirect.com/science/article/pii/S209672092500106X)
- [BitPriv: A Privacy-Preserving Protocol for DeFi Applications on Bitcoin](https://eprint.iacr.org/2025/1575)
- [Bitcoin Worlds](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5445935)
- [Eclair: Preimage Extraction Exploit](https://morehouse.github.io/lightning/eclair-preimage-extraction-exploit/)
- [Optimal Threshold Signatures in Bitcoin](https://arxiv.org/abs/2509.25408)
- [Hornet Node and the Hornet DSL](https://hornetnode.org/paper.html)
- [Comparative Analysis of Bitcoin Regulation in Latin American Countries](https://revfinypolecon.ucatolica.edu.co/index.php/RFYPE/article/view/6272)
- [Quantitative Analysis of Centralization in the Bitcoin Lightning Network Through Centrality Metrics](https://ieeexplore.ieee.org/abstract/document/11177488)

## Network Data

- [Stratum.work new analysis panel](https://stratum.work/)
- [Ordinals – Impact On Node Runners](https://blog.bitmex.com/ordinals-impact-on-node-runners/)

## Europe/Germany/Berlin

- [3. BitcoinForum Volksbank Raiffeisenbank Bayern Mitte eG with BitDevs](https://bitcoinforum.bayern/)

## Miscellaneous

- [It's Knot a Serious Project](https://blog.lopp.net/knot-a-serious-project/)
- [All For One & One For All](https://blog.bitmex.com/all-for-one-one-for-all/)
- [A Knotty Irony](https://insider.btcpp.dev/p/a-knotty-irony)
- [LEAKED: Luke Dashjr Plans Hardfork To “Save Bitcoin”](https://www.therage.co/leaked-luke-dashjr-bitcoin-hardfork/)
- [OpenTimestamps and Knots/OCEAN](https://petertodd.org/2025/opentimestamps-and-knots-ocean)
- [Why Bitcoiners should support covenant soft forks](https://lightco.in/2025/09/12/covenants/)
- [time2build Breetz virtual Hackathon](https://docs.google.com/presentation/d/1D_6b0Ho7yMbuIbGiWXlYlwv0xbsVPBdCl625m0NlVkM/edit?slide=id.p#slide=id.p)
- [PayPal to support Ethereum and Bitcoin](https://newsroom.paypal-corp.com/2025-09-15-PayPal-Ushers-in-a-New-Era-of-Peer-to-Peer-Payments,-Reimagining-How-Money-Moves-to-Anyone,-Anywhere)
- [Localhost Transparency report](https://lclhost.org/blog/transparency-report-002/)
- [ElectrumZ: Minimalistic Electrum server implementation](https://github.com/Overtorment/ElectrumZ)
- [Frigate Electrum Server](https://github.com/sparrowwallet/frigate)
- [OpenSats: Fourteenth Wave of Bitcoin Grants](https://opensats.org/blog/fourteenth-wave-of-bitcoin-grants)
- [Advancements in Ecash](https://opensats.org/blog/advancements-in-ecash)
- [State of Rootstock Q2 2025](https://messari.io/report/state-of-rootstock-q2-2025)
- [Ark and Spark are Channel Factories](https://bitcoinmagazine.com/print/ark-and-spark-the-channel-factories-print)
- [My review of the proposed C header for the Bitcoin Core Kernel API](https://habla.news/a/naddr1qvzqqqr4gupzqrcxrljwdpfz2qn5a57hse6ez6pkd34pe0wpeskmktt2p62yeketqqvxy6t5vdhkjmntv4exuetv94shq6fdwfjhv6t9wuxrjull)

## Mailing Lists

### bitcoin-dev

- [A Bitcoin Scripting Proposal BIP Quartet](https://gnusha.org/pi/bitcoindev/877bxknwk6.fsf@rustcorp.com.au/)

### Delving Bitcoin

- [Provable Cryptography for Bitcoin: An Introduction (Workbook)](https://delvingbitcoin.org/t/provable-cryptography-for-bitcoin-an-introduction-workbook/1974)
- [MultiChannel and MultiPTLC: Towards A Global High-Availability Consistent/Partition-Tolerant Database For Bitcoin Payments](https://delvingbitcoin.org/t/multichannel-and-multiptlc-towards-a-global-high-availability-consistent-partition-tolerant-database-for-bitcoin-payments/1983)
- [Measuring minrelaytxfee across the Bitcoin network](https://delvingbitcoin.org/t/measuring-minrelaytxfee-across-the-bitcoin-network/1989)

## Pull requests

### Bitcoin Core
- [v30 Release Testing Guide](https://github.com/bitcoin-core/bitcoin-devwiki/wiki/30.0-Release-Candidate-Testing-Guide)
- [docs: Undeprecate datacarrier and datacarriersize configuration options #33453](https://github.com/bitcoin/bitcoin/pull/33453)
- [Experimental branch with p2p as separate binary](https://github.com/theuni/bitcoin/tree/multiprocess_p2p)
- [rpc: fix getblock(header) returns target for tip #33446](https://github.com/bitcoin/bitcoin/pull/33446)
- [p2p: Increase tx relay rate #28592](https://github.com/bitcoin/bitcoin/pull/28592)
- [wallet: Identify transactions spending 0-value outputs, and add tests for anchor outputs in a wallet #33268](https://github.com/bitcoin/bitcoin/pull/33268)

### LND

- [Add XFindBaseLocalChanAlias RPC #10133](https://github.com/lightningnetwork/lnd/pull/10133)
- [Add Support for P2TR Fallback Addresses in BOLT-11 #9975](https://github.com/lightningnetwork/lnd/pull/9975)

### Eclair

- [Use balance estimates from past payments in path-finding #2308](https://github.com/ACINQ/eclair/pull/2308)
- [Remove PaymentWeightRatios from the routing config #3171](https://github.com/ACINQ/eclair/pull/3171)
- [Allow overriding max-closing-feerate with forceclose API #3142](https://github.com/ACINQ/eclair/pull/3142)

### BDK/rust-bitcoin & LDK/rust-lightning

- [Support client_trusts_lsp on LSPS2 #3838](https://github.com/lightningdevkit/rust-lightning/pull/3838)
- [CanonicalView #2029](https://github.com/bitcoindevkit/bdk/pull/2029)
- [Async send: sender-side #4046](https://github.com/lightningdevkit/rust-lightning/pull/4046)
- [Async send always-online counterparty side #4045](https://github.com/lightningdevkit/rust-lightning/pull/4045)
- [Always-online node forward invoice request #4049](https://github.com/lightningdevkit/rust-lightning/pull/4049)

### Others

- [Sparrow v2.3 with Silent Payments](https://github.com/sparrowwallet/sparrow/releases/tag/2.3.0)
