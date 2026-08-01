---
title:
author: Geovian
description:
created: 2026-07-24
modified: 2026-07-29
---

## Backing Up Your Web Data

![[databackup.jpg]]

<color orange>The Internet back-chatter is all a flurry at the moment about the current version of the Internet potentially closing down completely and replaced by something new. A bit of a doomsday scenario I know but what if, it did go down, then what happens to your data wherever it is stored?</color>

**Written By:** Geovian\
**Updated:** 5 November 2024

### The effectiveness of the Cloud
I won't get into the whys and wherefors about the Internet potentially shutting down, that's a discussion for another day and beyond the scope of this article. Having a backup strategy for your all-important data, whether stored on the cloud or stored in a web host database for your public facing website is the issue here. Let's go over a few of the issues.

When the Cloud strategy came in to play a few years ago, Enterprises more so than small business thought it was the next best thing since sliced bread. I've always been dubious about Cloud services, because I knew at the end of the day if the cloud went belly up or was hacked, my data was compromised. I always wanted to ensure my data was safe under my own roof, so to speak.

Also, not all businesses were convinced. For those that had security oriented data, like intellectual property (software code for instance), then putting it up on the cloud was a no-go. Unless stringent clauses were included under a service level agreement (SLA). However, one of the benefits of using a cloud service is that all the technology, skills, expertise and resources available through an outsourced arrangement, for a price of course.

For our readership/audience, technology will play a part in a small business operation for sure, but I'm guessing probably not to the same level as a corporate Enterprise using a data warehouse for instance. So therefore, being able to backup your data might be an easier proposition than you realise. 

### Data vs Web Infrastructure
Let's say that you have a WordPress website. Ok, fairly common but there are two aspects to it as there is with any website infrastructure, and that is:

  - your content (data, records etc) 
  - your entire website infrastructure minus the content.
  
Using the example above with WordPress, the content aspect is straight forward. WP posts might be loaded up directly on the web page, or if like me, you can create it in a document or text file offline and just copy and paste it on to the Web page or FTP up to the appropriate directory on your Web server. That way you have an offline copy immediately.

The second part is the infrastructure, and this is where it gets tricky, unless you are very familiar with dealing with content management systems, plugins, uploading of images, and all that stuff. Notwithstanding, some business owners don't bother with uploading their own version of a content management system, instead they use a service like **Softaculous** which your web host will automatically install for you on your Web domain hosting plan.

Despite all this, when creating a website part of your planning process should include a **continuity of operation strategy**. Which quite simply means having the ability to restore your website from scratch in case something untoward happens. And by 'scratch', this means you have access to your up-to-date content and infrastructure in an offline capacity, so that such a restore can take place without relying on the vagaries of a cloud backup. My motto simply is:

<color cyan>**"if your data is not in your direct hands then it's not in your control."**</color>

In one of my situations, I have had web data online since 1999, and I am absolutely anal about saving the content offline at all times. Never have I had to worry about losing any of it because I've got it backed up in different places both online and offline in case of emergencies. Some might consider it to be a little bit paranoid, but it gives me peace of mind and more importantly I know that it will save me money in the long run if a full blown restore is required. Losing 22 years of content is not to be contemplated. As it is, I have the technical capabilities to do it myself but that's something other small business owners might not be able to do.

### Using Google, Wix and other free services
Despite what people will tell you about free services, the reality is, they are not really free. There is always a cost whatever that might be, hidden in the packaging.  So, if you are using a free service like Google, Wix, Zoho, please ensure at the very least you have the capability to backup your data to an offline repository. Yes, at the very least.

I will ask the same question about email, uploading of images and other content you've placed up onto the cloud, like Facebook, Instagram or Tiktok or whatever. Sure some of these tools are very useful to the layperson, and I have no problem with that. The problem then becomes: 'what happens when you're not able to get access to your data, let's say if the Internet goes down or if there's a long outage of some sort and your business requires access to your data. 

Many people and many business owners have different strategies on how to manage their data. Some of them have super strong bulletproof strategies, but I'll go out on a limb and say that 80% have a strategy that is totally and utterly inadequate, and that they are ill-prepared for a tech catastrophe if and when it happens. A very sobering thought.

### Some Strategies
The robustness of your **continuity of operation strategy** depends on how serious you are about preserving your data. If you have a cavalier attitude about it all then you probably shouldn't be reading this page. If you are concerned, read on. 

### Web Data
We've discussed web data above. If you are outsourcing your web services work to someone else, have a talk to them about a backup strategy. It is your data after all, don't accept no for an answer. Get it documented, and include it in your overall business plan for transparency purposes. 

### Email
It depends on how and where your email is being used. There are four typical categories:

  - public email service (Gmail, Hotmail, Yandex, GMX).
  - a corporate email attached to a business (maybe you're employed there).
  - your own mail hosted on your own hosted domain.
  - email hosted on your own server privately, say at home (setup and configuration is not for the faint hearted).
  
The first two categories do not give you a great deal of flexibility to download your email data. However, you could use a Microsoft Outlook client in hooking into any mail services and then save your email to what is called a PST file which is located locally on your computer. I haven't used Outlook for many years so I'd need to come up to speed with that type of solution. 

The Mozilla mail client called Thunderbird is another option, but you need to configure your t-bird mailboxes to download content directly onto your computer. This can be done, but the file size of your mailboxes might get quite high if you send out lots of mail and also mail with attachments. Better to have them locally than not I say. Note: Thunderbird is only available for the Desktop.

The third category can also be saved onto a local computer. No problem there. Its what I do. You'd probably need to set it up using a POP3 port rather than IMAP, but do test the ability to download to your computer because not all mail clients are the same. Simply switch off your internet for a moment, go into your mail client and see if you can read the content of the emails intact when offline. If so, it works.

The fourth category is for those who are more than technically capable of setting up their own public facing servers at home including the provision of a mail server. If so, your data is 100% online but also 100% offline, if that makes sense. Again, that might be a discussion for another day.

### Calendars
Calendars are normally attached to an email address, as with Gmail. Tasks are also included into Calendars. So when migrating calendars through a CALDAV server, both Calendar and Tasks data will come across. With a bit of configuration, you can point nearly any calendar client or app, to other online repositories such as Google, EteSync, Nextcloud, Calendarly or Teamup. Make sure you can save your entries offline.

### Social Media
This is a hairy one because contributions to social media are considered by many to be of a throwaway nature. And because social media belongs to someone else, the question arises as to whether or not your contributions are worth saving, notwithstanding whether your contributions can actually be saved offline, then restored back onto someone else's system (like Facebook), it then begs the question, can it be done? My initial thoughts on that would probably lean towards 'no', you won't be able to.

If you use an **image library service** (like having an account on imgur), does that mean you have all of your images saved offline as well? I hope you do and I assume that you do. If not, make it happen.

### Offline Backup
The best, easiest and cheapest backup strategy for your data is to use a USB hard drive attached to your desktop or laptop, or a higher specced NAS Drive attached to your home WIFI system as network detectable device via IP Addressing. Anything over 4tb will not cost an arm or a leg. I have two Western Digital USB drives: one is a 4tb drive, the other a smaller 500gb drive. All of my content data lives on there. If worst comes to worst, like a house fire or some such, I can quickly grab them and depart the house using my Home Evacuation Procedure.

## Feedback
If any of you have your own backup solution that works for you and consider it might be useful for others, then hook up and drop in comment below.