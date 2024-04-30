---
layout: post
type: socratic
date: "2024-04-30 19:00:00"
title: "Vancouver Socratic 023"
meetup: https://lu.ma/bitdevs
---

## Institutio Theologiae Elencticae

Welcome Elenctics to tonight's Socratic Seminar!

- Event space [fundraiser](https://we.encrypt.cash/apps/4NKmXo1vaxtzDJfd3JnfCtHrzQBf/crowdfund)

We now post the links to this seminar in advance! [Check out our Github issues for the latest.](https://github.com/VancouverBitdevs/VancouverBitdevs.github.io/issues)

Today's MC: TBD

### Never miss a Bitcoin event ever again

[Check out and subscribe to the calendar here](/calendar)

- Port Moody Bitcoin Meetup **02 May 2024**
- [Canadian Bitcoin Conference](https://canadianbitcoinconf.com/) **16-18 May 2024** Discount code: _MEETUP10_
- Noderunners Workshop **21 May 2024**
- [Lightning Pints](https://www.meetup.com/bitcoin-n-beers-vancouver/events/300529786) **23 May 2024**
- May Bitdevs **28 May 2024**
- [BTCVancity Bitcoin Meetup #12](https://www.meetup.com/btc_vancity/events/300663514) **30 May 2024**
- Powell River Bitcoin Meetup **1 June 2024**

### Spend your sats in Vancouver

[Check out our new map and merchant directory](/map)

#### New merchants

[El Caracol](https://www.facebook.com/profile.php?id=100063959828739)
[Bula Lounge](https://bulalounge.com/)

<!-- ### Today's talk -->

### Today's talk

#### Privacy on Lightning

<br><br>
**Lightning channels**
- [Two-of-two multisignature contracts](https://mempool.space/tx/7bd5f8e832915dd09079cf7b3238c20fa0c71ac5e715a33c23a5a58283c0498b)
- [Capacity visible for everyone, balance isn't](https://amboss.space/node/021294fff596e497ad2902cd5f19673e9020953d90625d68c22e91b51a45c032d3)
- Channels are announced as part of the network graph
- Lots of improvements coming to how they are announced!

<br><br>
**Lightning invoices**
- [lnbc21u1pnrz6rspp588fx9kkgu6xqu9js22ptwv89v](https://lightningdecoder.com/lnbc21u1pnrz6rspp588fx9kkgu6xqu9js22ptwv89vpaggstrpf97yxrpht2yt228v6dsdqqcqzzsxqyz5vqsp5hwtj5ckccr6kmxsey6flyn9zxpuglv2f7zvlqvq2frknafwnsnvs9qyyssq6grhhaj6k5mz6u9q7gr5wagfvn4094uz0xaqjel7veqpgye2hu85llvq4sge5s3xxu5pe80wkmd6w2thewp66hg2s45dy9skdx0utpcptmqa2r)
- It may be easy to identify the destination
- Payments are identified by payment hash
- HTLCs become visible onchain if they have to be settled

<br><br>
**Lightning payments**
- [Onion routing hides the full path from routing nodes](https://ellemouton.com/posts/onion-routing-prelims/)
- Each node can only see the previous and next hop.
- Only the ultimate destination knows it is the ultimate destination.
- The ultimate destination only knows the incoming channel.
- Only the sender knows the full path.

<br><br>
**Onchain analysis**
- Segwit channels are easy to identify when they are closed cooperatively or uniltarerally
- As of now, a node's onchain balance can probably be easily calculated after the fact
- Unannounced channels can eventually be identified as their outputs are mixed with inputs from public channels

## bitcoin-dev

- [The Future of Bitcoin Testnet3](https://groups.google.com/g/bitcoindev/c/9bL00vRj7OU/m/9yCPo3uUBwAJ?utm_medium=email&utm_source=footer&pli=1)
- [Exploding Keys - Covenant construction](https://delvingbitcoin.org/t/exploding-keys-covenant-construction/832)
- [Assigning BIP Numbers](https://blog.bitmex.com/assigning-bip-numbers/)
- [Coinfaucet declares "Testnet war"](https://coinfaucet.eu/en/btc-testnet/)

## lightning-dev

- [Clearing the Paths: A Deep Dive into LND's Pathfinding Mechanism](https://lightning.engineering/posts/2024-04-11-pathfinding-1/)
- [LND v0.18.0-rc1 is released](https://groups.google.com/u/0/a/lightning.engineering/g/lnd/c/KzHbUzM6tnc)

## Optech

- [Hackers are threatening to leak World-Check, a huge sanctions and financial crimes watchlist](https://techcrunch.com/2024/04/18/world-check-database-leaked-sanctions-financial-crimes-watchlist/)
- [Wallet Fingerprints: Detection & Analysis](https://ishaana.com/blog/wallet_fingerprinting/)
- [List of known wallet fingerprints](https://github.com/achow101/wallet-fingerprinting/blob/main/fingerprints.md)

## Bitcoinomics



## Network Data

- [What the Drop in Lightning Nodes Means for LN's Future?](https://lightningnetwork.plus/posts/553)
- [Amboss All Time Nodes](https://amboss.space/stats?params=eyJtZXRyaWMiOiJhY3RpdmVfbm9kZXMiLCJjYXRlZ29yeSI6ImFsbFRpbWVNZXRyaWNzIn0%3D)
- [ViaBTC's total reward for the halving block was just over 74 BTC](https://twitter.com/mononautical/status/1783528618720727288)

## Mining

- [Bitcoin Mining Pools Have Become Critically Centralized](https://www.tftc.io/bitcoin-mining-pool-centralization/)
- [Pools sharing custodian](https://twitter.com/mononautical/status/1777686545715089605)
- [Pools sharing the same block template](https://twitter.com/0xB10C/status/1780611768081121700)
- [Marathon Slipstream lets you submit non-standard transactions directly to their node](https://slipstream.mara.com/)
- [Introducing Lightning Payouts](https://pool.braiins.com/en/news/introducing-lightning-payouts)

## Token Layer

- [Taproot Assets Edge Nodes](https://docs.lightning.engineering/lightning-network-tools/taproot-assets/edge-nodes)
- [OP_CAT BIP](https://github.com/bip420/bip420?tab=readme-ov-file)
- [OP_CAT is assigned BIP 347](https://twitter.com/roasbeef/status/1783197750949257436)
- [The Runes Protocol](https://docs.ordinals.com/runes.html)
- [Spaces Protocol: Scalable & Permissionless Bitcoin Identities](https://spacesprotocol.org/)
- [BitVM 2: Opening Up The Playing Field](https://bitcoinmagazine.com/technical/bitvm-2-opening-up-the-playing-field)
- [First BitVM transaction mined](https://mempool.space/tx/d8a091a7f5ffa4993681b3df688968fd274bc76897b8b3953309ffad6055f4b0)
- [Cashu Gateways](https://damus.io/nevent1qqsfakvg9fwttxp6y2fp0n0nmrgnguac63h3lf4pxafetrhms85yv5spz4mhxue69uhhyetvv9ujuerpd46hxtnfduhszxrhwden5te0dehhxarj9enx6apwwa5h5tnzd9az7qg7waehxw309ahx7um5wgkhqatz9emk2mrvdaexgetj9ehx2ap0qyvhwumn8ghj7un9d3shjtnndehhyapwwdhkx6tpdshsssnezh)
- [LRC-20](https://github.com/akitamiabtc/LRC-20/blob/main/LRC_20_V0.1.pdf)

## Regulatory

- [DOJ’s New Stance on Crypto Wallets is a Threat to Liberty and the Rule of Law](https://www.coincenter.org/dojs-new-stance-on-crypto-wallets-is-a-threat-to-liberty-and-the-rule-of-law/)
- [Founders And CEO Of Cryptocurrency Mixing Service Arrested And Charged With Money Laundering And Unlicensed Money Transmitting Offenses](https://www.justice.gov/usao-sdny/pr/founders-and-ceo-cryptocurrency-mixing-service-arrested-and-charged-money-laundering)
- [Phoenix Wallet exiting the US](https://twitter.com/jack/status/1783884776086409393)
- [Are Lightning nodes Money Service Providers](https://twitter.com/acinq_co/status/1783878732865740940)
- [Bull Bitcoin requires full KYC for buying Bitcoin at Canada Post](https://twitter.com/francispouliot_/status/1774840970841874438)
- [Lightspark Gets Debanked by Bill.com](https://www.nobsbitcoin.com/lightspark-gets-debanked-by-bill-com/)
- [zkSNACKs is Now Blocking U.S. Residents and Citizens](https://blog.wasabiwallet.io/zksnacks-now-blocking-u-s-residents-and-citizens/)
- [Binance Founder Sentenced to 4 Months in Prison](https://www.nytimes.com/2024/04/30/technology/binance-founder-changpeng-zhao-sentenced.html)
- [Early Bitcoin Investor Roger Ver Charged with Tax Fraud](https://www.justice.gov/opa/pr/early-bitcoin-investor-charged-tax-fraud)

## (Central Banking) Banking Crisis



## New Releases

- [Coinbase integrates the Lightning Network with Lightspark](https://www.coinbase.com/blog/coinbase-integrates-bitcoins-lightning-network-in-partnership-with)
- [Introducing Casa Inheritance: Secure your generational wealth](https://blog.keys.casa/introducing-casa-inheritance/)
- [LNURL for self-sovereign phoenixd](https://primal.net/e/note1tujvj50j76rhwts5tf6ud2fxdg9n8gyw8z7tsnwp4fsweg4xzt5sa7590u)
- [Sulu solutions releases Sparkwall](https://twitter.com/sulusolutions/status/1777776940134408442)
- [LLM Inference APIs with Lightning](https://www.sulu.sh/llm402)
- [Kraken launches self-custodial mobile wallet and releases its open-source code](https://www.theblock.co/post/289448/kraken-launches-self-custodial-mobile-wallet-and-releases-its-open-source-code)
- [The Bitcoin Scholarship](https://bitcoinscholarship.xyz/)
- [Bitcoin Holiday Calendar](https://bitcoin.holiday/)
- [Neutronpay expands throughout South-east Asia](https://twitter.com/neutronpayapp/status/1783119464932016399)
- [Block lets Square merchants convert a part of their daily sales to bitcoin](https://techcrunch.com/2024/04/24/block-now-lets-square-merchants-convert-a-part-of-their-daily-sales-to-bitcoin/)
- [Perfect forward secrecy is coming to Nostr](https://twitter.com/jb55/status/1785280982226190588)


## Events and Podcasts

- [MIT Bitcoin Expo '24 recording](https://web.mit.edu/webcast/bitcoin-expo-s24/)

## Miscellaneous

- [Satoshi’s 2014 Email Hack](https://blog.bitmex.com/satoshis-2014-email-hack/)
- [The Untold Story of ditto-b](https://blog.lopp.net/the-untold-story-of-ditto-b/)
- [Notes on El Salvador](https://mattlakeman.org/2024/03/30/notes-on-el-salvador/)
- [How to Dictator-Proof Your Money](https://journalofdemocracy.org/online-exclusive/how-to-dictator-proof-your-money/)
- [Vancouver discussion on Stacker News](https://stacker.news/items/519353)
- [He Emptied an Entire Crypto Exchange Onto a Thumb Drive. Then He Disappeared](https://www.wired.com/story/faruk-ozer-turkey-crypto-fraud/)
- [The Deaths of Effective Altruism](https://www.wired.com/story/deaths-of-effective-altruism/)
- [Anatomy of a credit card rewards program](https://www.bitsaboutmoney.com/archive/anatomy-of-credit-card-rewards-programs/)
- [B.C. files unexplained wealth order against co-founder of defunct crypto exchange Quadriga](https://www.theglobeandmail.com/canada/article-bc-files-unexplained-wealth-order-against-co-founder-of-defunct-crypto/)
- [‘I want to be like bitcoin jesus’: Court documents reveal how the Quadriga crypto scandal unfolded](https://www.theglobeandmail.com/business/article-quadrigacx-crypto-scandal/)
