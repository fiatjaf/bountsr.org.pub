---
layout: post
title: Filesharing App
date: 2023-02-04 21:19:00 -0300
categories: code
author: FNF
value: 0.05
currency: BTC
contact: https://t.me/fiatjaf
status: New
---

A very simple and lean web Nostr client dedicated to offering files and requesting files using either a special kind, probably better, just `kind:1` with a `"t"` tag that marks it as a filesharing request or offer.

Once this is working we should standardize it with a NIP.

The actual filesharing should be done over either HTTP or the BitTorrent protocol.

The file "offer" is composed of the file link and a short description of the files, in some standard plaintext format, like

```
title: Autobiography, Charles Dickens
description: A very cool book I wrote
location: magnet:...
```

The file "request" should be similar, but with fields for requesting a file and offering a prize in satoshis for whoever provides that. The money offers are based on trust only.

The simply structured format of the posts exist such that a table view of offers and requests can be shown. I don't know if this is really a good idea, but I think it is.

The "zap" spec for tipping should also be integrated so the file offerers can receive tips for their service of providing files -- and for the requester to pay what he has promised. I don't know exactly how the zap spec works, we must get jb55 to publish it.

Comments on the file requests and offers (that could be made from other apps) should be shown and the user should be able to answer them. Comments will serve as a first and very naïve iteration of some better reputation system that will hopefully happen in the future. Or maybe instead of showing all the comments it is better to have a `nostr:nevent1` link to these posts so the user can open them in their client.

---

The specs above are just ideas to serve as inspiration. Let me know how they could be improved.

The bounty size can be increased depending on how this is going.

Please reach out to me before starting to work on this.

---

If you don't want to use Telegram, mention me on Nostr (`npub180cvv07tjdrrgpa0j7j7tmnyl2yr6yr7l8j4s3evf6u64th6gkwsyjh6w6`/`nprofile1qqsrhuxx8l9ex335q7he0f09aej04zpazpl0ne2cgukyawd24mayt8gpr4mhxue69uhkummnw3ez6ur4vgh8wetvd3hhyer9wghxuet5qyw8wumn8ghj7mn0wd68yttjv4kxz7fww4h8get5dpezumt9qy38wumn8ghj7mn0wd68yttkv4exjenfv4jzuam9d3kx7unyv4ezumn9wslzm9ln`) and we can chat in public (I don't use Nostr DMs currently).
