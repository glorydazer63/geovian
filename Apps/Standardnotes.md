---
title: Standardnotes
author: Geovian
description: Standard Notes App
created: 2026-07-24
modified: 2026-08-06
---
# Standard Notes - Use Web Option

<img src="assets/standardnotes.webp" />

_If you're a Web Netizen, there's every likelihood that you accumulate all manner of digital information. The glue that holds it together for me is the note taking app Standard Notes._

**Written By:** Geovian
**Date:** 17 October 2024

## Introduction
If you're a Web Netizen, there's every likelihood that you accumulate all manner of digital information. Much of it in text form. This can be in the form of website URL's which can be saved as bookmarks, or even better, saved into a web clipper app like the excellent Raindrop.io.

Or it can be a heavy collection of text files, accumulating snippets of text for any/every subject imaginable. In my case, I gather various instructions for Linux installations, not only of Linux distributions (Ubuntu, RaspberryPi, Debian etc), but also of Linux instructions to install applications and systems using a variety of methods (including Synaptic, AppImage, Flatpak etc).

The glue that holds it together for me is the note taking app **Standard Notes**. 

## The Detail
This is not just any app. It can run across all platforms, and is synchronized in real time. There is no polling trigger to activate content update. You write something, as soon as you see the green tick appear in your SN page, it's updated.

The modern day problem with apps is that you cannot trust whether the developer has your best interests at heart. This is most apparent on the mobile platform. In my case, I use the Graphene OS on a Google Pixel 6a phone. All stock Android apps downloaded off the Google Playstore are quarantined (sandboxed) into their own memory/drive space on the phone, and are unable to communicate with other apps, nor "home base". All apps can have phone sensors switched off (either individually or all), meaning that apps cannot access things like the camera, the GPS etc.

Which leads me back to Standard Notes. I do use it on mobile, but have pretty much locked it down as per above. I don't bother using the specific app for Linux because it's quite clunky to set up on the command line. Plus I don't see an autostart function which I could apply using systemd scripts.

In saying that though, if you use a Distro that does still use systemd, then the autostart function works well for this apps that can take advantage of it.

I use a Debian distro (MX Linux) which doesn't use systemd anyway. So instead, I just use the web browser. A heavily locked down Brave Browser at that.

There are numerous advantages to this approach.

  - The data is contained in an encrypted online ecosystem, and I don't have to worry about the data should I migrate to a new laptop or even a new Linux distro. It'll all still be there.
  - My Brave Browser runs a Private DNS function (using AdGuard), which means no one can eavesdrop on your connection.. Brave also has a Shields option, plus I run a VPN 100% of the time (on both mobile and Linux). Call me paranoid much?
  - Much of the data I add into my Standard Notes store is from the web, so copy and paste is done between open Browser pages, rather than workspaces on your laptop, or different screens on mobile. I'm all for convenience.

## In Summary
Standard Notes direct competitor would be Evernote. The pervasive nature of Evernote's business model means I will probably never sign on with them again.
I use the Standard Notes annual subscription, but you can use it for free if you so wish. It's a critical piece of my small business model toolkit, paying a sub is not an inconvenience.

Check them out at:  [Link](https://standardnotes.com)