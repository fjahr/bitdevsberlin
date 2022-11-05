---
layout: post
title: "Socratic Seminar #37"
---

[Meetup](https://www.meetup.com/de-DE/bitcoin-lab-berlin/events/hllwtsydcpblb/)

## Focus Topic: Full-RBF

- [Recap/Continued discussion: Zero-conf apps in immediate danger](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2022-October/020980.html)
- [Luke Re: Zero-conf apps in immediate danger](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2022-October/020983.html)
- [Analysis of full-RBF deployment methods](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2022-October/021075.html)
- [AJ: On mempool policy consistency](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2022-October/021116.html)
- [Suhas Re: On mempool policy consistency](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2022-October/021135.html)
- [Remove mempoolfullrbf option #26438](https://github.com/bitcoin/bitcoin/pull/26438)
- [Announcement: Full-RBF Miner Bounty](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2022-November/021143.html)
- [Conversations spills over to Twitter with predictable change of tone](https://twitter.com/BitcoinErrorLog/status/1588129881988153345)

## Security/CVEs/InfoSec/Research

- [River Financial: Insights From the 4th Largest Lightning Network Node](https://river.com/learn/files/river-lightning-report.pdf)
- [Validity Rollups on Bitcoin](https://bitcoinrollups.org/)
- [Unjamming Lightning: A Systematic Approach](https://github.com/s-tikhomirov/ln-jamming-simulator/blob/master/unjamming-lightning.pdf)
- [A Note on the Unforgeability of MuSig2 with Key Tweaking](https://github.com/jonasnick/musig2-tweaking/blob/master/main.pdf)
- [DyFEn: Agent-Based Fee Setting in Payment Channel Networks](https://arxiv.org/pdf/2210.08197.pdf)
- [Do not rug on me: Zero-dimensional Scam Detection](https://arxiv.org/abs/2201.07220)
- [Leveraging the Verifier’s Dilemma to Double Spend in Bitcoin](https://arxiv.org/pdf/2210.14072.pdf)

## Miscellaneous

- [LND/BTCD fails a second time](https://github.com/lightningnetwork/lnd/issues/7096)
  - [Brief summary](https://www.nobsbitcoin.com/second-critical-lnd-bug-in-a-month/)
  - [BTCD issue](https://github.com/btcsuite/btcd/issues/1906)
  - [Burak Tweet](https://twitter.com/brqgoo/status/1587397646125260802)
  - [AJ Towns had disclosed bug already](https://twitter.com/ajtowns/status/1587414992961216512)
  - [Ongoing Twitter discussions on responsible disclosure](https://twitter.com/KLoaec/status/1587413526343294976)
- [Using LNsploit to Steal from LND nodes](https://abytesjourney.com/using-lnsploit-to-steal-from-lnd-nodes/)
- [WIP Bitcoin Core QML-based GUI](https://bitcoincore.app/)
- [Blocks/Square hardware wallet design](https://wallet.build/how-we-design-our-hardware/)
- [Sprial and Braiins establish Working Group to Develop Stratum v2 Mining Pool](https://bitcoinmagazine.com/business/spiral-braiins-launch-working-group-for-stratum-v2)
- [CardCoins conference trivia](https://github.com/CardCoins/conference-trivia/)
- [Bitcoin Ring](https://www.bitcoin-ring.com/)
- [Bitmex Research: Bitcoin Developer Grants](https://blog.bitmex.com/wp-content/uploads/2022/10/Bitcoin-Grant-Presentation-1.pdf)
- [Jam: a modern interface for JoinMarket](https://jamapp.org/)

## Europe/Germany/Berlin

- [Hetzner enforces TOS: 1/5 solana validators offline](https://www.theblock.co/post/182283/1000-solana-validators-go-offline-as-hetzner-blocks-server-access) [email](https://twitter.com/solblaze_org/status/1587818136694591491)
- [Switzerland: FINMA publishes revised AML ordinance](https://finma.ch/en/news/2022/11/20221102-mm-gwv-finma/)
- [Santander limits tx to crypto exchanges to £3,000/30day](https://www.santander.co.uk/personal/support/fraud-and-security/cryptocurrency)

## Mailing Lists

### bitcoin-dev

- [Relaxing minimum non-witness transaction size policy restriction](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2022-October/020995.html)
- [Ephemeral Anchors: Fixing V3 Package RBF against package limit pinning](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2022-October/021036.html)
- [Bitcoin Contracting Primitives WG 1st Meeting, Tuesday 15 Nov. 18:00 UTC](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2022-November/021139.html)

### lighting-dev

- [Fat Errors](https://lists.linuxfoundation.org/pipermail/lightning-dev/2022-October/003723.html)
- [Forwardable Peerswaps: Improving Network Health Via Pressure Release Valve](https://lists.linuxfoundation.org/pipermail/lightning-dev/2022-October/003710.html)

## Pull requests

### BIPs, BOLTs and Proposals

- [Bug in Musig2 BIP discovered (and fixed)](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2022-October/021000.html)
- [Refreshed BIP324](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2022-October/020985.html)

### Bitcoin Core

- [Add scanblocks RPC call (attempt 2) #23549](https://github.com/bitcoin/bitcoin/pull/23549)
- [p2p: Erlay support signaling #23443](https://github.com/bitcoin/bitcoin/pull/23443)
- [wallet: fast rescan with BIP157 block filters for descriptor wallets #25957](https://github.com/bitcoin/bitcoin/pull/25957)
- [rpc: Pruning nodes can not fetch blocks before syncing past their height #23927](https://github.com/bitcoin/bitcoin/pull/23927)

### LND

- [add SECURITY.MD to bolster security entry in README](https://github.com/LightningNetwork/lnd/commit/609cc8b883c7e6186e447e8d7e6349688d78d4fd)
- [htlcswitch: final settle signal #6517](https://github.com/lightningnetwork/lnd/pull/6517)

### Eclair

- [Add tlv to require confirmed inputs for dual funding #2461](https://github.com/ACINQ/eclair/pull/2461)

### BDK & LDK

- [Add signature grinding for ECDSA signatures #779](https://github.com/bitcoindevkit/bdk/pull/779)

### Core Lightning

- [Blinded payments spec update and infrastructure for forwarding #5646](https://github.com/ElementsProject/lightning/pull/5646)

### rust-bitcoin & rust-lightning

- [Track Channel Liquidity History in ProbabilisticScorer #1625](https://github.com/lightningdevkit/rust-lightning/pull/1625)

## Newsletters

- [Bitcoin Optech](https://bitcoinops.org/)
