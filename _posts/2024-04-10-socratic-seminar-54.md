---
layout: post
title: "Socratic Seminar #54"
---

[Meetup](https://www.meetup.com/bitcoin-lab-berlin/events/298337257/)

Thanks to [Ordimint](https://ordimint.com) for sponsoring food and drinks for this meetup!

## Security/CVEs/InfoSec/Research

- [ViaBTC's mutated blocks without witness data](https://b10c.me/observations/10-viabtc-blocks-without-witness-data/)
- [Introducing SRI 1.0.0 - the most important milestone in our Stratum V2 journey!](https://stratumprotocol.org/blog/sri-1-0-0/)
- [ASIC Ultraboost and ASIC EnhancedBoost](https://www.ft.com/content/8aa731a0-5456-4121-a2f7-828ae90ed199)
- [Efficient and Reliable Service Detection on Bitcoin](https://orbi.uliege.be/handle/2268/314439)
- [Statistical Confidence in Mining Power Estimates for PoW Blockchains](https://arxiv.org/abs/2403.13736)
- [Bitcoin MiCA Whitepaper](https://arxiv.org/abs/2403.10583)
- [51% Attack via Difficulty Increase with a Small Quantum Miner](https://arxiv.org/abs/2403.08023)
- [First practical SHA-256 collision for 31 steps](https://twitter.com/jedisct1/status/1772647350554464448)
- [CVE-2024-3094: Timeline of the xz open source attack](https://research.swtch.com/xz-timeline)
    - [Everything I Know About the XZ Backdoor](https://boehs.org/node/everything-i-know-about-the-xz-backdoor)
    - [OSS-security post](https://www.openwall.com/lists/oss-security/2024/03/29/4)
    - [FAQ on the xz-utils backdoor](https://gist.github.com/thesamesam/223949d5a074ebc3dce9ee78baad9e27)
    - [Infographic](https://infosec.exchange/@fr0gger/112189232773640259)
- [IMF: A Primer on Bitcoin Cross-Border Flows](https://www.imf.org/-/media/Files/Publications/WP/2024/English/wpiea2024085-print-pdf.ashx)

## Miscellaneous

- [BitCan: DIY Bitcoin Seed Storage](https://bitcan.world/)
- [utxo-teleport](https://github.com/utxo-teleport/teleport-transactions) is an [implementation](https://x.com/RajarshiMaitra/status/1768623072280809841) of Chris Belcher's [coinswap](https://gist.github.com/chris-belcher/9144bd57a91c194e332fb5ca371d0964)
- [New HRF grants](https://bitcoinmagazine.com/business/human-rights-foundation-grants-500000-to-14-bitcoin-projects-worldwide)
- [Bitcoin Core Contributor Challenges](https://blog.lopp.net/bitcoin-core-contributor-challenges/)
- [Phoenixd Server](https://phoenix.acinq.co/server)
- [Laanwj's blog about CSW case](https://laanwj.github.io/2024/03/19/finally.html)
- [Mara pool funny block](https://mempool.space/de/block/0000000000000000000341cc26cda4af82cd25f7063c448772228cbf2836915b?audit=false)
- [Bitkey review](https://nunchuk.io/blog/bitkey)
- [Hedgehog](https://github.com/supertestnet/hedgehog)
- [SigBash](https://sigbash.com/)
- [BitMEXResearch: Satoshis 2014 email hack](https://blog.bitmex.com/satoshis-2014-email-hack/)
- [TwentyTwo HWW](https://twenty-two.xyz/)
- [COPA closing arguments vs CSW](https://satoshi50.com/pdf/closing.pdf)

## Network Data

- [Update on LinkingLion: Reduced activity and a statement by LionLink Networks](https://b10c.me/blog/013-one-year-update-on-linkinglion/)

## Europe/Germany/Berlin

- [EU cash cap and ban on anonymous crypto payments results in financial paternalism](https://www.patrick-breyer.de/en/eu-cash-cap-and-ban-on-anonymous-crypto-payments-results-in-financial-paternalism/)
- [Einzelfragen zur ertragsteuerrechtlichen Behandlung von virtuellen Währungen und von sonstigen Token](https://www.bundesfinanzministerium.de/Content/DE/Pressemitteilungen/Finanzpolitik/2022/05/2022-05-09-einzelfragen-zur-ertragsteuerrechtlichen-behandlung-von-virtuellen-waehrungen-und-von-sonstigen-token-bmf-schreiben.pdf?__blob=publicationFile&v=3)
- [Bitvavo will nach Deutschland expandieren](https://financefwd.com/de/bitvavo-expansion-deutschland/)

## Mailing Lists

### bitcoin-dev

- [A Free-Relay Attack Exploiting RBF Rule #6](https://gnusha.org/pi/bitcoindev/Zfg%2F6IZyA%2FiInyMx@petertodd.org/T/#u)

### Delving Bitcoin

- [BTC Lisp as an alternative to Script](https://delvingbitcoin.org/t/btc-lisp-as-an-alternative-to-script/682/1)
- [BIP324 Proxy: easy integration of v2 transport protocol for light clients (PoC)](https://delvingbitcoin.org/t/bip324-proxy-easy-integration-of-v2-transport-protocol-for-light-clients-poc/678)
- [Great Consensus Cleanup Revival](https://delvingbitcoin.org/t/great-consensus-cleanup-revival/710/1)

## Pull requests

### Bitcoin Core

- [net: support unix domain sockets for -proxy and -onion #27375](https://github.com/bitcoin/bitcoin/pull/27375)
- [p2p: Allow whitelisting manual connections #27114](https://github.com/bitcoin/bitcoin/pull/27114)
- [policy: enable sibling eviction for v3 transactions #29306](https://github.com/bitcoin/bitcoin/pull/29306)
- [wallet: track mempool conflicts with wallet transactions #27307](https://github.com/bitcoin/bitcoin/pull/27307)
- [Mempool util: Add RBF diagram checks for single chunks against clusters of size 2 #29242](https://github.com/bitcoin/bitcoin/pull/29242)

### LND

- [Probing for more reliable route fee estimation #8136](https://github.com/lightningnetwork/lnd/pull/8136)

### BDK & LDK

- [Interactive Transaction Construction #2419](https://github.com/lightningdevkit/rust-lightning/pull/2419)

### rust-bitcoin

- [Support signing taproot in psbt #2458](https://github.com/rust-bitcoin/rust-bitcoin/pull/2458)
