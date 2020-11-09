---
layout: post
title: "Socratic Seminar #13"
---

[Meetup](https://www.meetup.com/Bitcoin-Lab-Berlin/events/kmbjwrybcpbnb/)

## Optech

- [Newsletter #119](https://bitcoinops.org/en/newsletters/2020/10/14/)
- [Newsletter #120](https://bitcoinops.org/en/newsletters/2020/10/21/)
- [Newsletter #121](https://bitcoinops.org/en/newsletters/2020/10/28/)
- [Newsletter #122](https://bitcoinops.org/en/newsletters/2020/11/04/)

## Security/CVEs/InfoSec/Research

- [MuSig2: Simple Two-Round Schnorr Multi-Signatures](https://eprint.iacr.org/2020/1261)
- [LN Research Data](https://github.com/lnresearch/topology)
- [Why are you hiding: Characterising Proxy Usage in the Bitcoin Peer-to-Peer Network](https://hpi.de/fileadmin/user_upload/fachgebiete/meinel/teaching/ws2020/Why_are_you_hiding_.pdf)
- [Gotta Catch’em All! Improving P2P Network Crawling Strategies](https://hpi.de/fileadmin/user_upload/fachgebiete/meinel/teaching/ws2020/Gotta_Catch_em_All__IEEE_NCA.pdf)
- [securePrune: Secure block pruning in UTXO based blockchains using Accumulators](https://arxiv.org/abs/2010.05448)
- [CVE-2020-26895: LND Low-S Tx-Relay Standardness](https://lists.linuxfoundation.org/pipermail/lightning-dev/2020-October/002858.html)
- [CVE-2020-26896: LND Invoice Preimage Extraction](https://lists.linuxfoundation.org/pipermail/lightning-dev/2020-October/002857.html)
- [Diplomarbeit: Die Einzelzwangsvollstreckung in Bitcoins - Möglichkeiten des Zugriffs ](https://d-nb.info/1215208820/34)
- [This Month In Bitcoin Privacy October 2020 Newsletter](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/October_2020/)
- [Large Wallet with allegedly long-time lost keys emptied out](https://twitter.com/Dogetoshi/status/1323753835391864832?s=19)
- [Low Bandwidth Bitcoin](https://github.com/global-mesh-labs/Low_Bandwidth_Bitcoin/blob/main/Low_Bandwidth_Bitcoin.md)
- [The Growth of Bitcoin Merge Mining](https://blog.bitmex.com/the-growth-of-bitcoin-merge-mining/)
- [Hashrate Index](https://hashrateindex.com/)
- [How nearly all personal hardware wallet multisig setups are insecure](https://shiftcrypto.ch/blog/how-nearly-all-personal-hardware-wallet-multisig-setups-are-insecure/)

## Miscellaneous

- [Trezor Suite Public Beta](https://blog.trezor.io/introducing-trezor-suite-public-beta-7c5949aeef45)
- [Coinbase will sponsor two Bitcoin Core developers](https://blog.coinbase.com/coinbase-will-sponsor-two-bitcoin-core-developers-with-first-crypto-community-fund-grants-cf55a3a520a3)
- [BitMex Research on Brainwallets](https://blog.bitmex.com/call-me-ishmael/)
- [First Bitcoin “Mixer” Penalized by FinCEN for Violating Anti-Money Laundering Laws](https://www.fincen.gov/news/news-releases/first-bitcoin-mixer-penalized-fincen-violating-anti-money-laundering-laws)
- [PayPal Launches New Service Enabling Users to Buy, Hold and Sell Cryptocurrency](https://newsroom.paypal-corp.com/2020-10-21-PayPal-Launches-New-Service-Enabling-Users-to-Buy-Hold-and-Sell-Cryptocurrency)
- [What’s Coming To The Bitcoin Core Wallet in 0.21](https://achow101.com/2020/10/0.21-wallets)
- [Umbrel: personal Bitcoin and Lightning Network node](https://getumbrel.com/)
- [Activating Soft Forks in Bitcoin](http://www.erisian.com.au/wordpress/2020/10/26/activating-soft-forks-in-bitcoin)
- [Enterprise Bitcoin Engineering](https://blog.river.com/enterprise-bitcoin-engineering/)
- [Mercury Statechain](https://blog.commerceblock.com/mercury-swap-test-8d291b684cb4)
- [Lightning Pool: A Technical Deep-Dive](https://lightning.engineering/posts/2020-11-02-pool-deep-dive/)
- [Ledger Phising Attack](https://twitter.com/ndeet/status/1320307663427768320)
- [Coldcard Best Practices](https://mattodell.keybase.pub/coldcard.html)
- [Nunchuk: New Multisig Wallet](https://hugonguyen.medium.com/introducing-nunchuk-multisig-made-easy-1b9846e6b3ca)
- [Atomic Pivot](https://atomic.finance/blog/an-atomic-pivot/)
- [Miner Autotuning](https://www.minerupdate.com/news/miner-insights/autotuning-by-braiins)
- [Utreexo Project Update](https://blog.bitmex.com/current-status-of-the-utreexo-project/)
- [DLC: Oracle Public Key Distribution](https://suredbits.com/dlc-key-management-pt-3-oracle-public-key-distribution/)

## Europe/Germany/Berlin

- [First compliant Bitcoin-ATMs in Germany?](https://cpi-int.coop/)
- [Room77 is closed for good](https://www.coindesk.com/bitcoin-bar-room-77-closes)
- [Sutor Bank now offers a regulated Bitcoin exchange in Germany](https://bit4coin.net/)
- [Spain plans bill to force disclosure of crypto-currency holdings](https://news.trust.org/item/20201013100845-lja6d/)

## Mailing Lists

### bitcoin-dev

- [(Continued discussion) Progress on bech32 for future Segwit Versions (BIP-173)](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2020-October/018236.html)

### lighting-dev

- [Hold fees: 402 Payment Required for Lightning itself](https://lists.linuxfoundation.org/pipermail/lightning-dev/2020-October/002826.html)
- [Simplified (but less optimal) HTLC Negotiation](https://lists.linuxfoundation.org/pipermail/lightning-dev/2020-October/002831.html)

## Pull requests

### Bitcoin Core

- [Complete the BIP155 implementation and upgrade to TORv3 #19954](https://github.com/bitcoin/bitcoin/pull/19954)
- [Implement BIP 340-342 validation (Schnorr/taproot/tapscript) #19953](https://github.com/bitcoin/bitcoin/pull/19953)
- [Overhaul transaction request logic #19988](https://github.com/bitcoin/bitcoin/pull/19988)
- [Add sqlite as an alternative wallet database and use it for new descriptor wallets #19077](https://github.com/bitcoin/bitcoin/pull/19077)

### Secp256k1

- [Rip out non-endomorphism code + dependencies #830](https://github.com/bitcoin-core/secp256k1/issues/830)

### LND

- [lncli: allow configurable timeout in send payment #4688](https://github.com/lightningnetwork/lnd/pull/4688)

### c-lightning

- [Notification support #4046](https://github.com/ElementsProject/lightning/pull/4046)

### Eclair

- [Send to channel route #1537](https://github.com/ACINQ/eclair/pull/1537)
