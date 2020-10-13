---
layout: post
title: "Socratic Seminar #12"
---

[Meetup](https://www.meetup.com/Bitcoin-Lab-Berlin/events/kmbjwrybcnbrb/)

## Optech

- [Newsletter #114](https://bitcoinops.org/en/newsletters/2020/09/09/)
- [Newsletter #115](https://bitcoinops.org/en/newsletters/2020/09/16/)
- [Newsletter #116](https://bitcoinops.org/en/newsletters/2020/09/23/)
- [Newsletter #117](https://bitcoinops.org/en/newsletters/2020/09/30/)
- [Newsletter #118](https://bitcoinops.org/en/newsletters/2020/10/07/)

## Security/CVEs/InfoSec/Research

- [Fake Ian Coleman (iancoleman/bip39) site is top of google search results](https://www.reddit.com/r/Bitcoin/comments/injxay/beware_fake_ian_coleman_iancolemanbip39_site_is/)
- [Bitcoin Inventory Out-of-Memory Denial-of-Service Attack](https://invdos.net/)
- [Bitcoin Multisig Hardware Signing Performance](https://blog.keys.casa/bitcoin-multisig-hardware-signing-performance/)
- [CoinJoin DoS](https://blog.wasabiwallet.io/responsible-disclosure-v4-hard-fork/)
- [Acceleration of ECDSA Verification with Endomorphism Mapping of secp256k1](https://medium.com/@CoinExChain/acceleration-of-ecdsa-verification-with-endomorphism-mapping-of-secp256k1-126e77a51dba)
- [Things Bitcoiners Don’t Want To Hear](https://medium.com/block-digest-mempool/things-bitcoiners-dont-want-to-hear-33823c2e984)
- [MPPs & Wumbo Channels: Optimizing Liquidity on the Lightning Network](https://medium.com/breez-technology/mpps-wumbo-channels-optimizing-liquidity-on-the-lightning-network-6059bedea322)
- [This Month in Bitcoin privacy](https://enegnei.github.io/This-Month-In-Bitcoin-Privacy/September_2020/)
- [Attacking Threshold Wallets](https://eprint.iacr.org/2020/1052)
- [Anonymous proof-of-asset transactions using designated blind signatures](https://arxiv.org/pdf/2009.13978.pdf)
- [DLC with Adaptor Sigs](https://gist.github.com/NicolasDorier/2d585db8e8561c66fa928b4b99a8cad1)
- [It Is Never a Compiler Bug Until It Is](http://r6.ca/blog/20200929T023701Z.html)

## Miscellaneous

- [Why mempools are the network’s most brutal information space](https://blog.knoxcustody.com/bitcoins-town-square/)
- [From the Sapio Zoo: HODL Chicken + Tux Preview](https://judica.org/blog/hodl-chicken/)
- [Bitfinex Leads Investment in Lightning Network Bitcoin Exchange](https://cryptobriefing.com/bitfinex-leads-investment-lightning-network-bitcoin-exchange/)
- [Nigiri Bitcoin](https://nigiri.vulpem.com/)
- [Bitcoin Bull open sources transaction-batching API](https://medium.com/bull-bitcoin/batcher-by-bull-bitcoin-open-source-non-custodial-on-chain-bitcoin-core-transaction-batching-api-b81e734a59e6)
- [no KYC only](https://bitcoinqna.github.io/noKYConly/)
- [Magical Bitcoin is now BDK and releases first beta](https://github.com/bitcoindevkit/bdk/releases/tag/0.1.0-beta.1)
- [Faraday Accounting](https://lightning.engineering/posts/2020-09-15-faraday-accounting/)
- [Don’t Mix Your Timelocks](https://medium.com/blockstream/dont-mix-your-timelocks-d9939b665094)
- [Joost Jager leaves Lightning Labs to work on Lightning security](https://twitter.com/joostjgr/status/1308414364911841281)
    - [Circuit Breaker](https://github.com/lightningequipment/circuitbreaker)
- [Bitcoin based DocuSign competitor](https://www.woleet.io/)
- [How to pay for Bitcoin Development](https://www.pierrerochard.com/how-to-pay-for-bitcoin-development/)
- [How to pay for Bitcoin Reviews](https://www.pierrerochard.com/how-to-pay-for-bitcoin-code-reviews/)
- [Specter adds Smartcard support](https://twitter.com/StepanSnigirev/status/1309149888341573632)
- [Square Crypto has a website](https://squarecrypto.org/)
- [Suredbits - Taproot upgrade](https://suredbits.com/the-taproot-upgrade/)
- [Virtual HCPP](https://bitcoinmagazine.com/articles/hackers-congress-paralelni-polis-is-ready-to-deliver-fifty-eight-hours-of-freedom-content)
- [Murch joins Chaincode](https://twitter.com/murchandamus/status/1311679486866403333)
- [Blockstream Aqua Wallet](https://blockstream.com/2020/09/26/en-introducing-aqua-wallet/)
- [Building on Liquid](https://twitter.com/Liquid_BTC/status/1304120260593889288)
- [Bitcoin Privacy Guide](https://bitcoinprivacy.guide/)
- [Why we may fail Lightning](https://medium.com/@antoine.riard/why-we-may-fail-lightning-ee3692de1a55)
- [Disconnecting Simplicity Expressions](https://medium.com/blockstream/disconnecting-simplicity-expressions-7b8ee0392fde)

## Mailing Lists

### bitcoin-dev

- [A Replacement for RBF and CPFP: Non-Destructive TXID Dependencies for Fee Sponsoring](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2020-September/018168.html)
- [Floating Point Nakamoto Consensus](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2020-September/018199.html)
- [Compiler bug discussion](http://www.erisian.com.au/meetbot/bitcoin-core-dev/2020/bitcoin-core-dev.2020-09-24-19.02.log.html#l-18)
- [Endomorphism in Secp256k1](https://github.com/bitcoin-core/secp256k1/pull/826)

### lightning-dev

- [Partial LND Vulnerability Disclosure, Upgrade to 0.11.x](https://lists.linuxfoundation.org/pipermail/lightning-dev/2020-October/002819.html)

## Pull requests

### BIPs, BOLTs and Proposals

- [More conservative `cltv_expiry_delta` recommendations #785](https://github.com/lightningnetwork/lightning-rfc/pull/785)

### Bitcoin Core

- [BIP-325: Signet [consensus] #18267](https://github.com/bitcoin/bitcoin/pull/18267)
- [Remove the automatic creation and loading of the default wallet #15454](https://github.com/bitcoin/bitcoin/pull/15454)
- [Add -netinfo peer connections dashboard #19643](https://github.com/bitcoin/bitcoin/pull/19643)
- [The ultimate send RPC #16378](https://github.com/bitcoin/bitcoin/pull/16378)

### LND

- [lncli: add profiles for easy multi-node management #4310](https://github.com/lightningnetwork/lnd/pull/4310)
- [watchtower: conditionally reconstruct justice txns for anchor channels #4576](https://github.com/lightningnetwork/lnd/pull/4576)
- [chanfitness: Rate limit in memory events based on peer flap rate #4440](https://github.com/lightningnetwork/lnd/pull/4440)
- [add new max channel size config option #4567](https://github.com/lightningnetwork/lnd/pull/4567)

### c-lightning

- [Dual-funding, accepter side only #3973](https://github.com/ElementsProject/lightning/pull/3973)
- [Multifundchannel #3763](https://github.com/ElementsProject/lightning/pull/3763)
- [Multiwithdraw #3812](https://github.com/ElementsProject/lightning/pull/3812)
- [feat: notification channel_state_changed #4020](https://github.com/ElementsProject/lightning/pull/4020)

### Eclair

- [Prioritize lowest capacity channels #1539](https://github.com/ACINQ/eclair/pull/1539)
- [Plugin messaging #1528](https://github.com/ACINQ/eclair/pull/1528)

### Joinmarket

- [BIP78 receiver over a Tor hidden service. #682](https://github.com/JoinMarket-Org/joinmarket-clientserver/pull/682)
