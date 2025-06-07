---
layout: post
title: "Socratic Seminar #68"
---

[Meetup](https://www.meetup.com/bitcoin-lab-berlin/events/307914318/)

Thanks to [Ordimint](https://ordimint.com) for sponsoring food and drinks for this meetup!

## Presentation: StratumV2 and DMND (General Kenobi, DMND/SV2)

- [StratumV2 protocol](https://stratumprotocol.org/features/) 
- [Demand Pool](https://www.dmnd.work/)
- [Understanding SLICE (PPLNS+JD)](https://blog.dmnd.work/understanding-slice-pplns-jd/)
- [PPLNS with Job Declaration](https://www.dmnd.work/pplns-with-job-declaration/pplns-with-job-declaration.pdf)
- [SLICE: Making PPLNS Work for Demand Response](https://blog.dmnd.work/slice-making-pplns-work-for-demand-response/)


## Security/CVEs/InfoSec/Research

- [Coinbase Security incient SEC filling](https://www.sec.gov/ix?doc=/Archives/edgar/data/1679788/000167978825000094/coin-20250514.htm)
- [Mempool Space Research: UTXO set report](https://research.mempool.space/utxo-set-report/)
- [Bitmex research: The 2025 spam attacks](https://blog.bitmex.com/the-2015-spam-attacks/)
- [River: The American Bitcoin Advantage](https://river.com/learn/files/river-america-report-2025.pdf)
- [MnemonicMaker: A Serious Game for Reconstructing Bitcoin Wallet Mnemonic Phrases](https://journal.seriousgamessociety.org/index.php/IJSG/article/view/911)
- [Cryptology with Bitcoin and Blockchain Applications](https://rdw.rowan.edu/textbooks/1/)
- [Block Number-Based Address Clustering for Bitcoin Taproot Upgrade](https://ieeexplore.ieee.org/abstract/document/11005452)
- [Fully-Threshold Hierarchical Deterministic Wallets in Bitcoin](https://ucalgary.scholaris.ca/items/b53e23cb-b507-44eb-854d-5b2809417587)
- [Bitcoin and Quantum Computing: Current Status and Future Directions](https://chaincode.com/bitcoin-post-quantum.pdf)
- [Warum Bitcoin nicht umweltfreundlicher wird](https://archive.ph/2025.05.26-083023/https://www.spektrum.de/news/bitcoin-und-proof-of-work-zwischen-sicherheit-und-stromverbrauch/2267443#selection-1679.515-1679.632)
- [KeyJoin: Privacy-Focused CoinJoin Protocol for Bitcoin](https://eprint.iacr.org/2025/838)
- [The Hop-Return Protocol: Introducing Non-Standard Tokens (NST)](https://gist.github.com/mononaut/3d08be8a5c00a5e6c9a5641daf6b1338)
- [TOOP: A transfer of ownership protocol over Bitcoin](https://eprint.iacr.org/2025/964)
- [Round-Efficient Adaptively Secure Threshold Signatures with Rewinding](https://eprint.iacr.org/2025/638.pdf)
- [Enforcing arbitrary constraints on Bitcoin transactions](https://eprint.iacr.org/2025/912.pdf)

## Network Data

- [c= routing node is earning 9.7% APR](https://x.com/RyanTheGentry/status/1927795177759928763)
- [Non-Standard Bitcoin Transaction Dataset](https://bitcoin-data.github.io/non-standard-transactions/)
- [Removal of minimum relay fee](https://x.com/mononautical/status/1919090261654638954)

## Europe/Germany/Berlin

- [Volksbanken enable BTC buy/sell for their 30 million clients](https://archive.is/2oKuH)

## Miscellaneous

- [Bounty for Bitcoin Brainrot wallet for GenZ](https://skibidi.cash/)
- [Maelstrom funding for benalleng/Payjoin](https://x.com/MaelstromFund/status/1927158251147182338)
- [ArkadeOS](https://arkadeos.com/)
- [Quantum Bitcoin Summit](https://pbquantum.com/)
- [Bitcoin Payments on Square](https://block.xyz/inside/block-to-roll-out-bitcoin-payments-on-square)
- [Bitlayer Joins Forces With Antpool, F2Pool, and SpiderPool to Supercharge Bitcoin DeFi](https://www.coindesk.com/business/2025/05/27/bitlayer-joins-forces-with-antpool-f2pool-and-spiderpool-to-supercharge-bitcoin-defi)
- [The Bitcoin Mempool: Private Mempools](https://bitcoinmagazine.com/technical/the-bitcoin-mempool-private-mempools)
- [Open letter for CTV+CSFS](https://ctv-csfs.com/)

## Mailing Lists

### bitcoin-dev

- [Pre-emptive commit/reveal for quantum-safe migration (poison-pill)](https://groups.google.com/g/bitcoindev/c/oa4nDmlLzN4)
- [Censorship Resistant Transaction Relay - Taking out the garbage(man)](https://groups.google.com/g/bitcoindev/c/bmV1QwYEN4k)

### Delving Bitcoin

- [Latency and Privacy in Lightning](https://delvingbitcoin.org/t/latency-and-privacy-in-lightning/1723)
- [Non-confiscatory Transaction Weight Limit](https://delvingbitcoin.org/t/non-confiscatory-transaction-weight-limit/1732)
- [Dust Expiry: Clean the UTXO set from spam](https://delvingbitcoin.org/t/dust-expiry-clean-the-utxo-set-from-spam/1707)
- [Witnessless Sync for Pruned Nodes](https://delvingbitcoin.org/t/witnessless-sync-for-pruned-nodes/1742)

## Pull requests

### BIPs, BOLTs and Proposals

- [BIP 77: Async Payjoin #1483](https://github.com/bitcoin/bips/pull/1483)
- [BIP 443: OP_CHECKCONTRACTVERIFY #1793](https://github.com/bitcoin/bips/pull/1793)
- [BIP 53: Disallow 64-byte transactions #1760](https://github.com/bitcoin/bips/pull/1760)
- [BIP172: Define Bitcoin Subunits as Satoshis #1841](https://github.com/bitcoin/bips/pull/1841)
- [BIP177: Redefine Bitcoin’s Base Unit #1821](https://github.com/bitcoin/bips/pull/1821)

### Bitcoin Core

- [Bitcoin Core development and transaction relay policy](https://bitcoincore.org/en/2025/06/06/relay-statement/)
- [CVE-2024-52919 - Remote crash due to addr message spam (part 2)](https://bitcoincore.org/en/2025/04/28/disclose-cve-2024-52919/)
- [bitcoind 29.0 much slower than 28.0 on my system #32455](https://github.com/bitcoin/bitcoin/issues/32455)
- [miner: timelock the coinbase to the mined block's height #32155](https://github.com/bitcoin/bitcoin/pull/32155)
- [cluster mempool: add txgraph diagrams/mining/eviction #31444](https://github.com/bitcoin/bitcoin/pull/31444)
- [psbt: add non-default sighash types to PSBTs and unify sighash type match checking #31622](https://github.com/bitcoin/bitcoin/pull/31622)
- [multiprocess: Add bitcoin wrapper executable #31375](https://github.com/bitcoin/bitcoin/pull/31375)

### Core Lightning

- [Peer storage enable #8140](https://github.com/ElementsProject/lightning/pull/8140)
- [Splice: Interop Final (probably) with Eclair #8021](https://github.com/ElementsProject/lightning/pull/8021)
- [Signmessage #8226](https://github.com/ElementsProject/lightning/pull/8226)

### Eclair

- [Attributable failures #3065](https://github.com/ACINQ/eclair/pull/3065)

### Others

- [NBitcoin Crash Bug](https://github.com/MetacoSA/NBitcoin/pull/1269)
