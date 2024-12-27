+++
title = "Current status on Mostro"
date = 2024-12-20

[extra]
author = "negrunch"
img = "/img/first-post.png"
summary = "Since more than a year we've been tirelessly working on Mostro, here is a summary."
+++

Since more than a year we've been tirelessly working on Mostro, here is a summary.

## Keys management
We have a lot of improvements and probably one of the most important is the final design of keys management, we started to discuss this idea in the previous quarter and we commented it in the last report, keys management is a way clients rotate keys for every trade adding another privacy layer to gift wrap previous implementation, more detailed info here. Today we've merged our main PR for implementing it on mostrod, we also implemented it on mostro-core and mostro-cli

## New Nostr NIP merged
We also had our first official NIP merged, NIP-69, with this we aim to standarize all orders from peer-to-peer platform on Nostr to have a big liquidity pool easily filterable.

## Mostro foundation
We also made progress on establishing the Mostro Foundation, which will serve as a legal entity to handle donations and direct them to developers who want to contribute. Another contributor created the Mostro Foundation website.

## Mostro-tools
We already have contributors working on mostro-tools, a TypeScript library implementing the Mostro protocol.

## Mobile app
Our past attempt of building the mobile app failed, the developer quit, so we found another dev, third time's the charm. Now we’re moving forward with the mobile app, which is being developed by developer called Biz. Working on Mostro is a bit complex because we focus on privacy and censorship-resistance, and our main goal is to deliver these privacy features in an easy-to-use application. I want this app to be very intuitive, suitable even for non-technical users. Biz, delivered a first functional mobile app we can see all the work here and here, we tested it and it works :D

## Mostrui
Finally we started another client, a Terminal User Interface (TUI) which is helping us to implement and understand problems that client developers can find on the process of building a client, this client is called Mostrui

All this couldn't be possible without the support of HRF and Opensats and all collaborators <3
