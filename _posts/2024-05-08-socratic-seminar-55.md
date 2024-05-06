---
layout: post
title: "Socratic Seminar #55"
---

[Meetup](https://www.meetup.com/bitcoin-lab-berlin/events/298337262/)

Thanks to [Ordimint](https://ordimint.com) for sponsoring food and drinks for this meetup!

## Security/CVEs/InfoSec/Research

- [Bitcoin Core 27.0 Release notes](https://github.com/bitcoin/bitcoin/blob/v27.0/doc/release-notes.md)
- [Stop calling it MEV](https://bluematt.bitcoin.ninja/2024/04/16/stop-calling-it-mev/)
- [Bulletproofs++ review for Monero](https://github.com/cypherstack/bppp-review/releases/tag/final)
- [BitVM2](https://bitvm.org/bitvm2)
- [Efficient Linkable Ring Signatures: New Framework and Post-Quantum Instantiations](https://eprint.iacr.org/2024/553)
- [SQIAsignHD: SQIsignHD Adaptor Signature](https://eprint.iacr.org/2024/561)

## Miscellaneous

- [Virtoshi: API for simulating/dry-run Bitcoin transactions](https://virtoshi.com/)
- [Bitcoind 27 breaks LND](https://twitter.com/roasbeef/status/1781086945986404559)
- [AJ Towns: Team slow and steady](https://www.erisian.com.au/wordpress/2024/04/20/team-slow-and-steady)
- [Block sends 3nm mining chip design to foundry](https://www.mining.build/latest-updates-3nm-system/)
- [Microstrategy DID BTC Spec](https://microstrategy.github.io/did-btc-spec/)
- [Bitcoin Core Dev Tech Meeting Transcripts](https://btctranscripts.com/bitcoin-core-dev-tech/2024-04/)
- [WTFhappenedinfeb2023.com](https://wtfhappenedinfeb2023.com/)
- [CatVM](https://catvm.org/catvm.pdf)
- [Open Source Miners](https://opensourceminers.org/)
- [BOLT12 has arrived](https://lightningdevkit.org/blog/bolt12-has-arrived/)
- [SafetyNet](https://wizardsardine.com/blog/safetynet/)
- [CISA Research Website](https://cisaresearch.org/)
- [FBI probed bitcoin core developer event linked to Luke Dashjr’s BTC hack](https://www.theblock.co/amp/post/287939/fbi-luke-dashjr-btc-hack)
- [Samourai Arrests and fallout](https://www.justice.gov/usao-sdny/pr/founders-and-ceo-cryptocurrency-mixing-service-arrested-and-charged-money-laundering)
    - [Wasabi shuts down coordinator](https://twitter.com/wasabiwallet/status/1786083838415769673)
    - [Phoenix withdraws from US](https://twitter.com/acinq_co/status/1783878735168507972)

## Network Data

- [Many miners using same custodian?](https://twitter.com/mononautical/status/1777686545715089605)
- [Many miners using same block template?](https://twitter.com/0xB10C/status/1780611768081121700)
- [The Halving](https://mempool.space/block/0000000000000000000320283a032748cef8227873ff4872689bf23f1cda83a5)

## Mailing Lists

### bitcoin-dev

- [Testnet reset discussion](https://gnusha.org/pi/bitcoindev/CADL_X_eXjbRFROuJU0b336vPVy5Q2RJvhcx64NSNPH-3fDCUfw@mail.gmail.com/#r)

### Delving Bitcoin

- [Research into the effects of a cluster size limited mempool in 2023](https://delvingbitcoin.org/t/research-into-the-effects-of-a-cluster-size-limited-mempool-in-2023/794)
- [Second Look at Weak Blocks](https://delvingbitcoin.org/t/second-look-at-weak-blocks/805)
- [Exploding Keys - Covenant construction](https://delvingbitcoin.org/t/exploding-keys-covenant-construction/832/2)

## Pull requests

### BIPs, BOLTs and Proposals

- [BIP2: update BIP editors](https://github.com/bitcoin/bips/commit/fa95e343886ee28e2c10b5bcbd93e15441bf55a4)
- [BIP 331: Ancestor Package Relay](https://github.com/bitcoin/bips/blob/master/bip-0331.mediawiki)
- [Opcode Restauration BIP draft](https://github.com/rustyrussell/bips/commit/c2f268e83031b9b67e798c5c72a1171bfc463d1f)

### Bitcoin Core

- [refactor: Use our own implementation of urlDecode #29904](https://github.com/bitcoin/bitcoin/pull/29904)
- [p2p: opportunistically accept 1-parent-1-child packages #28970](https://github.com/bitcoin/bitcoin/pull/28970)
- [net: Decrease nMaxIPs when learning from DNS seeds #29850](https://github.com/bitcoin/bitcoin/pull/29850)
- [wallet: Add createwalletdescriptor and gethdkeys RPCs for adding new automatically generated descriptors #29130](https://github.com/bitcoin/bitcoin/pull/29130)
- [Remove libbitcoinconsensus #29648](https://github.com/bitcoin/bitcoin/pull/29648)

### LND

- [Support Forwarding of Blinded Payments #8160](https://github.com/lightningnetwork/lnd/pull/8160)
- [htlcswitch: add inbound routing fees receive support #6703](https://github.com/lightningnetwork/lnd/pull/6703)
- [coin select: add coin selection strategy option to all on-chain RPCs #8515](https://github.com/lightningnetwork/lnd/pull/8515)

### Eclair

- [Update Bitcoin Core to v26.1 #2851](https://github.com/ACINQ/eclair/pull/2851)

### BDK & LDK

- [ChannelManager Documentation](https://github.com/lightningdevkit/rust-lightning/pull/2704)

### Core Lightning

- [Fetch block from a peer if we don't have it #7240](https://github.com/ElementsProject/lightning/pull/7240)
