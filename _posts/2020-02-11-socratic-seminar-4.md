---
layout: post
title: "Socratic Seminar #4"
---

[Meetup](https://www.meetup.com/Bitcoin-Lab-Berlin/events/267904053/)

Special thanks to Fulmo for organizing and c-base for event space.

## Looking for transcription volunteers
- [Michael Folkson: Want to Learn About Bitcoin? Try Contributing a Transcript](https://bitcoinmagazine.com/articles/op-ed-want-to-learn-about-bitcoin-try-contributing-a-transcript)
- [Bryan Bishop: Example of Socratic Seminar Austin transcript](https://diyhpl.us/wiki/transcripts/austin-bitcoin-developers/2019-11-19-socratic-seminar-4/)
- [Google Recorder (Example for automation tools)](https://play.google.com/store/apps/details?id=com.google.android.apps.recorder&hl=en)

## Europe/Germany/Berlin
- [Comment on the new money laundering law](https://www.lto.de/recht/hintergruende/h/blockchain-bitcoin-regulierung-bafin-aufsicht-digitale-vermoegenswerte-erlaubnis/)
- [Tagesschau: Bitcoin erreicht den Mainstream](https://www.tagesschau.de/wirtschaft/boerse/bitcoin-153.html)
- [German translation of "Grokking Bitcoin"](http://bitcoinbegreifen.de/)

## Bitcoin Optech newsletter
- [Newsletter #81](https://bitcoinops.org/en/newsletters/2020/01/22/)
- [Newsletter #82](https://bitcoinops.org/en/newsletters/2020/01/29/)
- [Newsletter #83](https://bitcoinops.org/en/newsletters/2020/02/05/)

Security/CVEs/InfoSec/Research
- [Characterizing Orphan Transactionsin the Bitcoin Network](https://arxiv.org/pdf/1912.11541.pdf)
- [The Arwen Trading Protocol](https://eprint.iacr.org/2020/024)
- [A Bitcoin Payment Network with Reduced Transaction Fees and Confirmation Times](https://www.sciencedirect.com/science/article/abs/pii/S1389128619308850)
- [Deanonymizing Tor hidden service users through Bitcoin transactions analysis](https://www.sciencedirect.com/science/article/pii/S0167404818309908)
- [Kraken finds flaw in Trezor hardware wallets](https://blog.kraken.com/post/3662/kraken-identifies-critical-flaw-in-trezor-hardware-wallets/)
- [Academics steal data from air-gapped systems using screen brightness variations](https://www.zdnet.com/article/academics-steal-data-from-air-gapped-systems-using-screen-brightness-variations/)
- [Ed25519 / EdDSA key leakage due to fragility in recommended nonce procedure](https://moderncrypto.org/mail-archive/curves/2020/001012.html)
- [Cache out attack](https://cacheoutattack.com/)

## Mailing lists
### lightning-dev
- [DRAFT: interactive tx construction protocol](https://lists.linuxfoundation.org/pipermail/lightning-dev/2020-January/002466.html)
- [Speculations on hardware wallet support for Lightning](https://lists.linuxfoundation.org/pipermail/lightning-dev/2020-January/002425.html)
- [Layered commitments with eltoo](https://lists.linuxfoundation.org/pipermail/lightning-dev/2020-January/002448.html)
- [Decoy node_ids and short_channel_ids](https://lists.linuxfoundation.org/pipermail/lightning-dev/2020-January/002435.html)

### bitcoin-dev
- [Modern Soft Fork Activation](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2020-January/017547.html)
- [Taproot critique](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2020-February/017618.html)
- [Onchain fee insurance mechanism](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2020-January/017601.html)
- [Payswap](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2020-January/017595.html)
- [Announcement: Discreet Log Contract Protocol Specification](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2020-January/017563.html)
- [***UNCHECKED*** Wormhole: Sending and receiving bitcoin anonymously](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2020-January/017585.html)

## Pull requests/repo updates/BIPs
### BIPs
- [Taproot BIP numbers](https://github.com/bitcoin/bips/pull/876)
- [CHECKTEMPLATEVERIFY assigned BIP119](https://github.com/bitcoin/bips/blob/master/bip-0119.mediawiki)
  - [CTV meeting](https://twitter.com/jeremyrubin/status/1223672458516938752)
  - [Critique by gmaxwell](https://bitcointalk.org/index.php?topic=5220520.msg53699487#msg53699487)
### Bitcoin Core
- [Taproot WIP code](https://github.com/bitcoin/bitcoin/pull/17977)
- [p2p: supplying and using asmap to improve IP bucketing in addrman #16702](https://github.com/bitcoin/bitcoin/pull/16702)
- [Use rolling bloom filter of recent block txs for AlreadyHave() check #17951](https://github.com/bitcoin/bitcoin/pull/17951)
- [Bitcoin Knots fork release 0.19.1 with BIP 157 (Neutrino)](https://bitcoinknots.org/)

### LND
- [LND 0.9.0-beta released](https://github.com/lightningnetwork/lnd/releases/tag/v0.9.0-beta)
  - [Blog post](https://blog.lightning.engineering/announcement/2020/01/22/lnd-v0.9.html)

### Acinq
- [Phoenix now supporting LNURL (v1.1.0)](https://github.com/ACINQ/phoenix/releases)
- [Eclair 0.3.3 release with multipart payments, trampoline routing and deterministic builds](https://github.com/ACINQ/eclair/releases/tag/v0.3.3)

## Miscellaneous
- [Square Crypto is working on LDK](https://medium.com/@squarecrypto/what-were-building-lightning-development-kit-1ed58b0cab06)
- [Taproot support in btcdeb](https://github.com/kallewoof/btcdeb/tree/taproot)
  - [Example](https://github.com/kallewoof/btcdeb/blob/taproot/doc/tapscript-example.md)
- [Strike by Zap](https://medium.com/@JimmyMow/announcing-strike-by-zap-4f578c7c8984)
- [Amiti Uttarwar: Onboarding to Bitcoin Core](https://medium.com/@amitiu/onboarding-to-bitcoin-core-7c1a83b20365)
- [Chaincode Podcast](https://podcast.chaincode.com/)
- [Bitmex Research - Proportion Of Public vs Private Channels](https://blog.bitmex.com/lightning-network-part-7-proportion-of-public-vs-private-channels/)
- [Chainalysis: Darknet markets analysis](https://blog.chainalysis.com/reports/darknet-markets-cryptocurrency-2019)
- [Chainalysis: Money laundering analysis](https://blog.chainalysis.com/reports/money-laundering-cryptocurrency-2019)
- [Miner salary share across PoW currencies](https://twitter.com/yassineark/status/1215700239245549575)
- [LSATs: Pseudonymous Authentication using Bitcoin Lightning Payments](https://medium.com/tierion/lsats-pseudonymous-authentication-using-bitcoin-lightning-payments-459e209b4b36)
- [c-lightning REST plugin](https://github.com/Ride-The-Lightning/c-lightning-REST)

## Quiz
1. Which BIP numbers were assigned to Taproot/Tapscript/Schnorr?
  - a) 140, 141, 142
  - b) 240, 241, 242
  - c) 340, 341, 342
  - d) 440, 441, 442

2. What is the coinbase?
  - a) Mining Pool
  - b) Exchange/Custodial Wallet
  - c) First TX in a Block that pays the miner/pool its reward
  - d) Mining hardware

3. Who gets the Bitcoin transaction fees?
  - a) The mining pool
  - b) The miner
  - c) The exchange
  - d) The wallet provider

4. Why can’t the genesis block coinbase be spent?
  - a) Satoshi lost the private key
  - b) Genesis block is not included in TX database
  - c) Because of the "Chancellor Bank Bailout" text
  - d) Bitcoin wasn't worth anything at that time

5. What is Bitcoin Dust?
  - a) A Bitcoin hard fork
  - b) Output that costs more to spend than what it is worth
  - c) A famous documentary about Bitcoin
  - d) Another name for the root of the Merkle tree

6. How large can the description inside an Lightning invoice be?
  - a) 639 bytes
  - b) 140 bytes
  - c) 2049 bytes

7. What specific technology was needed to fix transaction malleability in order to implement the Lightning Network?
  - a) HD wallets
  - b) ASICBoost
  - c) SegWit
  - d) OP_CHECKLOCKTIMEVERIFY

8. What is it called when you swap a Lightning Network payment for an onchain payment?
  - a) Closing the channel
  - b) Eltoo
  - c) Balancing channels
  - d) Submarine Swap

9. Which BIP number did CHECKTEMPLATEVERIFY get assigned?
  - a) 113
  - b) 115
  - c) 117
  - d) 119

10. What is true for a PRIVATE lightning channel? (multiple possible)
  - a) Channel is not announced to the network
  - b) Initiator can only receive funds through the channel
  - c) Initiator can only send funds through the channel
  - d) A node that only opens private channels can be unknown to the network

### Answers
1. c
2. a, b
3. b
4. b
5. c
6. a
7. c
8. d
9. d
10. a, d
