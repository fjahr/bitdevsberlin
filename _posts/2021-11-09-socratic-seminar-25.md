---
layout: post
title: "Socratic Seminar #25"
---

[Meetup](https://www.meetup.com/de-DE/Bitcoin-Lab-Berlin/events/rkzdqsyccpbmb/)

## Security/CVEs/InfoSec/Research

- [Blockchain Analysis of the Bitcoin market](https://www.nber.org/system/files/working_papers/w29396/w29396.pdf)
- [Kazakhstan to restrict crypto miners amid power shortages](https://eurasianet.org/kazakhstan-to-restrict-crypto-miners-amid-power-shortages)
- [Bank of Spain: The role of cryptoassets as legal tender: the example of El Salvador ](https://repositorio.bde.es/handle/123456789/19051)
- [Where is the Light(ning) in the Taproot Dawn? Unveiling the Bitcoin Lightning (IP) Network](https://orbi.uliege.be/handle/2268/264663)
- [Metal Bitcoin Seed Storage Stress Test (Round V)](https://blog.lopp.net/metal-bitcoin-seed-storage-stress-tests-round-v/)
- [Sleepy  Channels:  Bitcoin-Compatible  Bi-directional  Payment  Channels  without  Watchtowers](https://eprint.iacr.org/2021/1445)
- [Estimation of Ransomware Payments in Bitcoin Ecosystem](https://www.researchgate.net/profile/Ali-H-Raheem/publication/355351795_Estimation_of_Ransomware_Payments_in_Bitcoin_Ecosystem/links/616b5ff0039ba2684452097a/Estimation-of-Ransomware-Payments-in-Bitcoin-Ecosystem.pdf)
- [Analysis and Patterns of Unknown Transactions in Bitcoin](https://cri-lab.net/wp-content/uploads/2021/10/unk_tx_Bitcoin_IEEE_Blockchain2021.pdf)
- [Analysis of Decentralized Mixing Services in the Greater Bitcoin Ecosystem](https://repositum.tuwien.at/handle/20.500.12708/18576)
- [How much does it cost to destroy Bitcoin?](https://gist.github.com/fernandonm/ef9721bacf7284e039caf39ba2a07258)
- [Elligator Squared for BN-like curves](https://github.com/sipa/writeups/tree/main/elligator-square-for-bn)
- [Preventing Channel Jamming](https://blog.bitmex.com/preventing-channel-jamming/)

## Miscellaneous

- [Jonas Schnelli steps down as Bitcoin Core maintainer and dev](https://twitter.com/_jonasschnelli_/status/1451268520159875080)
- [Blockstream Sponsors Federated E-Cash as a Bitcoin Scaling Technology](https://medium.com/blockstream/blockstream-sponsors-federated-e-cash-as-a-bitcoin-scaling-technology-637ba05de7b3)
- [Fedimint Website](https://fedimint.org/)
- [Umbrel raises 3M$](https://blog.getumbrel.com/seed-6d09aa08f8ac)
- [Effortlessly create Lightning Channels with Flow](https://blog.voltage.cloud/introducing-flow/)
- [Bug in Eclair enabled hack of lntxbot](https://twitter.com/lntxbot/status/1457054454251917314)
- [libbitcoinkernel status](https://twitter.com/carl_dong/status/1448081732385771522)
- [Schnorr Wizardry Cheatsheet](https://github.com/t-bast/lightning-docs/blob/master/schnorr.md)
- [Liquid and Taproot Activation](https://www.erisian.com.au/wordpress/2021/10/26/liquid-and-taproot-activation)
- [BIP70 vs. LNURL](https://xn--57h.bigsun.xyz/lnurlpay-vs-bip70.txt)

## Europe/Germany/Berlin

- [NRW versteigert beschlagnahmte Bitcoin](https://www.justiz-auktion.de/categories.php?parent=1875)

## Mailing Lists

### bitcoin-dev

- [death to the mempool, long live the mempool](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2021-October/019572.html)
- [Taproot testnet wallet](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2021-October/019533.html)
- [On the regularity of soft forks](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2021-October/019535.html)

### lighting-dev

- [LN Summit 2021 Notes & Summary/Commentary](https://lists.linuxfoundation.org/pipermail/lightning-dev/2021-November/003336.html)
- [Neutrino, Taproot, and The Evolution of BiPs 157/158](https://groups.google.com/a/lightning.engineering/g/lnd/c/CE2EslTiqW4)
- [Removing lnd's source code from the Lightning specs repository (Resolution)](https://lists.linuxfoundation.org/pipermail/lightning-dev/2021-November/003337.html)
- [A Mobile Lightning User Goes to Pay a Mobile Lightning User...](https://lists.linuxfoundation.org/pipermail/lightning-dev/2021-October/003307.html)

## Pull requests

### BIPs, BOLTs and Proposals

- [Peers need to check each other's dust limit #894](https://github.com/lightning/bolts/pull/894)

### Bitcoin Core

- [Make AddrMan support multiple ports per IP #23306](https://github.com/bitcoin/bitcoin/pull/23306)
- [Make descriptor wallets by default](https://github.com/bitcoin/bitcoin/pull/23002)
- [Re-include RBF replacement txs in fee estimation #22539](https://github.com/bitcoin/bitcoin/pull/22539)
- [p2p: Use legacy relaying to download blocks in blocks-only mode #22340](https://github.com/bitcoin/bitcoin/pull/22340)
- [Remove -rescan startup parameter #23123](https://github.com/bitcoin/bitcoin/pull/23123)
- [Allow fundrawtransaction and walletcreatefundedpsbt to take external inputs #17211](https://github.com/bitcoin/bitcoin/pull/17211)

### LND

- [lnrpc+peer: custom peer messages #5346](https://github.com/lightningnetwork/lnd/pull/5346)
- [Support remote signing over RPC #5689](https://github.com/lightningnetwork/lnd/pull/5689)
- [Allow skipping PsbtFinalize step during channel funding to support external broadcast #5363](https://github.com/lightningnetwork/lnd/pull/5363)

### c-lightning

- [Pay: take channel capacity into account for route selection #4771](https://github.com/ElementsProject/lightning/pull/4771)
- [experimental-websocket-port: option to accept websocket connections on additional port. #4685](https://github.com/ElementsProject/lightning/pull/4685)
- [Add htlc dust ceiling #4837](https://github.com/ElementsProject/lightning/pull/4837)

### Eclair

- [Configure dust in flight threshold #1985](https://github.com/ACINQ/eclair/pull/1985)
- [Additional parameters for findroute* API calls #1969](https://github.com/ACINQ/eclair/pull/1969)

### PTCPayServer

- [Add Lightning payout support #2517](https://github.com/btcpayserver/btcpayserver/pull/2517)
- [LNURL Payment Method Support #2897](https://github.com/btcpayserver/btcpayserver/pull/2897)

### rust-bitcoin

- [Taproot P2TR address #563](https://github.com/rust-bitcoin/rust-bitcoin/pull/563)
- [Add OP_CHECKSIGADD and OP_SUCCESSxxx #644](https://github.com/rust-bitcoin/rust-bitcoin/pull/644)

## Newsletters

- [Bitcoin Optech #170](https://bitcoinops.org/en/newsletters/2021/10/13/)
- [Bitcoin Optech #171](https://bitcoinops.org/en/newsletters/2021/10/20/)
- [Bitcoin Optech #172](https://bitcoinops.org/en/newsletters/2021/10/27/)
- [Bitcoin Optech #173](https://bitcoinops.org/en/newsletters/2021/11/03/)
