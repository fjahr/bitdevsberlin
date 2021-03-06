---
layout: post
title: "Socratic Seminar #2"
---

[Meetup](https://www.meetup.com/Bitcoin-Lab-Berlin/events/266777776/)

Special thanks to Fulmo and c-base for the event space.

Most of the following links were taken from the [BitDevs NYC Socratic Semainar #99](https://bitdevs.org/2019-12-03-socratic-seminar-99).

## Mailing Lists and Bitcoin Optech

#### Mailing Lists

##### bitcoin-dev

- [Composable MuSig](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2019-November/017493.html)
- [BIP OP_CHECKTEMPLATEVERIFY](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2019-November/017494.html)
  - [utxos.org](https://utxos.org)
  - [BIP draft](https://github.com/JeremyRubin/bips/blob/ctv/bip-ctv.mediawiki)
- [Signing CHECKSIG position in Tapscript](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2019-November/017495.html)

##### lightning-dev

- [[DRAFT] BOLT 13(?): WatchTower protocol](https://lists.linuxfoundation.org/pipermail/lightning-dev/2019-November/002350.html)

#### Optech

- [Newsletter #73](https://bitcoinops.org/en/newsletters/2019/11/20/)
- [Newsletter #74](https://bitcoinops.org/en/newsletters/2019/11/27/)
- [Newsletter #75](https://bitcoinops.org/en/newsletters/2019/12/04/)
- [Newsletter #76](https://bitcoinops.org/en/newsletters/2019/12/11/)

## Network Data

- [Announcing txstats.com](https://blog.bitmex.com/announcing-txstats-com/)

## CVEs and Research

#### Research

- [A Look at Innovation in Bitcoin’s Technology Stack](https://medium.com/digitalassetresearch/a-look-at-innovation-in-bitcoins-technology-stack-7edf877eab14)
- [Bitcoin's Initial Block Download](https://blog.bitmex.com/bitcoins-initial-block-download/)
- [Insecure Shortcuts in MuSig](https://medium.com/blockstream/insecure-shortcuts-in-musig-2ad0d38a97da)
- [Refresh When You Wake Up: Proactive Threshold Wallets with Oﬄine Devices](https://eprint.iacr.org/2019/1328.pdf)
  - [blog post](https://medium.com/zengo/refresh-when-you-wake-up-proactive-threshold-wallets-with-offline-devices-5e849e9d4c29)

#### InfoSec

- [A ransom attack on Coldcard's change and keypath verification](https://medium.com/shiftcrypto/a-ransom-attack-on-coldcards-change-and-keypath-verification-f3c71461624a)
- [Details of the multisig change address issue and its mitigation (trezor)](https://blog.trezor.io/details-of-the-multisig-change-address-issue-and-its-mitigation-6370ad73ed2a)
- [CLI binaries available on getmonero.org compromised](https://github.com/monero-project/monero/issues/6151)
- [TPM-FAIL: TPM meets Timing and Lattice Attacks](http://tpm.fail/tpmfail.pdf)
- [The Role of Dandelion Routing in “Breaking Mimblewimble’s Privacy Model”](https://medium.com/@gfanti/the-role-of-dandelion-routing-in-breaking-mimblewimbles-privacy-model-42e524d0187e)

## Pull Requests and repo updates

#### Bitcoin Core

- [Bitcoin Core v0.19.0.1 released](https://bitcoincore.org/en/releases/0.19.0.1/)
- [Remove OpenSSL](https://github.com/bitcoin/bitcoin/pull/17265)
  - see also [Use Hal's optimized secp256k1 verifier](https://github.com/bitcoin/bitcoin/pull/2061#issuecomment-11075455)
  - see also [Replace OpenSSL hash functions with built-in implementations](https://github.com/bitcoin/bitcoin/pull/4100)
  - see also [libsecp256k1 integration](https://github.com/bitcoin/bitcoin/pull/4312)
  - see also [Replace OpenSSL AES with ctaes-based version](https://github.com/bitcoin/bitcoin/pull/7689)
  - see also [Switch all RNG code to the built-in PRNG](https://github.com/bitcoin/bitcoin/pull/14955)
- [gui: create PSBT with watch-only wallet](https://github.com/bitcoin/bitcoin/pull/16944)
- [Enable BnB coin selection for preset inputs and subtract fee from outputs](https://github.com/bitcoin/bitcoin/pull/17290)

#### c-lightning
- [Never follow bitcoind backwards](https://github.com/ElementsProject/lightning/pull/3274)
- [New `sensitive_command` RPC hook](https://github.com/ElementsProject/lightning/pull/2925)

#### lnd

- [v0.8.1-beta released](https://github.com/lightningnetwork/lnd/releases/tag/v0.8.1-beta)
- Circular Payments
  - [Allow payment to self](https://github.com/lightningnetwork/lnd/pull/3736)
  - [Last hop restriction](https://github.com/lightningnetwork/lnd/pull/3739)
- Millisatoshis Support
  - [Add msat fields](https://github.com/lightningnetwork/lnd/pull/3706)
  - [Add msat fields to invoices](https://github.com/lightningnetwork/lnd/pull/3729)

#### Joinmarket

- [Joinmarket 0.6.0](https://github.com/JoinMarket-Org/joinmarket-clientserver/blob/master/docs/release-notes/release-notes-0.6.0.md)

## Miscellaneous

- [A Look at Innovation in Bitcoins Technology Stack](https://medium.com/digitalassetresearch/a-look-at-innovation-in-bitcoins-technology-stack-7edf877eab14)
- [Austin Bitcoin Developers Socratic Seminar 4 Transcript](https://diyhpl.us/wiki/transcripts/austin-bitcoin-developers/2019-11-19-socratic-seminar-4/)
- [Lightning on Mobile: Neutrino in the Palm of your Hand](https://blog.lightning.engineering/posts/2019/11/21/mobile-lnd.html)
- [lnd Mailing List](https://twitter.com/roasbeef/status/1197286544555380736)
- [on-chain hashrate derivatives using timelocks](https://twitter.com/somsenruben/status/1194993848180568064)
- [Stratum v2](https://stratumprotocol.org/)
  - [AMA](https://www.reddit.com/r/Bitcoin/comments/dz1mgp/ama_bitcoin_mining_stratum_v2_we_are_braiins_the/)
- [LNURL](https://github.com/fiatjaf/awesome-lnurl)
  - [Spec](https://github.com/btcontract/lnurl-rfc/blob/master/spec.md)
  - [Playground](https://lnurl.bigsun.xyz/)
- [Lightning This Week 605,954](https://medium.com/zebedee-engineering/lightning-this-week-605-954-23403a1f9737)
- [LNDroid Daemon](https://github.com/lndroid/lndroid-daemon)
- [Bolt-A-Thon2](https://boltathon.com/)
  - [Winners and Demos](https://twitter.com/Boltathon/status/1204091422065885184)
  - [Workshops](https://www.youtube.com/playlist?list=PLC_AgDAr0m6Rdl7emeEWR2JuJ8TQ-en4X)
- [BitFinex adds LN Support](https://twitter.com/paoloardoino/status/1201590067451613185)
- [STRIKE Virtual Hackathon Winners](https://medium.com/radartech/announcing-strike-hackathon-winners-5a4895708746)
- [Stakwork Residency](https://residency.stakwork.com/)

## Europe/Germany/Berlin

- [Boerse Stuttgart Digital Exchange (BSDEX)](https://www.bsdex.de/en/)
- [Deutsche Bank Research: Image 2030 study](https://www.dbresearch.com/PROD/RPS_EN-PROD/PROD0000000000503196/Imagine_2030.pdf)
- [Law change: EU Money Laundering Directive](https://www.bundesrat.de/SharedDocs/drucksachen/2019/0501-0600/598-19.pdf?__blob=publicationFile&v=1)
- [Handelsblatt: SolarisBank wants to start Bitcoin custody](https://www.handelsblatt.com/finanzen/banken-versicherungen/digitalbank-solarisbank-startet-bitcoin-verwahrgeschaeft/25320638.html)
- [Bitcoin, Electrum and Lightning node in Berlin mesh network available](https://hopglass.berlin.freifunk.net/)
- [Berlin Meetup on Monday, 2019-12-16: Bitcoin Mining 2020](https://www.meetup.com/de-DE/Cryptocurrency-Mining-Group/events/267043861/)
- [Bitcoin Assembly "402 Payment Required" at CCC congress 36c3](https://events.ccc.de/congress/2019/wiki/index.php/Assembly:402_Payment_Required)
