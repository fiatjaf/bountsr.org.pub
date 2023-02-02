---
layout: post
title:  Relay-centric Group Chat client
date:   2023-02-02 21:19:00 -0300
categories: code
author: FNF
value: 0.05
currency: BTC
contact: https://t.me/fiatjaf
status: New
---

The idea is to implement the group chat NIP (and possibly improve upon it) in a native (for iOS, Android or Desktop) client that puts relays at the forefront.

For example, instead of just "join group x" the user must be able to say "join group X on relays A, B and C -- simultaneously join group Y on relays B, D and E" and change that overtime. Groups must be shared using `nevent` type indicating the relays they're being hosted in by default (although nothing prevents them from existing in multiple places or even in parallel universes accessible only on mysteryous relays).

A client should also try to rebroadcast messages it gets from one relay in that group to the other relays it is using that group for.

This is just a basic concept of what I want to see done. I'm open to ideas. Please talk before building. See also https://t.me/nostrdesign/1367 for some rogue ideas related to making relays first-class citizens.

---

If you don't want to use Telegram, mention me on Nostr (`npub180cvv07tjdrrgpa0j7j7tmnyl2yr6yr7l8j4s3evf6u64th6gkwsyjh6w6`/`nprofile1qqsrhuxx8l9ex335q7he0f09aej04zpazpl0ne2cgukyawd24mayt8gpr4mhxue69uhkummnw3ez6ur4vgh8wetvd3hhyer9wghxuet5qyw8wumn8ghj7mn0wd68yttjv4kxz7fww4h8get5dpezumt9qy38wumn8ghj7mn0wd68yttkv4exjenfv4jzuam9d3kx7unyv4ezumn9wslzm9ln`) and we can chat in public (I don't use Nostr DMs currently).
