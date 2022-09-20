---
layout: post
type: socratic
title: "Vancouver Socratic 005"
meetup: https://www.meetup.com/vancouver-bitcoiners/events/288449479/
---

## Announcements
Please join us for today's Socratic Seminar. A special thank you to our sponsors [Adaptech Group](https://adaptechgroup.com/) and [Bull Bitcoin](https://www.bullbitcoin.com/), for food, refreshments and event space.

### Presentation

Merchant maps, how we discover shop

- Magazines
- Stickers at the door
- Targeted promotions

Bitcoin merchant adoption starting around 2012

**How do discover merchants that accept bitcoin?**

- OpenStreetMaps is open source and adaptable through tags
- [Coinmap](https://coinmap.org/) began displaying this data through an easy to navigate web interface
- [CoinATMRadar](https://coinatmradar.com/) began building its own proprietary database
- Point of Sale services may have their own proprietary maps, e.g. [IBEXMercado](https://www.ibexmercado.com/ibex-pay)

**The case for OpenStreetMaps**

- Open
- Wiki-style editing process (or use a [web form](https://www.btcmap.org/add-location))
- Adaptable
- Easy to build on top of or integrate, e.g. local communities or payment processors
- Data is often mirrored into corporate competitors

Tags commonly used:

```
currency:XBT=yes
payment:onchain=no
payment:lightning=yes
payment:lightning_contactless=yes
survey:date=yyyy-mm-dd
```


### Mailing Lists

#### bitcoin-dev

- [Progress on Silent Payments PR](https://bitcoinops.org/en/topics/silent-payments/) Silent payments are a clever way to send BTC to somebody's public key without making this obvious to an observer
- [Joinstr](https://github.com/1440000bytes/joinstr) a proof of concept for a coinjoin implementation over Nostr
- [Cashu](https://github.com/callebtc/cashu) easy to run (?) chaumian e-cash implementation that integrates with off- and on-chain payments

#### lightning-dev

- [Offline PoS now flashable from the browser](https://lnbits.github.io/lnpos/installer/) Easy to use web interface to flash your Offline PoS with the latest firmware
- [Guide to channel jamming attacks](https://jamming-dev.github.io/book/) Great resources to learn about channel jamming and mitigation

<!-- #### dlc-dev -->


### Optech

- [160 million hacked from "crypto" market maker Wintermute](https://decrypt.co/110131/algorithmic-market-maker-wintermute-hacked-for-160m)

<!-- ### Bitcoinomics -->



## Network Data

- [Mempool visualization is 🔥](https://twitter.com/mempool/status/1571846821151793152)
- [Mempool now showing Lightning channel opens](https://mempool.space/tx/036df36d0acda706e926e4156615dd8e34e444ad2ff433c3aff2e78443a003e2:1)



<!-- ## Research -->



<!-- ## InfoSec -->


## Pull Requests and repo updates

<!-- ### Bitcoin Core -->

<!-- ### rust-bitcoin -->

<!-- ### secp256k1 -->

<!-- ### secp256k1-zkp -->

<!-- ### BIPs -->

<!-- ### eclair -->

### c-lightning

### lnd


<!-- ### rust-lightning -->


<!-- ### BOLTS -->

### New Releases



## Events and Podcasts

<!-- ## Mining -->

## Miscellaneous



<iframe
id="btcmap"
title="BTC Map"
width="100%" height="480"
allowfullscreen="true"
src="https://www.btcmap.org/map?lat=49.326912087086605&long=-122.85976409912111&lat=49.11747845930749&long=-123.3424758911133"
></iframe>
