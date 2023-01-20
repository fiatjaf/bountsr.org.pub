---
layout: post
title:  "SATSCARD integration on Breez wallet"
date:   2022-12-14 01:01:01 -0500
categories: code
author: Breez
value: 0.05
currency: BTC
contact: https://doc.breez.technology/Bounties.html#satscard-integration
status: New
---

Find more information and contact for the bounty on https://doc.breez.technology/Bounties.html#satscard-integration

### SATSCARD Integration
- The main two interactions are initializing the card and unsealing the card slots for sweeping WIFs. Here is an implementation of the NFC protocol to talk to the cards in Python. Nunchuk re-wrote it in C++ here and this is a React Native implementation.
- From a product standpoint, when tapping the card on the device, Breez should show a dialog displaying the card balance and offer a sweep action to a Breez address.
- For anyone interested in the work and testing, the Coinkite team are happy to send test cards.
- Payout: 5M sats (donated by the Coinkite team) for a complete iOS and Android implementations.

