---
layout: post
title: "Socratic Seminar #28"
---

[Meetup](https://www.meetup.com/Bitcoin-Lab-Berlin/events/rkzdqsydcdblb/)

## Security/CVEs/InfoSec/Research

- [MuSig2: Multisig with Schnorr](https://popeller.io/schnorr-musig2)
- [musig2-py](https://github.com/meshcollider/musig2-py)
- [Safari Leaks](https://safarileaks.com/)
- [Extracting the Private Key from Schnorr Signatures that reuse a Nonce](https://b10c.me/blog/009-schnorr-nonce-reuse-challenge/)
- [Peter Todd review of OP_CTV](https://twitter.com/peterktodd/status/1483242144240443398?t=BfTW8eDBT_jEInWeMHtVFg&s=19)
- [Paper: Bitcoin investments and climate change: A financial and carbon intensity perspective](https://www.sciencedirect.com/science/article/abs/pii/S1544612321005262)
- [Discussion by @stefanwouldgo](https://threadreaderapp.com/thread/1486271577398386690.html)
- [Performance Benchmark of Electrum backend implementations](https://www.sparrowwallet.com/docs/server-performance.html)
- [Bitcoin Fungibility Graveyars](https://sethforprivacy.com/posts/fungibility-graveyard/)
- [Taproot Adoption](https://txstats.com/dashboard/db/taproot-statistics?orgId=1)
- [Dandelion DoS vulnerability on MimbleWimble chains](https://arxiv.org/abs/2112.13009)
- [Thresh Metr MuSig](https://github.com/ElementsProject/scriptless-scripts/blob/b39355fe8854e542c5c00939942f460b265d37d8/md/thresh-metr.md)

## Miscellaneous

- [Solo miner won a 6.25 BTC reward](https://bitcoinmagazine.com/markets/solo-bitcoin-miner-finds-valid-block)
- [Taproot activates on Liquid](https://twitter.com/ajtowns/status/1482703529576116225)
- [Bank of Russia calls for ban on Bitcoin mining and trading](https://www.zerohedge.com/crypto/bank-russia-calls-full-ban-crypto-mining)
- [Taproot funds burned on the bitcoin blockchain](https://suredbits.com/taproot-funds-burned-on-the-bitcoin-blockchain/)
- [PathCoin](https://gist.github.com/AdamISZ/b462838cbc8cc06aae0c15610502e4da)
- [Lightning Laisee](https://laisee.org/)
- [CypherpunkPay, a simple BTCPay Server alternative](https://cypherpunkpay.org/)
- [DSN Bitcoin P2P Monitoring](https://www.dsn.kastel.kit.edu/bitcoin/index.html)
- [Google Cloud launches dedicated digital asset team](https://cloud.google.com/blog/topics/financial-services/google-cloud-launches-dedicated-digital-asset-team)
- [Address Ownership Proof Protocol (AOPP)](https://aopp.group/)
- [Andrew Chow named Bitcoin Core maintainer](https://twitter.com/achow101/status/1473028680775606273)
- [LNRouter Liquidity Marketplace](https://lnrouter.app/liquidity-ads)
- [Bitcoin Python Community](https://bitcoinpy.dev/)
- [Distributed Charge](http://andyschroder.com/DistributedCharge/BoardA0/Overview/)

## Europe/Germany/Berlin

- [Event: Fulmo Lightning Network Hackday Istanbul. Feburary 25-27](https://lightninghackday.fulmo.org/)
- [Event: Advancing Bitcoin London. March 3rd-4th](https://www.advancingbitcoin.com/)
- [Sparkassen eröffnen Richtungsstreit um Bitcoin-Handel](https://financefwd.com/de/sparkassen-richtungsstreit/)
- [Bitcoin-Boom im Libanon - Die Verlockung der lautlosen Macht](https://www.tagesschau.de/wirtschaft/finanzen/libanon-bitcoin-101.html)

## Podcasts

- [This Week in Lightning Ep 3 with Special Guest Bastien](https://www.youtube.com/watch?v=F1Z7yuuMCCc)
- [Chaincode Podcast - Block Building with Clara and Murch](https://podcast.chaincode.com/2022/01/31/blockbuilding-clara-murch.html)
- [Dr. Bitcoin Podcast](https://podcasts.apple.com/gb/podcast/dr-bitcoin-the-man-who-wasnt-satoshi-nakamoto/id1592521379)

## Mailing Lists

### bitcoin-dev

- [Bitcoin Legal Defense Fund](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2022-January/019741.html)
- [TXHASH + CHECKSIGFROMSTACKVERIFY in lieu of CTV and ANYPREVOUT](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2022-January/019813.html)
- [Improving RBF Policy](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2022-January/019817.html)
- [CTV BIP review](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2022-January/019776.html)
- [CTV dramatically improves DLCs](https://lists.linuxfoundation.org/pipermail/bitcoin-dev/2022-January/019808.html)

### lighting-dev

- [Claiming the 1BTC Strike/HRF "Stable Channel" bounty](https://lists.linuxfoundation.org/pipermail/lightning-dev/2022-January/003438.html)

## Pull requests

### BIPs, BOLTs and Proposals

- [BIP 326: Anti-fee-sniping protection with nSequence in taproot transactions to improve privacy for off-chain protocols #1269](https://github.com/bitcoin/bips/pull/1269)
- [BOLT 1: adds remote address to optional init_tlvs (IP discovery) #917](https://github.com/lightning/bolts/pull/917)

### Bitcoin Core

- [ARMv8 SHA2 Intrinsics](https://github.com/bitcoin/bitcoin/pull/24115)
- [Add getdeploymentinfo RPC #23508](https://github.com/bitcoin/bitcoin/pull/23508)
- [wallet: Allow users to specify input weights when funding a transaction #23201](https://github.com/bitcoin/bitcoin/pull/23201)
- [doc: testnet3 was not reset and is doing BIP30 checks again #23882](https://github.com/bitcoin/bitcoin/pull/23882)

### LND

- [lncli: add leaseoutput command #5964](https://github.com/lightningnetwork/lnd/pull/5964)
- [Allow remote signer to run without chain backend #6006](https://github.com/lightningnetwork/lnd/pull/6006)

### Eclair

- [Activate onion messages #2133](https://github.com/ACINQ/eclair/pull/2133)
- [Replaceable txs fee bumping #2113](https://github.com/ACINQ/eclair/pull/2113)
- [More aggressive confirmation target when low on utxos #2141](https://github.com/ACINQ/eclair/pull/2141

### BTCPayServer

- [Support LNURL Auth #3083](https://github.com/btcpayserver/btcpayserver/pull/3083)
- [Add configurable BOLT11Expiration for refunds (Fix #3281) #3341](https://github.com/btcpayserver/btcpayserver/pull/3341)

## Newsletters

- [Bitcoin Optech](https://bitcoinops.org/)
