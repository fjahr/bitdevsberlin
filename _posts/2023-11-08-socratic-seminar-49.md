---
layout: post
title: "Socratic Seminar #49"
---

[Meetup](https://www.meetup.com/bitcoin-lab-berlin/events/295775830/)

Thanks to [Ordimint](https://ordimint.com) for sponsoring food and drinks for this meetup!

## Security/CVEs/InfoSec/Research

- [Covenants: Examining ScriptPubkeys in Bitcoin Script](https://rusty.ozlabs.org/2023/10/20/examining-scriptpubkey-in-script.html)
- [Covenants: Dealing with Amounts in Bitcoin Script](https://rusty.ozlabs.org/2023/10/22/amounts-in-script.html)
- [The Environmental Footprint of Bitcoin Mining Across the Globe: Call for Urgent Action](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2023EF003871)
- [Bitcoin Rollups Research (new content)](https://www.bitcoinrollups.io/)
- [PHD thesis: Evolving Bitcoin Custody](https://arxiv.org/abs/2310.11911)
- [Mixing Solutions in Bitcoin and Ethereum Ecosystems: A Review and Tutorial](https://arxiv.org/abs/2310.04899)
- [The Centralizing Effects of Private Order Flow on Proposer-Builder Separation](https://arxiv.org/abs/2305.19150v2)
- [Durabit: A Bitcoin-native Incentive Mechanism for Data Distribution](https://raw.githubusercontent.com/4de67a207019fd4d855ef0a188b4519c/Durabit/main/Durabit%20-%20A%20Bitcoin-native%20Incentive%20Mechanism%20for%20Data%20Distribution.pdf)
- [Drivechains: A Detailed Analysis](https://petertodd.org/2023/drivechains)
  - [Rebutal](https://twitter.com/Truthcoin/status/1712814820267802712?s=20)
- [One-time and Revocable Ring Signature with Logarithmic Size in Blockchain](https://eprint.iacr.org/2023/1633)
- [Naysayer proofs](https://eprint.iacr.org/2023/1472)

## Miscellaneous

- [Join Xmas Hardcore Bitcoin Trivia at Stammtisch](https://pad.riseup.net/p/fdP8zvtcw8dBo9ozCHpn)
- [Project Spartacus](https://www.projectspartacus.org/)
- [Meet the MDK Hashboard](https://www.mining.build/meet-the-mdk-hashboard/)
- [Opentimestamps used in elections in Guatemala](https://film.simpleproof.com/)
- [Lightspark Universal Money Address](https://www.lightspark.com/uma)
- [LinuxFoundation will stop hosting mailing lists](https://twitter.com/kanzure/status/1720083660815376832)
- [BitcoinDev.org](https://bitcoindev.org/)
- [Doppler - A lightning DSL](https://voltage.cloud/blog/bitcoin-development-platform/doppler-a-lightning-domain-specific-language/)
- [Taproot Assets on Mainnet](https://lightning.engineering/posts/2023-10-18-taproot-assets-v0.3/)
- [ANNOUNCING THE $12K NIST ELLIPTIC CURVES SEEDS BOUNTY](https://words.filippo.io/dispatches/seeds-bounty/)
- [Payjoin for a Better Bitcoin Future](https://brandonlucas.net/articles/bitcoin/payjoin)

## Europe/Germany/Berlin

- [Eurosystem proceeds to next phase of digital euro project](https://www.ecb.europa.eu/press/pr/date/2023/html/ecb.pr231018~111a014ae7.en.html)

## Mailing Lists

### bitcoin-dev

- [Ordinals BIP PR](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-October/022065.html)
- [Proposed BIP for OP_CAT](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-October/022049.html)
- [Examining ScriptPubkeys in Bitcoin Script](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-October/022031.html)

### lighting-dev

- [Full Disclosure: CVE-2023-40231 / CVE-2023-40232 / CVE-2023-40233 / CVE-2023-40234 "All your mempool are belong to us"](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-October/004122.html)
  - [Visual explanation](https://twitter.com/mononautical/status/1715736832950825224)
- [Batch exchange withdrawal to lightning requires covenants](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-October/004126.html)
- [Removing channel reserve for mobile wallet users](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-October/004136.html)

## Pull requests

### BIPs, BOLTs and Proposals

- [BOLT4: Specify max HTLC nLocktime for expiry_too_far #1086](https://github.com/lightning/bolts/pull/1086)

### Bitcoin Core

- [coinstats, assumeutxo: fix hash_serialized2 calculation #28685](https://github.com/bitcoin/bitcoin/pull/28685)
- [Make miniscript GetWitnessSize accurate for tapscript #28651](https://github.com/bitcoin/bitcoin/pull/28651)
- [v26.0 Testing #28718](https://github.com/bitcoin/bitcoin/issues/28718)
  - [Download](https://bitcoincore.org/bin/bitcoin-core-26.0/test.rc2/)

### LND

- [multi: pong enforcement #7828](https://github.com/lightningnetwork/lnd/pull/7828)

### BDK & LDK

- [Add bitcoind_rpc chain source module. #1041](https://github.com/bitcoindevkit/bdk/pull/1041)
- [More flexible fee rate estimates #2660](https://github.com/lightningdevkit/rust-lightning/pull/2660)

### Core Lightning

- [Feat/unified invoices #6421](https://github.com/ElementsProject/lightning/pull/6421)
