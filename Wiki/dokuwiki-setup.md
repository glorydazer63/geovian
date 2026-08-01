---
title: dokuwiki-setup
author: Geovian
description:
created: 2026-07-24
modified: 2026-07-27
---

# DokuWiki Setup Process

![[dwlogo.png]]

<color orange>Explaining our DokuWiki setup process.</color>

**Written By:** Geovian\
**Updated:** 5 November 2024

Here's a quick explainer as to how we set our DokuWiki instance up on our web server.

We have a new web host based in Canada, they have an installer program called **Softaculous**, which is a collection of all the biggest and best apps and platforms out there on the Internet. They have DokuWiki within their library. We just click on it and install it, the install process takes all of a minute.

Once it's installed, we can then go and get inside the bare bones skeleton of it, and start populating what we need. Firstly we use the Extension Manager to upload all of the plugins that we will use. We use about 20 which do all sorts of different things to make the Wiki very flash looking. Once that's been done we then upload all our text files and images via FTP from my local computer directly into the appropriate folders on the DokuWiki platform. It's basically really simple.

As a consequence, we are maintaining an offline copy of the Wiki, so in the rare event of a system failure, we can easily restore everything. 

The other great thing is that we do not use mySQL databases. Not at all. We use mostly plugins, text files, images and links. This combination is what is used to render our web pages onto the Internet. 