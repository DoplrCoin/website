---
# In /about.md:
layout: default
title: Whitepaper
language: en
handle: /about # same as in /de/about.md and /it/about.md
---

# Doplr Whitepaper

![](https://i.imgur.com/oVSYenv.png)

## Vision

* The vision of Doplr is that in the end the coins and tech will become invisible for the end-user.
* We see that users want crypto to play with, but paying for it seems too much risk for most.
* We see users create value in a social network and receive nothing back but fake internet karma points.
* Doplr will never promote itself as a blockchain dev company, we're not building the next gen blockchain, so let's not lie to the users.
* We will however develop services and ideas around the use of crypto, we will focus on social media tipping.
* The goal of Doplr is to provide value in the connection between users, internet services and the blockchain.
* When we see interesting developments in other chains that have proven their stability, we will port it back to the Doplr chain. The organisation sees itself more in the role of a curator of technology rather than running on the forefront of blockchain technology.
* From the vision of the curator we will develop a practical plan as an integrator of internet and blockchain technologies.
* We envision a multiverse of coins, where some coins have an ecosystem of plain plug-in  internet technology and provide a link to the 'classical' internet world.
* There will be other blockchains providing arbitrage and interoperability between the hundreds of successful coins.
* Doplr will be more like a store af value, and edge-currency designed to be compatible with 3 generation blockchain protocols like polkadot, aion and the likes.

Doplr aims to have as much users as possible, the airdrop mechanism is one of the ways we achieve this.

First, some theory: **Metcalfe's law** states that the value of a telecommunications network is proportional to the square of the number of connected users of the system $n^2$. First formulated[^first] in this form by George Gildera and attributed to Robert Metcalfe in regard to Ethernet, Metcalfe’s law was originally presented, c. 1980, not in terms of users, but rather of “compatible communicating devices” (for example, fax machines, telephones, etc.).[^second]
![](https://i.imgur.com/idLYhaq.png)

### What does this mean for us?

Highlights of the study on this phenomenon in relation to blockchain networks in the following academic paper: "Digital blockchain networks appear to be following Metcalfe’s Law"[^third]  by Ken Alabi: “the networks were fairly well modeled by Metcalfe’s Law, which identifies the value of a network as proportional to the square of the number of its nodes, or end users,”

If the value of a network increases, then the value of each individual coins increase.  This was and is still very noticeable with bitcoin.

![](https://i.imgur.com/YL3BADW.png)


## Doplr Airdrop

* Let's get as much people as possible involved.
* Let's fight multiple accounts/scammers but not make it ruin the experience of the normal users.
* We want this to be a low effort coin, max 42 mins of effort needed per week to qualify for a semi full airdrop.
* We need ways to uniquely identify users but without classical KYC or asking people for papers.

The rest of the airdrop details are **Conceptual**. We will tweak them of the course of time.


### Classic returning airdrop
Basic concept: we give rewards to  
* Unique people, who stay in our channels, PoP proof of presence.
* People who refer and


Based on 'presence' in social channels. We will never monitor the volume you type but we will check if you're online. People will **never** be paid for volume.


So for 100 timeunits in an airdrop.
We check:
* is user online in discord (0 - 100) $D
* is the user online in telegram (0 - 100) $T

Every airdrop:
* did the user make 1 post on bttalk with our sig (0/1) $BTT
* did the user make 1 reply in the official reddit airdrop thread (0/1) $RED
* ...

**this gives us a score, for example:**
`` ($D + $T) + (($D + $T)/10) * $BTT +  (($D + $T)/10) * $RED  ``
*(take sum of forum + telegram, add 10% if btt add another 10% if reddit )*

We take that score and make it a bit more heavy by the level of auth :
* Mail (x1.1)
* Phone (x1.1)
* bttalk account (x1.1)
* reddit account (x1.1)

### Special challenge
Then, there will be the ***ta-ta-dam*** special airdrop challenge.

* You need to take a picture with your username / id / uuid / code.
* We tell you what has to be on it, like a cup , a piece of fruit , a flower , a hand , a shoe, a spoon, a drink, ...
* People submit that picture to a form.
* the bot displays the ids and posts pics in the channel with :+1: and :-1:, users vote , get a little reward for that and pics get validated.
*  this will *add* a number to your score that is the median of all other scores.

The we have a list of scores and we apply a ladder system to it. But not with big fees for to 1%. A broad and equal distribution is the goal here.



### Referrals

If users refer someone, this means someone else types **!setref @username** , he will get good compensation based on the amount of airdrop the person he referred to has received. This will be different from the next referrals.

### Reach out airdrop aka Hard Spoon.
* a big part of the funds will be reserved for other coins that will be reached out to.
* e choose a coin (dying or not), which community seems reachable to us.
* We reserve an amount, we take a snapshot of the balances, we publish that list.
* If users want to claim their coins they will need to sign a message and dump that into a form somewhere.
* We will put a referrer in the link for the user who has spread the link, this code will be logged and signed by the person collection the hard spoon reward. Users who've referred users from the other community get a **good** reward.

## Finance
* From analysis of other project we've reached the conclusion that coins which are still in airdrop phase do terribly on exchanges.
* Some people have the idea that they can get coins for free and sell that for money immediately, this is not economically sustainable.
* We will not be fundraising btc to get on an exchange. Too much scamminess.
* Let's wait till we're big enough so exchanges will come to us.
* Even better: let's wait for 3rd gen blockchains that can be used by our huge userbase.
* Investors put pressure on the project, and manipulate it to go a certain way.
* No fundraising ICO style, no '*donations*' (which is actually selling), no airdrop immunity buying.
* We can not stop exchanges from listing us, we will not stop users organizing voting campaigns to get listed somewhere, but it seems more sustainable to us to wait and let the market act without forcing it.
* If users want to use our channels to trade among themselves, they should feel free to do so.

### how will we run/pay the services?
* Distributed , we might set up a fundraising account to pay for these small expenses.
* People can set up to be part of the fundraising for the crypto equivalent of 2$/month and will receive early updates and goodies, special discord rank, ...
* The team can afford these costs for the time being.

## Coin Specifics
* We're looking for a masternode enabled technology, for the first iteration
* staking reward / masternode reward / foundation reward.
* We start with low market cap and reserve a reasonably large part of the mining rewards for the foundation in the beginning, these funds will mostly be used for airdrops and hard spoons.
* This will give a low amount of coins and true broad distribution.
* A technical whitepaper with detailed coin specifics will follow **after** release of the **testnet** but before the release of the public net.
* Testnet and test wallets will be deployed soon.



[^first]: Carl Shapiro and Hal R. Varian (1999). [_Information Rules_](https://books.google.com/books?id=aE_J4Iv_PVEC&printsec=frontcover&dq=inauthor:shapiro+inauthor:varian#PPA184,M1). Harvard Business Press. [ISBN](https://en.wikipedia.org/wiki/International_Standard_Book_Number "International Standard Book Number") [0-87584-863-X](https://en.wikipedia.org/wiki/Special:BookSources/0-87584-863-X "Special:BookSources/0-87584-863-X").

[^second]: Simeon Simeonov (July 26, 2006). ["Metcalfe's Law: more misunderstood than wrong?"](http://simeons.wordpress.com/2006/07/26/metcalfes-law-more-misunderstood-than-wrong/). _HighContrast: Innovation & venture capital in the post-broadband era_.

[^third]: KenAlabi (2017). ["Digital blockchain networks appear to be following Metcalfe’s Law"](https://www.sciencedirect.com/science/article/pii/S1567422317300480) (PDF).


Author links open overlay panel
