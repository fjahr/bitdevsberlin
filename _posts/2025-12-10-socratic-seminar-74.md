---
layout: post
title: "Socratic Seminar #74"
---

[Meetup](https://www.meetup.com/bitcoin-lab-berlin/events/312036059/)

Thanks to [Ordimint](https://ordimint.com) for sponsoring food and drinks for this meetup!


## Security/CVEs/InfoSec/Research

- [An Independent Security Audit of Bitcoin Core](https://brink.dev/blog/2025/11/19/bitcoin-core-security-audit/)
- [Hash-based Signature Schemes for Bitcoin](https://eprint.iacr.org/2025/2203.pdf)
- [Golden: Lightweight Non-Interactive Distributed Key Generation](https://eprint.iacr.org/2025/1924)
- [Payment-failure times for random Lightning paths](https://arxiv.org/abs/2511.16376)
- [When Can You Trust Bitcoin? Value-Dependent Block Confirmation to Determine Transaction Finality](https://arxiv.org/abs/2511.15421)
- [The Time to Consensus in a Blockchain: Insights into Bitcoin's "6 Blocks Rule"](https://arxiv.org/abs/2511.12687)
- [Multiple Sides of 36 Coins: Measuring Peer-to-Peer Infrastructure Across Cryptocurrencies](https://arxiv.org/abs/2511.15388)
- [Incentive Attacks in BTC: Short-Term Revenue Changes and Long-Term Efficiencies](https://arxiv.org/abs/2511.11538)
- [A spatial analysis of the use of Bitcoin as a medium of exchange](https://link.springer.com/article/10.1186/s40854-025-00871-z)
- [Bitcoin Hashrate Dynamics: Price, Revenue Correction, and Evolution - A Time-Varying Parameter SVAR Stochastic Volatility Analysis](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5786322)
- [Masterthesis: Strategische Nutzung von Bitcoin Mining in Unternehmen](https://monami.hs-mittweida.de/frontdoor/deliver/index/docId/16329/file/Masterthesis_Charlie_Fritzsche.pdf)
- [Shai Hulud Launches Second Supply-Chain Attack](https://www.aikido.dev/blog/shai-hulud-strikes-again-hitting-zapier-ensdomains)

## Network Data

- [Many connections to bitproject.io nodes?](https://bnoc.xyz/t/many-connections-to-bitproject-io-nodes/40/19)
- [>60% spy-peers connected to freshly setup node](https://bnoc.xyz/t/60-spy-peers-connected-to-freshly-setup-node/15)

## Local/Legal

- [Bitcoin und Nostr als Werkzeuge des demokratischen Widerstands](https://coinspondent.de/2025/11/18/bitcoin-und-nostr-als-werkzeuge-des-demokratischen-widerstands/)
- [Berlin Manifesto of the World Liberty Congress](https://worldlibertycongress.org/berlin-manifesto-of-the-world-liberty-congress/)
- [Bericht Libertarismus/extreme Rechte mit Roman Reher, Joana Cotar, Marc Friedrich](https://cemas.io/publikationen/freier-markt-und-kulturkampf-libertarismus/)
- [KYC: Volle Verifizierung bei Pocket](https://pocketbitcoin.com/de/blog/posts/volle-verifizierung-bei-pocket)
- [Berlin Bitcoin Mining meetup Thursday, December 11](https://www.meetup.com/bitcoin_berlin_/events/311958983/)
- [Wirecard Scandal: Fresh Leads Point to a Gambling Kingpin](https://www.tagesschau.de/investigativ/br-recherche/wirecard-marsalek-braun-calvin-ayre-102.html)
- [BTC is money](https://btcismoney.xyz/)

## Miscellaneous

- [Project 11](https://www.projecteleven.com/)
- [RawBit Tool](https://rawbit.io/)
- [Penlock](https://v1.penlock.io/en/)
- [Mempal Android App](https://github.com/aeonBTC/Mempal)
- [Miniscript Studio](https://adys.dev/miniscript)
- [BOSS Challenge: Applications open](https://bosschallenge.xyz/)
- [BNOC Forum](https://bnoc.xyz/t/why-not-use-delvingbitcoin-org-for-bnoc/23)
- [Bitcoin Core Roadmap question](https://x.com/bitschmidty/status/1986100498567499789)
- [Keymeld](https://github.com/tee8z/keymeld)
- [Quantum Doomsday Clock](https://quantumdoomclock.com/)
- [Ordiknots](https://github.com/taproot-wizards/ordiknots)

## Mailing Lists

### bitcoin-dev

- [Motion to Activate BIP 3](https://groups.google.com/g/bitcoindev/c/j4_toD-ofEc)
- [Benchmarking Bitcoin Script Evaluation for the Varops Budget (GSR)](https://groups.google.com/g/bitcoindev/c/epbDDH9MHNw/m/OUrIeSHmAAAJ)

### Delving Bitcoin

- [Consensus bug on NBitcoin: out-of-bound issue in `Remove()`](https://delvingbitcoin.org/t/consensus-bug-on-nbitcoin-out-of-bound-issue-in-remove/2120)
- [Propagation Delay and Mining Centralization: Modeling Stale Rates](https://delvingbitcoin.org/t/propagation-delay-and-mining-centralization-modeling-stale-rates/2110)
- [Disclosure: Critical vulnerabilities fixed in LND 0.19.0](https://delvingbitcoin.org/t/disclosure-critical-vulnerabilities-fixed-in-lnd-0-19-0/2145/4)

## Pull requests

### Bitcoin Core

- [Cluster mempool #33629](https://github.com/bitcoin/bitcoin/pull/33629)
- [init: completely remove -maxorphantx option #33872](https://github.com/bitcoin/bitcoin/pull/33872)
- [chainparams: remove dnsseed.bitcoin.dashjr-list-of-p2p-nodes.us #33723](https://github.com/bitcoin/bitcoin/pull/33723)

### LND

- [multi: add upfront-shutdown-address to lnd.conf. #9432](https://github.com/lightningnetwork/lnd/pull/9432)

### Core Lightning

- [Fix the long-elusive "sometimes we miss utxo spends" bug. #8735](https://github.com/ElementsProject/lightning/pull/8735)
- [Add Experimental no-MPP, Lsp-Trusts-Client LSPS2 Support #8569](https://github.com/ElementsProject/lightning/pull/8569)
- [hsmd: fix HSM sent an unknown message type error #8728](https://github.com/ElementsProject/lightning/pull/8728)

### Eclair

- [Fix reconnection to clearnet addresses via Tor #3054](https://github.com/ACINQ/eclair/pull/3054)

### BDK/rust-bitcoin & LDK/rust-lightning

- [Add support for Testnet4 #4148](http://github.com/lightningdevkit/rust-lightning/pull/4148)
- [feat(chain): add new list_ordered_canonical_txs method #2027](https://github.com/bitcoindevkit/bdk/pull/2027)
- [Enforce Trampoline Constraints (replacement) #4226](https://github.com/lightningdevkit/rust-lightning/pull/4226)

### Others

- [Electrum protocol 1.6: minimal update to get broadcast_package out](https://github.com/spesmilo/electrum-protocol/pull/6)
- [Monetization #6986](https://github.com/btcpayserver/btcpayserver/pull/6986)
