---
layout: post
title: "Socratic Seminar #70"
---

[Meetup](https://www.meetup.com/bitcoin-lab-berlin/events/dtbxqtyhclbrb/)

Thanks to [Ordimint](https://ordimint.com) for sponsoring food and drinks for this meetup!

## Security/CVEs/InfoSec/Research

- [RGB v0.12 consensus release](https://rgb.tech/blog/release-v0-12-consensus/)
- [Bitmex: Bitcoin Versus The IMF](https://blog.bitmex.com/bitcoin-versus-the-imf/)
- [Wrapless: The trustless lending protocol on top of Bitcoin](https://arxiv.org/abs/2507.06064)
- [BIP: Post Quantum Migration and Legacy Signature Sunset](https://github.com/jlopp/bips/blob/quantum_migration/bip-post-quantum-migration.mediawiki)
- [Glock: A new standard for verification on Bitcoin](https://www.alpenlabs.io/blog/glock-verification-on-bitcoin)
- [BitVM 3s – Garbled Circuits for Efficient Computation on Bitcoin](https://bitvm.org/bitvm3.pdf)
- [DARI report: Bring Only What You Can Carry](https://cdn.prod.website-files.com/656cd20247e4444dd911a978/6878661e609241f0a3962eb4_Bring%20Only%20What%20You%20Can%20Carry%20DARI%20Web.pdf)
- [The Post-Quantum Security of Bitcoin's Taproot as a Commitment Scheme](https://eprint.iacr.org/2025/1307)
- [Evaluating usage of the Whirlpool Bitcoin privacy protocol](https://www.dci.mit.edu/dci-news/coinjoin-timing-questions)
- [How Good Are The Widely Used Coinjoin Implementations?](https://petertodd.org/2025/coinjoin-comparison)

## Network Data

- [What Network Activity Says About Changing Face of Bitcoin Users](https://www.nydig.com/research/what-network-activity-says-about-changing-face-of-bitcoin-users)

## Europe/Germany/Berlin

- [Admin entwendet Kryptowährung in Millionenwert und bleibt vor Gericht straflos](https://www.heise.de/news/Oberlandesgericht-Virtuelle-Entwendung-von-Kryptowerten-bleibt-straflos-10484771.html)
- [Bitcoin ATMs in Berlin außer Betrieb](https://www.rbb24.de/wirtschaft/beitrag/2025/07/automaten-bitcoin-kryptowaherung-berlin-offline-betreiber.html)
- [GosuPay UG: Freiheit auf Knopfdruck: Wie ein Berliner Startup mit Bitcoin neue Wege im Zahlungsverkehr geht](https://www.the-germanz.de/freiheit-auf-knopfdruck-wie-ein-berliner-startup-mit-bitcoin-neue-wege-im-zahlungsverkehr-geht/)

## Miscellaneous

- [How secure is your Bitcoin wallet's mnemonic seed phrase?](https://bennet.org/learn/how-secure-is-your-bitcoin-wallets-mnemonic-seed-phrase/)
- [Current state of sub 1 sat/vbyte summer](https://x.com/mononautical/status/1947530080475091159)
- [Block: Policies to Unlock Bitcoin as Everyday Money](https://block.xyz/inside/policies-to-unlock-bitcoin-as-everyday-money)
- [Payjoin Foundation announcement](https://insider.btcpp.dev/p/the-payjoin-foundation-is-announced)
- [Simplicity launch](https://simplicity-lang.org/)
- [SimplicityHL](https://docs.simplicity-lang.org/)
- [LaBitBu](https://github.com/rot13maxi/awesome-labitbu)
- [Kyoto - New light client ](https://github.com/2140-dev/kyoto)
- [Samourai Wallet Developers Plead Guilty to Conspiring to Operate an Unlicensed Money Transmitting Business](https://bitcoinmagazine.com/news/samourai-wallet-developers-plead-guilty)
- [Tornado Cash Trial Concludes: Roman Storm Found Guilty on One of Three Counts](https://bitcoinmagazine.com/news/tornado-cash-trial-concludes-roman-storm-found-guilty-of-one-of-three-counts)
- [Adios, Expiry: Rethinking Liveness and Liquidity in Arkade](https://blog.arklabs.xyz/adios-expiry-rethinking-liveness-and-liquidity-in-arkade/)
- [PkgZap](https://pkgzap.albylabs.com/)
- [Qubic Overtakes Monero’s Hash Rate in Live “51% Takeover Demo”](https://qubic.org/pr/qubic-overtakes-monero-s-hash-rate-in-live-51-takeover-demo)

## Mailing Lists

### bitcoin-dev

- [Utreexo BIPs](https://mailing-list.bitcoindevs.xyz/bitcoindev/3452b63c-ff2b-4dd9-90ee-83fd9cedcf4an@googlegroups.com/)
- [A Taproot-native (re-)bindable transaction bundle proposal](https://mailing-list.bitcoindevs.xyz/bitcoindev/26b96fb1-d916-474a-bd23-920becc3412cn@googlegroups.com/)

### Delving Bitcoin

- [Disclosure: LND gossip_timestamp_filter DoS](https://delvingbitcoin.org/t/disclosure-lnd-gossip-timestamp-filter-dos/1859)
- [Sharing block templates](https://delvingbitcoin.org/t/sharing-block-templates/1906)
- [Changing the minimum relay feerate](https://delvingbitcoin.org/t/changing-the-minimum-relay-feerate/1886)
- [Chain Code Delegation: Private Access Control for Bitcoin Keys](https://delvingbitcoin.org/t/chain-code-delegation-private-access-control-for-bitcoin-keys/1837)

## Pull requests

### Bitcoin Core

- [policy: make pathological transactions packed with legacy sigops non-standard #32521](https://github.com/bitcoin/bitcoin/pull/32521)
- [p2p: improve TxOrphanage denial of service bounds #31829](https://github.com/bitcoin/bitcoin/pull/31829)
- [descriptors: MuSig2 #31244](https://github.com/bitcoin/bitcoin/pull/31244)
- [log: Mitigate disk filling attacks by rate limiting LogPrintf, LogInfo, LogWarning, LogError #32604](https://github.com/bitcoin/bitcoin/pull/32604)
- [cluster mempool: add TxGraph reorg functionality #31553](https://github.com/bitcoin/bitcoin/pull/31553)

### LND

- [Add deletecanceledinvoice RPC call #9625](https://github.com/lightningnetwork/lnd/pull/9625)

### Core Lightning

- [logs: A basic javascript log viewer #7725](https://github.com/ElementsProject/lightning/pull/7725)

### Eclair

- [Endorse htlc and local reputation #2716](https://github.com/ACINQ/eclair/pull/2716)

### BDK/rust-bitcoin & LDK/rust-lightning

- [Static invoice server #3628](https://github.com/lightningdevkit/rust-lightning/pull/3628)
- [LSPS5 implementation #3662](https://github.com/lightningdevkit/rust-lightning/pull/3662)
- [Add Shared Input support in interactive TX construction #3842](https://github.com/lightningdevkit/rust-lightning/pull/3842)

### Others

- [BTCPayServer LSP Plugin](https://github.com/MegalithicBTC/BTCPayserver-LSPS1)
