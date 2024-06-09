---
layout: post
title: "Socratic Seminar #56"
---

[Meetup](https://www.meetup.com/bitcoin-lab-berlin/events/298337266/)

Thanks to [Ordimint](https://ordimint.com) for sponsoring food and drinks for this meetup!

## Security/CVEs/InfoSec/Research

- [Bitcoin's Precarious Position](https://bluematt.bitcoin.ninja/2024/05/11/bitcoins-precarious-position/)
- [FE'd Up Covenants](https://rubin.io/public/pdfs/fedcov.pdf)
- [Securing Lightning Channels against Rational Miners](https://eprint.iacr.org/2024/826)
- [Security of the Secp256k1 Elliptic Curve used in the Bitcoin Blockchain](https://www.ijcns.latticescipub.com/wp-content/uploads/papers/v4i1/A1426054124.pdf)
- [Preventing 51% Attack By Using Consecutive Block Limits In Bitcoin](https://ieeexplore.ieee.org/abstract/document/10542114)
- [A Framing Contest Between Institutional Actors on Crypto-Asset Policymaking in the EU](https://research.cbs.dk/en/publications/a-framing-contest-between-institutional-actors-on-crypto-asset-po)
- [Targeted Nakamoto: A Bitcoin Protocol to Balance Network Security and Energy Consumption](https://arxiv.org/abs/2405.15089)
- [BitVMX: A CPU for Universal Computation on Bitcoin](https://ui.adsabs.harvard.edu/abs/2024arXiv240506842D/abstract)
- [Channel Balance Interpolation in the Lightning Network via Machine Learning](https://arxiv.org/abs/2405.12087)

## Miscellaneous

- [Penlock](https://beta.penlock.io/)
- [Silentium - Silent Payments POC Light Client](https://app.silentium.dev/)
- [Silent Payments support in Cake Wallet](https://guides.cakewallet.com/docs/cryptos/bitcoin/#silent-payments)
- [Silent Payments Website](https://silentpayments.xyz/)
- [Peer-to-Peer Rights Fund](https://p2prights.org/)
- [Vitalik reviews blocksize war books](https://vitalik.eth.limo/general/2024/05/31/blocksize.html)
- [Wasabi Wallet 2.0.8 with custom coordinator](https://blog.wasabiwallet.io/wasabi-wallet-2-0-8-release-post/?ref=nobsbitcoin.com)
- [blindbitd: A Bip352 silent payment wallet which runs as daemon](https://github.com/setavenger/blindbitd)
- [ValidiTEE: a Validating Lightning Signer (VLS) service that runs inside a secure enclave](https://github.com/msgilligan/ValidiTEE)
- [Bitcoin Core vulnerability disclosure policy discussions report](https://gist.github.com/darosior/eb71638f20968f0dc896c4261a127be6)
- [ZK Rollup on Bitcoin: Technical Whitepaper](https://github.com/alpenlabs/Technical-Whitepaper/blob/main/whitepaper_v085.pdf)

## Network Data

- [OKX mempool spam](https://jochen-hoenicke.de/queue/#BTC,4d,fee)

## Europe/Germany/Berlin

- [Antwort auf kleine Anfrage der AfD](https://workupload.com/start/SsnfKxdBaYX)

## Mailing Lists

### bitcoin-dev

- [Testnet4 BIP draft](https://mailing-list.bitcoindevs.xyz/bitcoindev/a6e3VPsXJf9p3gt_FmNF_Up-wrFuNMKTN30-xCSDHBKXzXnSpVflIZIj2NQ8Wos4PhQCzI2mWEMvIms_FAEs7rQdL15MpC_Phmu_fnR9iTg=@protonmail.com/)
- [Signing a Bitcoin Transaction with Lamport Signatures (no changes needed)](https://mailing-list.bitcoindevs.xyz/bitcoindev/CAEM=y+XyW8wNOekw13C5jDMzQ-dOJpQrBC+qR8-uDot25tM=XA@mail.gmail.com/)
- [Utreexod beta release](https://mailing-list.bitcoindevs.xyz/bitcoindev/d5f47120-3397-4f56-93ca-dd310d845f3cn@googlegroups.com/T/#u)

### Delving Bitcoin

- [Ecash TIDES using Cashu and Stratum v2](https://delvingbitcoin.org/t/ecash-tides-using-cashu-and-stratum-v2/870)
- [Anonymous usage tokens from curve trees or autct](https://delvingbitcoin.org/t/anonymous-usage-tokens-from-curve-trees-or-autct/862)
- [Stable Channels - peer-to-peer dollar balances on Lightning](https://delvingbitcoin.org/t/stable-channels-peer-to-peer-dollar-balances-on-lightning/875)
- [Upgrading Existing Lightning Channels](https://delvingbitcoin.org/t/upgrading-existing-lightning-channels/881)
- [Proof-of-work based signet faucet](https://delvingbitcoin.org/t/proof-of-work-based-signet-faucet/937)

## Pull requests

### BIPs, BOLTs and Proposals

- [BIP: 337 Compressed Transactions](https://github.com/bitcoin/bips/blob/master/bip-0337.mediawiki)
- [Bitcoin Core Disclosure Policy draft](https://gist.github.com/darosior/eb71638f20968f0dc896c4261a127be6)
- [BIP352 Light Client Specification (WIP)](https://github.com/setavenger/BIP0352-light-client-specification/)
- [Define blip-0032, DNSSEC proof querying over onion messages #32](https://github.com/lightning/blips/pull/32)
- [BIP 347: OP_CAT in Tapscript #1525](https://github.com/bitcoin/bips/pull/1525)

### Bitcoin Core

- [Autotools vs CMake Feature Parity Table](https://gist.github.com/hebasto/2ef97d3a726bfce08ded9df07f7dab5e)
- [rpc: Optimize serialization and enhance metadata of dumptxoutset output #29612](https://github.com/bitcoin/bitcoin/pull/29612)
- [policy: restrict all TRUC (v3) transactions to 10kvB #29873](https://github.com/bitcoin/bitcoin/pull/29873)
- [wallet: Implement independent BDB parser #26606](https://github.com/bitcoin/bitcoin/pull/26606)
- [p2p: index TxOrphanage by wtxid, allow entries with same txid #30000](https://github.com/bitcoin/bitcoin/pull/30000)
- [validation: don't clear cache on periodic flush: >2x block connection speed #28233](https://github.com/bitcoin/bitcoin/pull/28233)

### LND

- [Announcing LND 0.18 beta: Smarter Sweeps, Inbound Fees, and Improved Scaling!](https://lightning.engineering/posts/2024-05-30-lnd-0.18-launch/?ref=nobsbitcoin.com)

### BDK & LDK

- [Log available liquidity on each channel when starting routefinding #2931](https://github.com/lightningdevkit/rust-lightning/pull/2931)

### Core Lightning

- [Ignore --ignore-fee-rates on mutual close, don't massively overpay with LDK nodes #7252](https://github.com/ElementsProject/lightning/pull/7252)
- [channeld: Reduce the feerate security margin in high fee environments #7063](https://github.com/ElementsProject/lightning/pull/7063)
