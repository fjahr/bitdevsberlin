---
layout: post
title: "Socratic Seminar #69"
---

[Meetup](https://www.meetup.com/bitcoin-lab-berlin/events/306678770/)

Thanks to [Ordimint](https://ordimint.com) for sponsoring food and drinks for this meetup!


## Security/CVEs/InfoSec/Research

- [Overview over recent BitVM developments: BitVM1, BitVM2, Garbled Circuits etc.](https://x.com/david_seroy/status/1930342753961161172)
- [Bridging Bitcoin to Second Layers via BitVM2](https://eprint.iacr.org/2025/1158)
- [BitVM3](https://bitvm.org/bitvm3.pdf)
- [Union Bridge:A Trust-minimized Bridge for Rootstock using BitVMX](https://arxiv.org/pdf/2501.07435)
- [Spiral Blog: The Scroll #4: Intersection Attacks on CoinJoin Anonymity](https://spiralbtc.substack.com/p/the-scroll-4-intersection-attacks)
- [How Stratum V2 Increases Mining Profitability](https://x.com/StratumV2/status/1933191370123993478)
- [The Rich Get Richer in Bitcoin Mining - Induced by Blockchain Forks](https://arxiv.org/abs/2506.13360)
- [Monero’s Decentralized P2P Exchanges: Functionality, Adoption, and Privacy Risks](https://arxiv.org/pdf/2505.02392)

## Network Data

- [Notes on 'DoS due to inv-to-send sets growing too large' from May 2023](https://b10c.me/observations/15-inv-to-send-queue/)

## Europe/Germany/Berlin

- [Arbeitslohn in Bitcoin](https://www.vdaa.de/pressemitteilungen/arbeitslohn-in-bitcoin-co-gericht-sagt-ja/)
- [Sparkassen ermöglichen Privatkunden Bitcoin-Handel](https://www.wiwo.de/dpa/kryptowaehrung-sparkassen-ermoeglichen-privatkunden-bitcoin-handel/30387088.html)
- [Deutsche Bank will Privat- und Firmenkunden Handel und Verwahrung von Bitcoin anbieten](https://www.blocktrainer.de/blog/deutsche-bank-krypto-verwahrdienstleistungen-fuer-2026-geplant)

## Miscellaneous

- [Another explanation of how Ark works](https://nehanarula.org/2025/05/20/ark.html)
- [Augur: An Open Source Bitcoin Fee Estimation Library](https://engineering.block.xyz/blog/augur-an-open-source-bitcoin-fee-estimation-library)
- [Frostsnap open to pre-orders](https://frostsnap.com/)
- [AnchorWatch Inheritance protocol](https://x.com/AnchorWatch/status/1935034851268157751)
- [Eric Voskuil on Bitcoin Core's UTXO Model](https://brink.dev/blog/2025/06/17/eng-call-eric-voskuil-utxo-model/)
- [Announcement: new Zerolink coinjoin coordinator](https://ashigaru.rs/news/announcement-whirlpool/)
- [New ashigaru whirlpool coordinator can de-anonymize users](https://bitcointalk.org/index.php?topic=5547639.0)
- [Bitmain working on decentralized mining!?](https://x.com/bitmaintech/status/1927581481674670492)
- [First mobile wallets using Spark (statechains) are live](https://docs.spark.money/spark/spark-tldr): [BlitzWallet](https://Wallet.blitz-wallet.com) and [Wallet of Satoshi](https://x.com/walletofsatoshi/status/1940169795565146571)
- [A practical example how CTV+CSFS enables Eltoo/Lnsymmetry channels](https://github.com/stutxo/simple_ctv_csfs)

## Mailing Lists

### bitcoin-dev

- [The case for privatizing Bitcoin Core](https://mailing-list.bitcoindevs.xyz/bitcoindev/CABaSBax-meEsC2013zKYJnC3phFFB_W3cHQLroUJcPDZKsjB8w@mail.gmail.com/)

### Delving Bitcoin

- [Reimagining Onion Messages as an Overlay Layer](https://delvingbitcoin.org/t/reimagining-onion-messages-as-an-overlay-layer/1799)
- [Where does the 33.33% threshold for selfish mining come from?](https://delvingbitcoin.org/t/where-does-the-33-33-threshold-for-selfish-mining-come-from/1757)
- [CTV vault output descriptor](https://delvingbitcoin.org/t/ctv-vault-output-descriptor/1766)
- [JIT fees with TXHASH: comparing options for sponsorring and stacking](https://delvingbitcoin.org/t/jit-fees-with-txhash-comparing-options-for-sponsorring-and-stacking/1760/1)
- [Fingerprinting nodes via addr requests](https://delvingbitcoin.org/t/fingerprinting-nodes-via-addr-requests/1786)

## Pull requests

### Bitcoin Core

- [Add checkBlock() to Mining interface #31981](https://github.com/bitcoin/bitcoin/pull/31981)

### LND

- [peer+feature: start to signal the prod rbf coop close bit #9858](https://github.com/lightningnetwork/lnd/pull/9858)

### Eclair

- [Prepare attribution data for trampoline payments #3109](https://github.com/ACINQ/eclair/pull/3109)
- [Parse offers and pay offers with currency #3101](https://github.com/ACINQ/eclair/pull/3101)

### BDK/rust-bitcoin & LDK/rust-lightning

- [Channel Establishment for V3 Channels #3792](https://github.com/lightningdevkit/rust-lightning/pull/3792)
- [Revert attribution of failures #3817](https://github.com/lightningdevkit/rust-lightning/pull/3817)

### Others

- [feat(wallet): enhance Coin Selection with advanced filters and improved UX #6755](https://github.com/btcpayserver/btcpayserver/pull/6755)
