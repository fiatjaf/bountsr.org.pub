---
layout: post
title:  "Relay-based Social Nostr app design"
date:   2023-01-25 21:19:00 -0300
categories: design
author: FNF
value: 0.05
currency: BTC
contact: nostr:nprofile1qqsrhuxx8l9ex335q7he0f09aej04zpazpl0ne2cgukyawd24mayt8gpr4mhxue69uhkummnw3ez6ur4vgh8wetvd3hhyer9wghxuet5qyw8wumn8ghj7mn0wd68yttjv4kxz7fww4h8get5dpezumt9qy38wumn8ghj7mn0wd68yttkv4exjenfv4jzuam9d3kx7unyv4ezumn9wslzm9ln
status: New
---

Read these posts:
 - https://t.me/nostr_protocol/77689
 - https://t.me/nostr_protocol/77753
 - https://t.me/nostr_protocol/77754

Basically the apps that exist today treat relays as these shameful things that must be
hidden from the users. But for Nostr to really scale and be useful, I believe relays must
take a more prominent role in the user experience (or the app must do a really good job
in doing smart relay management under the hood, but that's not what this bounty is about).

I am not 100% sure about any of this, so feel free to experiment, but some of the things
that could be interesting for users to be able to do when interacting with Nostr are:

- Viewing from which relays each note came.
- Choosing to which relays they will publish each note. This could be done before writing
  a note or after, or based on the context (if you're replying to a note published on relay
  A you might want to publish your reply to A too and not only to your default relays B and
  C), or based on some presets or something else.
- Visualizing the relays each other user are known to be using.
- Browsing through different "local feeds", one for each relay -- or arbitrary combinations
  of relays?
- Viewing a relay's "profile", i.e. information the relay displays about themselves,
  policies etc, but also information gathered from interacting with that relay over time --
  users who post to that relay, number of notes downloaded from that relay, interactions
  you had with that relay and their quality.

If we can make such that this kind of interaction is not restricted to nerds in a hidden
"advanced setting" but is indeed an integral part of Nostr apps I think it has a a chance
of working.
