---
layout: post
title: "Socratic Seminar #41"
---

[Meetup](https://www.meetup.com/bitcoin-lab-berlin/events/mmnpbtyfcfbsb/)

Special thanks to [Wasabi Wallet](https://wasabiwallet.io/) for sponsoring food and drinks for this meetup!

## Security/CVEs/InfoSec/Research

- [Polynonce: A Tale of a Novel ECDSA Attack and Bitcoin Tears](https://research.kudelskisecurity.com/2023/03/06/polynonce-a-tale-of-a-novel-ecdsa-attack-and-bitcoin-tears/)
- [Blind signatures interactive demo](https://blindsigs.utxo.club/)
- [Two-Round Stateless Deterministic Two-Party Schnorr Signatures From Pseudorandom Correlation Functions](https://eprint.iacr.org/2023/216.pdf)
- [Flyover: A Repayment Protocol for Fast Bitcoin Transfers over Federated Pegs](https://eprint.iacr.org/2023/086.pdf)
- [From Reality Keys to Oraclize. A Deep Dive into the History of Bitcoin Oracles](https://arxiv.org/pdf/2302.07911v1.pdf)
- [Practical Security Analysis of Zero-Knowledge Proof Circuits](https://eprint.iacr.org/2023/190.pdf)
- [tlock: practical timelock encryption from threshold BLS](https://eprint.iacr.org/2023/189.pdf)
- [Going Mainstream: Cryptocurrency Narratives in Newspapers](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4368357)
- [Master Thesis: Bitcoin Network Topology Discovery Using Timing Analysis](https://repositum.tuwien.at/handle/20.500.12708/154417?mode=simple)
- [New Records in Collision Attacks on RIPEMD-160 and SHA-256](https://eprint.iacr.org/2023/285.pdf)
- [Analysis of RIPEMD-160: New Collision Attacks and Finding Characteristics with MILP](https://eprint.iacr.org/2023/277.pdf)
- [Research on Elliptic Curve Crypto Systemwith Bitcoin Curves – SECP256k1,NIST256p, NIST521p and LLL](https://journals.riverpublishers.com/index.php/JCSANDM/article/view/15085/17499)
- [Ciphertext-Policy Attribute-Based Encryption Scheme for Secure Organizations’ Bitcoin Wallet Access](https://journal.uob.edu.bh/handle/123456789/4764)
- [Exploring Unconfirmed Transactions for Effective Bitcoin Address Clustering](https://arxiv.org/pdf/2303.01012.pdf)
- [VDHLA: Variable Depth Hybrid Learning Automaton and Its Application to Defense Against the Selfish Mining Attack in Bitcoin](https://arxiv.org/pdf/2302.12096.pdf)
- [On the Sustainability of Bitcoin Partitioning Attacks](https://www.nsg.ee.ethz.ch/fileadmin/user_upload/publications/fc23-final204.pdf)

## Network Data

- [How Many Bitcoin Confirmations is Enough?](https://blog.lopp.net/how-many-bitcoin-confirmations-is-enough/)
- [USD "denominated-ness" of on-chain transactions](https://mobile.twitter.com/SteveUsingWords/status/1625482839327121408)
- [Bitcoin Mining historical Revenue per kWh](https://hashrateindex.com/blog/energy-arbitrage-analyzing-bitcoin-minings-historical-revenue-per-kwh/)

## Miscellaneous

- [Rigly.io](https://rigly.io/)
- [Seed XOR by Coldcard](https://seedxor.com/)
- [Christoph Ono's weekly updates](https://gbks.substack.com/)
- [Sats Names](https://docs.sats.id/sats-names/about)
- [c=, a new LSP by Jack Dorseys TPD](https://cequals.xyz/)
- [Bluewallet sunsetting lndhub.io](https://bluewallet.io/sunsetting-lndhub/)
- [Nostrocket](https://nostrocket.org/)
- [MDK by Block](https://www.mining.build/the-mining-development-kit-unlocking-innovation-in-bitcoin-mining/)
- [Marco Falke steps down as maintainer](https://twitter.com/MarcoFalke/status/1627987123788824576)
- [Mempool adds block audits](https://twitter.com/mempool/status/1625489545230954499)
- [PSBT.io, IFTTT for Bitcoin transaction broadcast](https://psbt.io/)
- [frozenkrill: a minimalist Bitcoin wallet focused on cold storage](https://github.com/planktonlabs/frozenkrill)
- [Hashhunt: Human Powered Bitcoin Mining](https://wp.josh.com/2023/02/17/human-powered-bitcoin-mining/)

## Europe/Germany/Berlin

- [Buchvorstellung "Die orange Pille" with Ijoma Mangold](https://www.kulturkaufhaus.de/de/veranstaltungen/detail/Buchpremiere-mit-Ijoma-Mangold-artcEvent)
- [Steuerbarkeit von Gewinnen aus der Veräußerung von verschiedenen Kryptowährungen (Bitcoin, Ether, Monero)](https://www.bundesfinanzhof.de/de/entscheidung/entscheidungen-online/detail/STRE202310057/)
- [Bachelor Thesis: Aspekte zur ertragsteuerlichen Behandlung von Kryptowährungen nach dem deutschen Steuerrecht](https://digibib.hs-nb.de/file/dbhsnb_thesis_0000002914/dbhsnb_derivate_0000003520/Bachelorarbeit-Dobberstein-2022.pdf)
- [TV-Documentation: Bitcoineros - Das digitale Gold und seine Versprechen](https://programm.ard.de/TV/Programm/Sender/?sendung=280074000888148)

## Mailing Lists

### bitcoin-dev

- [BIP for OP_VAULT continued discussion](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-March/021510.html)
- [Using service bit 24 for utreexo signaling in testnet and signet](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2023-March/021515.html)

### lighting-dev

- [Highly Available Lightning Channels](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-February/003842.html)
- [Local Reputation to Mitigate Slow Jamming](https://lists.linuxfoundation.org/pipermail/lightning-dev/2023-February/003857.html)

## Pull requests

### BIPs, BOLTs and Proposals

- [Codex32 BIP](https://github.com/apoelstra/bips/blob/2023-02--volvelles/bip-0000.mediawiki)

### Bitcoin Core

- [Signing support for Miniscript Descriptors #24149](https://github.com/bitcoin/bitcoin/pull/24149)
- [wallet: be able to specify a wallet name and passphrase to migratewallet #26595](https://github.com/bitcoin/bitcoin/pull/26595)
- [assumeutxo: background validation completion #25740](https://github.com/bitcoin/bitcoin/pull/25740)

### LND

- [signrpc: Upgrade to MuSig2 BIP draft v1.0.0rc2, add version flag to RPC #7171](https://github.com/lightningnetwork/lnd/pull/7171)
- [Pathfinding: take channel capacity into account #5988](https://github.com/lightningnetwork/lnd/issues/5988)

### Eclair

- [Add support for paying offers #2479](https://github.com/ACINQ/eclair/pull/2479)

### Core Lightning

- [Peer storage feature #5361](https://github.com/ElementsProject/lightning/pull/5361)

### Secp256k1

- [Version 0.3.0 released](https://github.com/bitcoin-core/secp256k1/blob/master/CHANGELOG.md)

### BTCPayServer

- [Fix: Payjoin wasn't always properly choosing utxo for optimal change #4600](https://github.com/btcpayserver/btcpayserver/pull/4600)

### rust-bitcoin

- [Weight prediction #1636](https://github.com/rust-bitcoin/rust-bitcoin/pull/1636)

## Newsletters

- [Bitcoin Optech](https://bitcoinops.org/)
