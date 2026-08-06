# The "other" Gateway to the Internet

![[assets/orbot.jpg]]

_Some of you might be familiar with TOR, otherwise known as The Onion Router. For those who are unaware, TOR provides an alternative gateway onto the Internet that bypasses your Internet Providers prying eyes._

**Written By:** Geovian\
**Date:** 12 July 2023

## Introduction
Some of you might be familiar with TOR, otherwise known as The Onion Router. For those who are unaware, TOR provides an alternative gateway onto the Internet that bypasses your Internet Providers prying eyes. The objective of TOR is to provide users with a private means to surf the Internet without any bad actors unable to trace your steps back to home base. I'll explain further on.

There are a few methods and tools to enable access through a TOR Network, and after a ten year tenure of existence kicking off back in 2014, the TOR protocol has matured to the point of being able to be used as a daily driver for some.

## The Detail
There are a few things to note about TOR:

1. The TOR Protocol acts as a Proxy Server, giving you access to the Internet through a series of relays (other machines or nodes on the TOR Network which act as a bridge) to finally exit out onto the Internet (which is also known as the Clearnet) through what is known as an Exit Node. The TOR configuration generally consists of a data stream of three relay nodes at a minimum, before reaching the exit node. These three nodes help disguise your data stream, so it is mixed and tumbled with all other traffic passing through the same exit node. If it was isolated, it can only be traced back to the third last node in the chain.

2. In the early days circa 2014, there was just the one tool which could be used. And that was a modified version of Firefox called the **TOR Browser**. It was only designed to redirect web based traffic only. It could access the no-man's zone called the Dark Web. No other browser could. It was hampered by the perception of the dark web being a nefarious place, plus using the TOR Browser was very slow  due to the low numbers of relay nodes on the network back then. 

3. Then the TOR Project team rolled out **Orbot**, which was a one stop shop that allowed users to redirect their entire traffic to TOR. Not just web, but everything. At the time, it too was hampered by slow speeds. But looking at it again in 2024, the Orbot Service has improved out of sight. It is now much faster, with more resources and relay/nodes added to the network along with refactoring the code to improve the overall experience.

4. At present, Orbot is only available for Android and iOS. For PC users there are other tools out there but discussing those here is outside the scope of this post. 

5. To clarify, Orbot is not a VPN, but it does operate similarly with a goal to anonymize traffic as much as possible. Contrary to popular belief, you cannot use Orbot and a VPN at the same time. Whoever suggested that has got their wires crossed.

## Operation
Installing Orbot is easy enough. You can find it on either Appstore. Plus for Android users it's also available from F-Droid.

Setting it up is straight forward. Unfortunately I was unable to take a screenshot of the app as the app developer has put a block on it. So anyway, here the four main menu items:

- **Choose the Apps** to be TOR Enabled, or choose VPN for entire device. VPN option is the default setting. 
- **Change the Exit Node** (leave as Global default  so the exit node is always rotating) 
- **Refresh**
- **Turn TOR off** (return to Clearnet mode).

There are other options under the **More..** button below, but I'll talk about them on another day. Mostly the default settings on the first two options above will suffice.

## In Summary
TOR should be downloaded and kept safe as an alternate Internet gateway option. If you have a fast Internet connection, the speed should be much better. Keep an eye of the traffic meter as data passes through. It's fairly rudimentary. I'd like to see the traffic speed monitoring on the App fleshed out a little more.

In the next wee while, I'll be going down the **Lokinet - Session - Nemomail** rabbit hole, as Lokinet is like TOR on steroids, but it's not quite there yet. Watch this space. 
