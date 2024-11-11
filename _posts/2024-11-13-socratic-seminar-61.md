---
layout: post
title: "Socratic Seminar #61"
---

[Meetup](https://www.meetup.com/bitcoin-lab-berlin/events/298337274/)

Thanks to [Ordimint](https://ordimint.com) for sponsoring food and drinks for this meetup!

## Security/CVEs/InfoSec/Research

- [Adaptors generalized](https://reyify.com/blog/adaptors-generalised/)
- [The distributional consequences of Bitcoin](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4985877)
- [BRC20 Pinning Attack](https://arxiv.org/abs/2410.11295)
- [BCAP: Analyzing Bitcoin Consensus: Risks in Protocol Upgrades](https://github.com/bitcoin-cap/bcap)
- [Great Restored Script Interpreter](https://github.com/jonasnick/GreatRSI)
- [CAT Protocol](https://catprotocol.org/)
- [Payment Censorship in the Lightning Network Despite Encrypted Communication](https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.AFT.2024.12)

## Miscellaneous

- [Bitcoin Core 28.0](https://bitcoincore.org/en/releases/28.0/)
- [Guide for Wallets Employing Bitcoin Core 28.0 Policies](https://bitcoinops.org/en/bitcoin-core-28-wallet-integration-guide/)
- [Blockstream raises $210M from Fulgur etc.](https://blockstream.com/press-releases/2024-10-15-blockstream-secures-210m-dollars-led-fulgur-ventures-drive-layer-2-growth-expand-bitcoin-treasury/)
- [EmailBTC](https://emailbtc.net/)
- [BitVMX website](https://bitvmx.org/)
- [Bitcoin Balance API](https://bitcoin-balance-api.com/)
- [Fabric, DNS resolver for spaces](https://github.com/spacesprotocol/fabric)
- [BTCPay Server 2.0: our biggest update yet!](https://blog.btcpayserver.org/btcpay-server-2-0/)
- [2140 in Europe](https://2140.dev/)
- [Localhost Research in San Francisco](https://lclhost.org/)
- [Satoshi9000 random number generator](https://www.youtube.com/watch?v=bJiOia5PoGE)
- [Report: Building Bitcoin - Funding a $1.2 Trillion Dollar Project](http://1a1z.com/fund.html)
- [Battle of Galen Erso](https://github.com/bitcoin-dev-project/battle-of-galen-erso)
- [StrataBTC by Alpenlabs](https://www.stratabtc.org/)
  - [Design Rationale](https://docs.stratabtc.org/technical/design-rationale/)
- [libbitcoin syncs full blockchain in 1 hour](https://x.com/evoskuil/status/1847673128073187536)

## Europe/Germany/Berlin

- [Telekom tests Bitcoin mining with surplus energy](https://www.telekom.com/en/media/media-information/archive/test-bitcoin-mining-infrastructure-for-surplus-energy-1082684)

## Mailing Lists

### bitcoin-dev

- [DLEQ BIP Draft](https://mailing-list.bitcoindevs.xyz/bitcoindev/b0f40eab-42f3-4153-8083-b455fbd17e19n@googlegroups.com/)

### Delving Bitcoin

- [SuperScalar: Laddered Timeout-Tree-Structured Decker-Wattenhofer Factories](https://delvingbitcoin.org/t/superscalar-laddered-timeout-tree-structured-decker-wattenhofer-factories/1143)
- [LN Summit 2024 Notes & Summary/Commentary](https://delvingbitcoin.org/t/ln-summit-2024-notes-summary-commentary/1198)
- [CVE-2024-38365 public disclosure (btcd `FindAndDelete` bug)](https://delvingbitcoin.org/t/cve-2024-38365-public-disclosure-btcd-findanddelete-bug/1184)
- [Libbitcoin for Core people](https://delvingbitcoin.org/t/libbitcoin-for-core-people/1222)

## Pull requests

### BIPs, BOLTs and Proposals

- [QuBit - P2QRH spending rules](https://github.com/cryptoquick/bips/blob/p2qrh/bip-p2qrh.mediawiki)

### Bitcoin Core

- [Disclosure of CVE-2024-35202](https://bitcoincore.org/en/2024/10/08/disclose-blocktxn-crash/)
- [Disclosure of DoS due to inv-to-send sets growing too large](https://bitcoincore.org/en/2024/10/08/disclose-large-inv-to-send/)
- [Disclosure of hindered block propagation due to mutated blocks](https://bitcoincore.org/en/2024/10/08/disclose-mutated-blocks-hindering-propagation/)
- [Disclosure of hindered block propagation due to stalling peers](https://bitcoincore.org/en/2024/11/05/cb-stall-hindering-propagation/)
- [Drop miniupnp dependency #31130](https://github.com/bitcoin/bitcoin/pull/31130)
- [Remove mempoolfullrbf #30592](https://github.com/bitcoin/bitcoin/pull/30592)

### LND

- [cmd: allow deterministic macaroon derivation with lncli #9172](https://github.com/lightningnetwork/lnd/pull/9172)

### Eclair

- [Add support for RBF-ing splice transactions #2925](https://github.com/ACINQ/eclair/pull/2925)

### BDK & LDK

- [Add the core functionality required to resolve Human Readable Names #3179](https://github.com/lightningdevkit/rust-lightning/pull/3179)
- [Re-broadcast channel_announcements every six blocks for a week #3360](https://github.com/lightningdevkit/rust-lightning/pull/3360)

### Core Lightning

- [pay: Remember and update channel_hints across payments #7494](https://github.com/ElementsProject/lightning/pull/7494)

### Secp256k1

- [Add module "musig" that implements MuSig2 multi-signatures (BIP 327) #1479](https://github.com/bitcoin-core/secp256k1/pull/1479)

### rust-bitcoin & rust-lightning

- [Support Testnet4 Network #2945](https://github.com/rust-bitcoin/rust-bitcoin/pull/2945)
- [Add version three variant to transaction version #3450](https://github.com/rust-bitcoin/rust-bitcoin/pull/3450)
- [Add the ChaCha20Poly1305 AEAD algorithm #2960](https://github.com/rust-bitcoin/rust-bitcoin/pull/2960)
