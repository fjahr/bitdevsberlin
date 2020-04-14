---
layout: post
title: "Socratic Seminar #6"
---

[Meetup](https://www.meetup.com/Bitcoin-Lab-Berlin/events/267904131/)

## Mailing Lists and Bitcoin Optech

### Mailing Lists

#### bitcoin-dev

- [Statechain Implementations](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2020-March/017714.html)
- [Overview of anti-covert-channel signing techniques](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2020-March/017667.html)
- [RFC: Kicking BIP-322 (message signing) into motion](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2020-March/017668.html)
- [Hash function requirements for Taproot](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2020-March/017670.html)
- [Mitigating Differential Power Analysis in BIP-340](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2020-March/017709.html)

#### lightning-dev

- [Blind paths revisited](https://lists.linuxfoundation.org/pipermail/lightning-dev/2020-March/002587.html)
- [Proof-of-closure as griefing attack mitigation](https://lists.linuxfoundation.org/pipermail/lightning-dev/2020-April/002608.html)
- [Superbolt Proposal - a professionally run LN subset delivering superior UX](https://lists.linuxfoundation.org/pipermail/lightning-dev/2020-March/002575.html)
- [Anchor Outputs Spec & Implementation Progress](https://lists.linuxfoundation.org/pipermail/lightning-dev/2020-March/002607.html)
- [BOLT 13(?): WatchTower protocol](https://lists.linuxfoundation.org/pipermail/lightning-dev/2020-March/002586.html)

### Optech

- [Newsletter #88](https://bitcoinops.org/en/newsletters/2020/03/11/)
- [Newsletter #89](https://bitcoinops.org/en/newsletters/2020/03/18/)
- [Newsletter #90](https://bitcoinops.org/en/newsletters/2020/03/25/)
- [Newsletter #91](https://bitcoinops.org/en/newsletters/2020/04/01/)
- [Newsletter #92](https://bitcoinops.org/en/newsletters/2020/04/08/)

## Network Data

- [Asicboost Block Explorer](https://asicboost.dance/)
- [Bitcoin Cash’s Halving Was Dull](https://www.coindesk.com/bitcoin-cash-halving-was-dull-bitcoins-may-be-much-the-same)
- [Bitcoin/Bcash PoW Speed](https://fork.lol/pow/speed)

## CVEs and Research

### Research

- [Islamic approach toward purification of transaction with cryptocurrency](http://www.jatit.org/volumes/Vol98No6/12Vol98No6.pdf)
- [SPECIAL SITUATION REPORT - PlusToken Issue 2](https://research.oxt.me/special-situation-report/2/preview)
- [Schnorrless Scriptless Scripts](https://joinmarket.me/blog/blog/schnorrless-scriptless-scripts/)

### InfoSec

- [Covid19 Contact tracing using BTLE in iOS and Android](https://www.apple.com/newsroom/2020/04/apple-and-google-partner-on-covid-19-contact-tracing-technology/)
- [AMD processors from 2011 to 2019 vulnerable to two new attacks](https://www.zdnet.com/article/amd-processors-from-2011-to-2019-vulnerable-to-two-new-attacks/)
- [Trrespass](https://www.vusec.net/projects/trrespass/)
- [Bisq Trading Halted](https://bisq.community/t/trading-halted-until-v1-3-0-hotfix/9208)
- [Warning — Two Unpatched Critical 0-Day RCE Flaws Affect All Windows Versions](https://thehackernews.com/2020/03/windows-adobe-font-vulnerability.html)
- [Intel x86 Root of Trust: loss of trust](http://blog.ptsecurity.com/2020/03/intelx86-root-of-trust-loss-of-trust.html)
- [Zoom Security](https://nymag.com/intelligencer/2020/04/the-zoom-app-has-a-lot-of-security-problems.html)
- [Phish of GoDaddy Employee Jeopardized Escrow.com, Among Others](https://krebsonsecurity.com/2020/03/phish-of-godaddy-employee-jeopardized-escrow-com-among-others/)

## Pull Requests and repo updates

### Bitcoin Core

- [Add ChainstateManager, remove BlockManager global #17737](https://github.com/bitcoin/bitcoin/pull/17737)
- [descriptors: improve descriptor cache and cache xpubs #18204](https://github.com/bitcoin/bitcoin/pull/18204)
- [wallet: Pass in transactions and messages for signing instead of exporting the private keys #18115](https://github.com/bitcoin/bitcoin/pull/18115)
- [Abstract out script execution out of VerifyWitnessProgram() #18002](https://github.com/bitcoin/bitcoin/pull/18002)
- [O(1) OP_IF/NOTIF/ELSE/ENDIF script implementation #16902](https://github.com/bitcoin/bitcoin/pull/16902)
- [A Document About Native Descriptor Wallets](https://gist.github.com/achow101/94d889715afd49181f8efdca1f9faa25)

### libsecp

- [Constant Time Violations Tests](https://twitter.com/n1ckler/status/1242538168743874561)

### eclair

- [Harden requirements on htlc-minimum-msat #1339](https://github.com/ACINQ/eclair/pull/1339)
- [Funder reserve for future fee increase #1319](https://github.com/ACINQ/eclair/pull/1319)
- [Support additional TLV records in SendPayentRequest #1367](https://github.com/ACINQ/eclair/pull/1367)

### c-lightning

- [Wumbo channel support #3612](https://github.com/ElementsProject/lightning/pull/3612)
- [Onion messages (EXPERIMENTAL) #3600](https://github.com/ElementsProject/lightning/pull/3600)

### lnd

- [wallet: PSBT channel funding #4079](https://github.com/lightningnetwork/lnd/pull/4079)
- [MPP: Enable MultiPathPayments for payment lifecycle #3970](https://github.com/lightningnetwork/lnd/pull/3970)
- [peers: Track errors across connections #4051](https://github.com/lightningnetwork/lnd/pull/4051)
- [doc: add Operational Safety Guidelines document #3963](https://github.com/lightningnetwork/lnd/pull/3963)
- [anchor: pluggable anchor commitments #3821](https://github.com/lightningnetwork/lnd/pull/3821)
- [watchtower: automatically create tor hidden service if enabled#4087](https://github.com/lightningnetwork/lnd/pull/4087)

### Joinmarket

- [WIP: Fidelity bond wallets #544](https://github.com/JoinMarket-Org/joinmarket-clientserver/pull/544)

## Releases

- [Bitcoin Core v0.19.1](https://github.com/bitcoin/bitcoin/blob/master/doc/release-notes/release-notes-0.19.1.md)
- [Bitcoin Core v0.20.0rc1](https://github.com/bitcoin/bitcoin/releases/tag/v0.20.0rc1)
- [bitcoin-s v0.3.0](https://github.com/bitcoin-s/bitcoin-s/releases/tag/v0.3.0)
- [Eclair v0.3.4](https://github.com/ACINQ/eclair/releases/tag/v0.3.4)

## Events

- [MIT Bitcoin Expo 2020 Videos](https://www.youtube.com/user/MITBitcoinClub/playlists)
- [First VR Socratic](https://www.pscp.tv/w/1ynKOpzzPZWGR)
- Bitcoin Halving around May 12: https://www.bitcoinhalving.com/
  - [21 hour live stream](https://www.bitcoinhalving.com/21-hour-bitcoin-halving-live-stream)jG

## Miscellaneous

- [Bitcoin Vaults](https://github.com/kanzure/python-vaults)
- [BitMEX: Who funds Bitcoin development?](https://blog.bitmex.com/who-funds-bitcoin-development/)
- [Announcing Faraday: Tame your Lightning Node with Close Recommendations](https://lightning.engineering/posts/2020-04-02-faraday/)
- [Lightning Polar v1.0 and Website](https://lightningpolar.com/)
- [Bitcoin Security Debate](https://podcasts.apple.com/us/podcast/dan-held-and-paul-sztorc-debating-bitcoins-security/id1438148082?i=1000470652406)
- [Coinbase rolls out transaction batching](https://blog.coinbase.com/coinbase-rolls-out-bitcoin-transaction-batching-5f6d09b8b045)
- [MakerDAO Disaster](https://www.coindesk.com/defi-leader-makerdao-weighs-emergency-shutdown-following-eth-price-drop)
- [How we recovered over $300K of Bitcoin](https://reperiendi.wordpress.com/2020/04/03/how-i-recovered-over-300k-of-bitcoin/)
- [Lightning Watchtower implementation: Eye of Satoshi](https://twitter.com/sr_gi/status/1241085178971328512)
- [21 Million Bitcoins to Rule all Sidechains: The Perpetual One-way Peg](https://medium.com/@RubenSomsen/21-million-bitcoins-to-rule-all-sidechains-the-perpetual-one-way-peg-96cb2f8ac302)
- [c-lightning Plugins Talk](https://www.youtube.com/watch?v=DF11qzBGmCs)
- [Wasabi Research Club](https://www.youtube.com/watch?v=Uf-EnLWawAE)
- [Your ASIC is Probably Mispriced](https://medium.com/@aviv.yaish/your-asic-is-probably-mispriced-12b5c8daf437)
- [LSAT: Authentication and Payments for the Lightning-Native Web](https://lightning.engineering/posts/2020-03-30-lsat/)
- [Chaincode Podcast: Matt Corallo and Compact Blocks/FIBRE](https://podcast.chaincode.com/2020/03/12/matt-corallo-6.html)
- [Chaincode Podcast: Nadav Kohen and Payment Points](https://podcast.chaincode.com/2020/03/30/nadav-cohen-7.html)
- [Samourai : Whirlpool CoinJoin Stats](https://docs.google.com/spreadsheets/d/e/2PACX-1vSq7Z_5bmXCBljAzGCd89ZZa4yicBPrh7DQ_IF2SZfyCrNaAIMeXeyUv2X5a2m1yQKhWSiA367jQpux/pubhtml?gid=0&single=true)
- [Stephan Livera Podcast: GLEB NAUMENKO – ERLAY BITCOIN TRANSACTION RELAY](https://stephanlivera.com/episode/164/)
- [Potzblitz Lightning Talk](https://wiki.fulmo.org/wiki/Potzblitz)
- [Zap Android](https://twitter.com/ln_zap/status/1249744912905576448)
- [Simplicity: Jets Release](https://medium.com/blockstream/simplicity-jets-release-803db10fd589 )

## Germany/ Europe

- [BITKOM wants Bitcoin/Crypto regulation instead of just guidelines in Europe](https://www.bitkom.org/sites/default/files/2020-03/bitkom_antworten_zur_eu_krypto-asset-konsultation_20200318.pdf)
- [New Bafin "Guidelines on applications for authorisation for crypto custody business"](https://www.bafin.de/SharedDocs/Veroeffentlichungen/EN/Merkblatt/BA/mb_Hinweise_zum_Erlaubnisantrag_fuer_das_Kryptoverwahrgeschaeft_en.html)
- [Berlin Bitcoin Mining virtual Meetup on Thursday, April 16](https://www.meetup.com/de-DE/Cryptocurrency-Mining-Group/events/270013756/)
