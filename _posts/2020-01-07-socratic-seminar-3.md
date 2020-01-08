---
layout: post
title: "Socratic Seminar #3"
---

[Meetup](https://www.meetup.com/Bitcoin-Lab-Berlin/events/267595081/)

Special thanks to Fulmo and CODE University for organization and event space.

## Bitcoin Optech newsletter
- [Newsletter #77](https://bitcoinops.org/en/newsletters/2019/12/18/)

## Network data/statistics
- [Clark Moody Bitcoin Dashboard](https://bitcoin.clarkmoody.com/dashboard/)
- [Number of nodes historical view](https://luke.dashjr.org/programs/bitcoin/files/charts/historical.html)
- [Bitcoin 11th birthday statistics](https://bitcoinmagazine.com/articles/happy-birthday-bitcoin-heres-a-look-at-bitcoins-11th-year-by-the-numbers)
- [Bitmex Lightning Network penalty transaction alert system](https://blog.bitmex.com/lightning-network-part-5-bitmex-research-launches-penalty-transaction-alert-system/)

## Taproot
- [Taproot Review retrospective (discussion)](https://github.com/ajtowns/taproot-review)
- [Taproot Presentation at Bitdev SF](https://diyhpl.us/wiki/transcripts/sf-bitcoin-meetup/2019-12-16-bip-taproot-bip-tapscript/)

## CVEs and Research

### Privacy
- [Anti virus false positive reporting](https://github.com/bitcoin/bitcoin/issues/17779)
- [Binance tracking wasabi transactions](https://twitter.com/bittlecat/status/1207621591820951552)
- [Anonymous CoinJoin Transactions with Arbitrary Values](https://www.comsys.rwth-aachen.de/fileadmin/papers/2017/2017-maurer-trustcom-coinjoin.pdf)
- [Wasabi Reseach Club](https://github.com/zkSNACKs/WasabiResearchClub)
- [Scrit](https://github.com/scritcash/scrit)

### Security
- [Strandhogg Android vulnerability](https://promon.co/security-news/strandhogg/)
- [Analysis of insertion in Bech32 strings](https://gist.github.com/sipa/a9845b37c1b298a7301c33a04090b2eb)
- [Flaw Found in Keepkey Crypto Hardware Wallet](https://blog.kraken.com/post/3245/flaw-found-in-keepkey-crypto-hardware-wallet/)
- [List of Hardware Wallet Hacks](https://thecharlatan.github.io/List-Of-Hardware-Wallet-Hacks/)
- [Can We Build Trustable Hardware?](https://www.bunniestudios.com/blog/?p=5706)
- [The pitfalls of multisig when using hardware wallets](https://medium.com/shiftcrypto/the-pitfalls-of-multisig-when-using-hardware-wallets-9b0e98e4c19c)

### Other
- [Reducing the Bandwidth of Block Propagation in Bitcoin Network With Erasure Coding](https://ieeexplore.ieee.org/abstract/document/8922597)
- [The senatorial governance of Bitcoin: making (de)centralized money](https://www.tandfonline.com/doi/abs/10.1080/03085147.2019.1678262)
- [Simulation of the Bitcoin Network Considering Compact Block Relay and Internet Improvements](https://arxiv.org/abs/1912.05208)
- [Bitcoin mining allocation](https://research.binance.com/analysis/bitcoin-mining-allocation)
- [Lightning hosted channels](https://lightning-wallet.com/hosted-channels#hosted-channels)
- [Gnocchi: Multiplexed Payment Channels for Cryptocurrencies](https://link.springer.com/chapter/10.1007/978-3-030-36938-5_30)

## Mailing lists

### bitcoin-dev
- [CashFusion - Non-equal value CoinJoins](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2019-December/017538.html)
- [easypaysy - A layer-two protocol to send payments without addresses](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2019-December/017503.html)
- [Blind Merged Mining with covenants](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2019-December/017534.html)
- [OP_CTV Workshop](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2020-January/017546.html)

### lightning-dev
- [Lightning in a Taproot future](https://lists.linuxfoundation.org/pipermail/lightning-dev/2019-December/002375.html)
- [On Path Privacy](https://lists.linuxfoundation.org/pipermail/lightning-dev/2019-December/002408.html)
- [Pay-to-Open and UX improvements](https://lists.linuxfoundation.org/pipermail/lightning-dev/2019-December/002381.html)

## Pull requests and repo updates
### BOLTs
- [Base AMP](https://github.com/lightningnetwork/lightning-rfc/pull/643)
- [Anchor outputs](https://github.com/lightningnetwork/lightning-rfc/pull/688)

### Bitcoin Core
- [`avoid_reuse=true` can be bypassed by using pubkey in alternate addresses](https://github.com/bitcoin/bitcoin/issues/17605)
  - [Fix: IsUsedDestination should count any known single-key address](https://github.com/bitcoin/bitcoin/pull/17621)
- [RPC Whitelisting](https://github.com/bitcoin/bitcoin/pull/12763)

### c-lightning
- [Add `createonion` and `sendonion` RPC commands](https://github.com/ElementsProject/lightning/pull/3260)
- [MPP send and receive support](https://github.com/ElementsProject/lightning/pull/3309)

### LND
- [Allow settling invoices via multi-path payments](https://github.com/lightningnetwork/lnd/pull/3415)

### Wasabi
- [v1.1.10.2 released](https://github.com/zkSNACKs/WalletWasabi/releases/tag/v1.1.10.2)
- [RPC Server](https://github.com/zkSNACKs/WalletWasabi/pull/1449)
- [Replace 'Label' by 'Observers'](https://github.com/zkSNACKs/WalletWasabi/pull/2901)

## Miscellaneous
- [Bitcoin fuzz testing coverage](https://twitter.com/MarcoFalke/status/1203174783300620288)
- Unchained Capital multisig and key sharding projects
  - [Caravan Demo](https://unchained-capital.github.io/caravan/#/)
  - [Caravan Code](https://github.com/unchained-capital/caravan)
  - [Hermit Code](https://github.com/unchained-capital/hermit)
  - [SLIP0039](https://github.com/satoshilabs/slips/blob/master/slip-0039.md)
  - [Unchained Capital Blog](https://www.unchained-capital.com/blog/)
- [MimbleWimble/Confidential Transactions in Bitcoin](https://www.reddit.com/r/Bitcoin/comments/e65vdf/could_bitcoins_privacy_benefit_from_litecoins_eb/f9olxfy/)
- [John Newbery year review tweets](https://twitter.com/jfnewbery/status/1208559196465184768)
- [100 c-lightning features](https://twitter.com/clightningcomit/status/1212810910731063297)
- [Focus in Bitcoin development](http://www.erisian.com.au/wordpress/2020/01/07/bitcoiner-maximalism)
- [Fiat Market Capitalization](https://fiatmarketcap.com/)
- [Current state of P2P research in Bitcoin/Erlay](https://www.youtube.com/watch?v=ZUWs00Anpaw)
- [Build your own Bitcoin hardware wallet](https://www.youtube.com/playlist?list=PLn2qRQUAAg0z_-R0swVuSsNS9bzRu6oP5)
- [Metal Bitcoin Seed Storage Reviews](https://jlopp.github.io/metal-bitcoin-storage-reviews/ )
- [GoldenEye - Running Bitcoin from Space](https://www.alexanderjsingleton.com/goldeneye-running-bitcoin-from-space-with-blockstream/)
- [NthKey - iOS device in Bitcoin multisig](https://nthkey.com/)
    - [Demo](https://www.youtube.com/watch?v=1YgkAOY08iE)

## Europe/Germany/Berlin
- [Mining Meetup in Berlin](https://www.meetup.com/de-DE/Cryptocurrency-Mining-Group/events/267043861/)
- [Germans queue to buy Gold](https://twitter.com/PopescuCo/status/1209559269382787072?s=20)

## Quiz

Tool: [Kahoot](https://kahoot.com/)

### Questions
1. Around which date will the next halving/halvening happen?
  - a) April 30, 2020
  - b) May 13, 2020
  - c) June 15, 2020
  - d) May 15, 2022

2. What notation is this? `or_d(c:pk(A),and_v(vc:pk_h(B),older(144)))`
  - a) Bitcoin script
  - b) Policy script
  - c) Miniscript
  - d) Stack Script

3. Which are NOT use-cases for Partially Signed Bitcoin Transactions (PSBT)?
  - a) Hardware-wallets
  - b) Multipath routing
  - c) Multisig setups
  - d) Mining

4. Which method of peer discovery was removed in bitcoind 0.8 in 2013?
  - a) DNS seeds
  - b) Hardcoded IPs
  - c) IRC
  - d) Asking other nodes with "getaddr"

5. Which soft fork would make the eltoo udate scheme possible in the Lightning network?
  - a) OP_CHECKTEMPLATEVERIFY
  - b) NODE_NETWORK_LIMITED
  - c) Schnorr/Taproot
  - d) SIGHASH_NOINPUT

6. Why does the Lightning network use port 9735 by default?
  - a) it represents the "High voltage" emoji in Unicode
  - b) it was the BTC price in Dollar when the port was selected
  - c) it was the lowest available port
  - d) it represents "Fulmo" when translated to binary and back

7. When was the first Bitcoin Stammtisch at Room77 on the first Thursday of the month?
  - a) August 4, 2010
  - b) August 4, 2011
  - c) August 4, 2012
  - d) August 4, 2013

8. Which letter can be inserted into a bech32 address to exploit its recently discovered weakness?
  - a) p
  - b) o
  - c) q
  - d) n

9. Which ones of the following are proposed BIPs included in the Taproot proposal?
  - a) BIP Schnorr
  - b) BIP Taptweak
  - c) BIP Tapscript
  - d) BIP Tapleaf

10. Where do you find the notes for this meetup?
  - a) bitdevs.berlin
  - b) bitdevsberlin.org
  - c) bitdevs.org/berlin
  - d) bitdevsberlin.com

### Answers
1. b
2. c
3. b, d
4. c
5. d
6. a
7. b
8. c
9. a, c
10. a
