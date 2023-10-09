---
layout: post
title: "Socratic Seminar #48"
---

[Meetup](https://www.meetup.com/bitcoin-lab-berlin/events/294115696/)

## Security/CVEs/InfoSec/Research

- [ZeroSync demo](https://zerosync.org/demo/)
- [Runes](https://rodarmor.com/blog/runes/)
- [An Introduction to Spiderchain](https://blog.lopp.net/an-introduction-to-spiderchain/)
- [Electrum CVE: sending with Lightning: payment_preimage validation is skipped on Android](https://github.com/spesmilo/electrum/security/advisories/GHSA-9gpc-prj9-89x7)
- [Electrum CVE: receiving with Lightning: partial MPP might be accepted](https://github.com/spesmilo/electrum/security/advisories/GHSA-8r85-vp7r-hjxf)
- [Don’t overextend your Oblivious Transfer](https://blog.trailofbits.com/2023/09/20/dont-overextend-your-oblivious-transfer/)
- [Undetectable Selfish Mining](https://browse.arxiv.org/pdf/2309.06847.pdf)
- [Our Data Driven Approach to Fixing Payment Reliability](https://blog.mutinywallet.com/fixing-payment-reliability/)
- [BitVM](https://bitvm.org/bitvm.pdf)

## Miscellaneous

- [GPUtopia](https://gputopia.ai/)
- [warnet](https://warnet.dev/)
- [Lexe Wallet](https://lexe.app/)
- [OP_VAULT Demo Video](https://www.youtube.com/watch?v=7Zwm5iHFyBQ)
- [Coinjoins.org](https://www.coinjoins.org/)
- [Delving Bitcoin Forum](https://delvingbitcoin.org/)
- [Covenant Tools Softfork Discussion](https://delvingbitcoin.org/t/covenant-tools-softfork/98)

## Network Data

- [Bitcoin price estimation from on-chain data](https://utxo.live/oracle/)
- [Invalid Marathon Block](https://twitter.com/0xB10C/status/1706937041739530556)
- [Invalid MARAPool block 809478](https://b10c.me/observations/07-invalid-block-809478/)
- [Hunting the Real Bitcoin Network Hashrate](https://blog.lopp.net/hunting-the-real-bitcoin-network-hashrate/)

## Europe/Germany/Berlin

- ["Bitcoin fixes this" bei Datenspuren Konferenz](https://media.ccc.de/v/ds23-260-bitcoin-fixes-this)
- [Bitwala Comeback](https://www.handelsblatt.com/finanzen/banken-versicherungen/banken/bitwala-comeback-des-insolventen-krypto-start-ups-nuri-unter-altem-namen/29396584.html)
- [ECASH HACKDAY](https://twitter.com/callebtc/status/1702686992578855333)

## Mailing Lists

### bitcoin-dev

- [Solving CoinPool high-interactivity issue with cut-through update of Taproot leaves](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-September/021969.html)
- [Actuarial System To Reduce Interactivity In N-of-N (N > 2) Multiparticipant Offchain Mechanisms](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-September/021942.html)
- [Draft BIP: OP_TXHASH and OP_CHECKTXHASHVERIFY](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-September/021975.html)

### lighting-dev

- [Sidepools For Improving Payment Reliability At Scale](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-September/004099.html)
- [Practical PTLCs, a little more concretely](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-September/004088.html)
- [Payment Splitting & Switching and its impact on Balance Discovery Attacks (preprint)](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-September/004114.html?ref=blog.lnmarkets.com&utm_source=substack&utm_medium=email)

## Pull requests

### BIPs, BOLTs and Proposals

- [bip324: Remove garbage authentication packet (breaking change) #1498](https://github.com/bitcoin/bips/pull/1498)

### Bitcoin Core

- [BIP324 integration #28331](https://github.com/bitcoin/bitcoin/pull/28331)
- [assumeutxo (2) #27596](https://github.com/bitcoin/bitcoin/pull/27596)
- [validation: fix coins disappearing mid-package evaluation #28251](https://github.com/bitcoin/bitcoin/pull/28251)
- [rpc: allow submitpackage to be called outside of regtest #27609](https://github.com/bitcoin/bitcoin/pull/27609)
- [MiniTapscript: port Miniscript to Tapscript #27255](https://github.com/bitcoin/bitcoin/pull/27255)
- [Gathering Priorities for 27.0 #28599](https://github.com/bitcoin/bitcoin/issues/28599)

### LND

- [routing: Support Pathfinding to Blinded Routes #7267](https://github.com/lightningnetwork/lnd/pull/7267)

### Eclair

- [Delegate Bitcoin Core's private key management to Eclair #2613](https://github.com/ACINQ/eclair/pull/2613)
- [Adapt max HTLC amount to balance #2703](https://github.com/ACINQ/eclair/pull/2703)

### BDK & LDK

- [Route blinding MVP #2413](https://github.com/lightningdevkit/rust-lightning/pull/2413)
- [BOLT 12 Invoice payments #2371](https://github.com/lightningdevkit/rust-lightning/pull/2371)
- [Batch funding for v1 channel establishments #2486](https://github.com/lightningdevkit/rust-lightning/pull/2486)
- [Add an option to make the success probability estimation nonlinear #2547](https://github.com/lightningdevkit/rust-lightning/pull/2547)

### Core Lightning

- [Remove developer configuration option / DEVELOPER, use --developer runtime flag #6311](https://github.com/ElementsProject/lightning/pull/6311)
