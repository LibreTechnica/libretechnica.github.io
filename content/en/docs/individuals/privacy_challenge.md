---
title : "Privacy Challenge"
description: "Privacy Challenge"
lead: ""
date: 2020-10-06T08:48:45+00:00
lastmod: 2020-10-06T08:48:45+00:00
draft: false
menu:
  docs:
    parent: "individuals"
weight: 130
images: []
---

Digital Privacy is more important now than ever before.  Countless concessions of our personal data in exchange for convenient online services have eroded our awareness of what others know about you.  By taking this challenge, you can significantly reduce the amount of information that is collected about you and your online activities.

--------------------
### Level 1. Switch to a secure messaging app

Most of us don't give a second though to what we use to message our friends and family.  "They all use WhatsApp/iMessage/Facebook Messenger, so I should, too.  Right?"  The sheer gravity of those aforementioned services' user bases is often large enough to overcome any reservations to installing them.  

But consider this... you will never know how those messaging apps work, nor _can_ you ever know.  That's because those apps are completely closed-source.  Are their apps sending personal data to their servers outside of your conversations?  Like perhaps your precise location, advertising data, and browsing history?  This [article](https://www.forbes.com/sites/zakdoffman/2021/01/16/stop-using-facebook-messenger-after-whatsapp-vs-apple-imessage-and-signal-privacy-backlash/) from Forbes answers those questions with all the scary details.

While you may have heard that some of these apps use end-to-end encryption (E2EE) on their conversations (meaning that only you and the recipient are able to see the contents of your messages), it's simply not worth using them even for their extraneous data collection alone.  For this reason and many others, it's highly recommended to switch to an open-source, E2EE messaging apps like [Signal](https://signal.org/).

Signal let's you send messages, make audio and video calls, and even set disappearing messages.  On top of that, the app is developed by the non-profit Signal Foundation which doesn't have an incentive to sell any of your data.  All while being open-source so you can verify everything we just said. Check out some great content about Signal including a Signal Configuration and Hardening Guide from [PrivacyGuides.org](https://www.privacyguides.org/en/real-time-communication/#signal).

--------------------
### Level 2. Block Ads and Trackers

When you type in www.askjeeves.com into your address bar and hit enter, your browser doesn't know where on the Internet to find that server is (its IP address).  So your computer calls out to a DNS (Domain Name System) server, which is like the phonebook of the internet.  Your computer says "Hey, DNS server, what's the IP address for askjeeves.com?", and the DNS server replies with "askjeeves.com is located at 146.75.38.114".  Then your browser connects to 146.75.38.114 and you search away!

Generally, your DNS requests are handled by your Internet Service Provider.  While ISP's can't see what you're doing *at* the websites you visit, they still know and likely log what sites you visit.  Not only that, but trackers and malware are constantly making requests behind your back!  You can hinder all this by using an encrypted DNS service or by putting your very own ad blocker on your network.  

Privacy Guide has some great insights on how to use an encrypted DNS filter like AdGuard or NextDNS (see [https://www.privacyguides.org/dns/](https://www.privacyguides.org/dns/)).  To go fully self-hosted, you can set up your own ad blocker called [Pi-Hole](https://pi-hole.net/).

--------------------
### Level 3. Use a Virtual Private Network (VPN)

A virtual private network (VPN) is a very useful tool in the fight for data privacy.  To oversimplify, a VPN is like a special tunnel between your computer (or phone) and another computer located elsewhere.  That other computer has access to the internet, so you can sort of "teleport" your internet communications from where you are to where you would like to be.  Here are some examples of common uses:

- You can make your computer appear that it's in the U.K. so you can watch TV shows only available on British streaming services.  
- If you're using a Wi-Fi network that you don't control, like at a coffee shop or at McDonald's, a VPN will secure your internet traffic from others on the Wi-Fi network and the network operator.
- While the above examples secure your traffic out to the internet, you can also make a VPN tunnel into your home network as well.  This can allow you to safely access resources on home network like a file server or movie library.

--------------------
### Level 4. Delete Facebook and Twitter

Social media companies are known for some of the worst abuses of digital privacy.  With their vast stores of data points on their members, they use this information to target you with advertisements, addictive triggers, and rage-bait for the sake of profit.  It's important to remember that if a service is free, then YOU are the product.

Privacy is the ability to control the information about yourself.  Social media works tirelessly to dispossess you of that ability, even if don't have an account with them. Their wide network of trackers feed your deeply personal attributes and behaviors into their data centers so that they can nudge you into acting in the interests of their advertisers and, in some cases, influence your political and electoral activities.

While much of the past and present data that social media companies have on you may be retained forever, deleting your accounts will help diminish their power and control in your life; and will reclaim the right to your own future. 

--------------------
### Level 5. De-Google your life!  

This one is even more difficult than deleting social media.  Google had such deep penetration into our lives, that living without Google is tantamount to living in a cave.  It doesn't help that some of their products actually pretty good only by virtue of their massive surviellance aparatus.  (Google Maps can only tell you traffic is gridlocked on your route to work becuase they have a GPS-enable tracking beacons in most of the cars- smartphones!)  

But all is not lost when you remove Google from your life.  When more users adopt alternative products and services, they weaken Google's power over the mass market.  They make those alternatives better.  They shift market power to more ethical businesses that actually respect your privacy.  

So let's get started.  A great resource for de-Googling your life is [PrivacyGuides.org](https://www.privacyguides.org/tools/).  They list multiple privacy-respecting recommendations for nearly all aspects of our digital lives.  Here are some good alternatives to start with.

- Search Engine - [DuckDuckGo](https://duckduckgo.com/), [Brave](https://search.brave.com)
- Email - [ProtonMail](https://proton.me/mail), [Tutanota](https://tutanota.com)
- Web Browser - [Firefox](https://firefox.com/), [Brave Browser](https://brave.com/)

#### Secure Mobile Operating Systems

Wanna get Google out of your Android phone?  These de-Googled operating systems are based on the Android Open Source Project (AOSP) and feature tons tweaks and security enhancements.  The ironic thing is that they generally only work on Google Pixel phones since they're the only devices that allow you to put a custom OS on them.

- [GrapheneOS](https://grapheneos.org/)
- [CalyxOS](https://calyxos.org/)

*FOSS Bonus* - Only use free and open-source apps on your phone.  You can get them through [F-droid](https://f-droid.org/) or the [Neo-Store](https://github.com/NeoApplications/Neo-Store).

--------------------
# Resources

## Education

- [EFF: Surveillance Self-Defense](https://ssd.eff.org) - "Expert guide to protecting you and your friends from online spying."

- [EFF: Security Education Companion](https://sec.eff.org) - Resources for teaching digital security to friends and neighbors. 

- [https://www.cryptoparty.in/learn](https://www.cryptoparty.in/learn).

- [LevelUp](https://www.level-up.cc/) - "LevelUp is a living project intended to provide support to, and enable creation of resources and sharing of knowledge within, a growing network of individuals providing needed digital safety training and education to users of technology worldwide."

## Privacy-focused groups

- [Citizen Lab](https://citizenlab.ca/) - "The Citizen Lab is an interdisciplinary lab focusing on research, development, and high-level strategic policy and legal engagement at the intersection of information and communication technologies, human rights, and global security."

- [Privacy International](https://privacyinternational.org/) - a group to "protecting democracy, defending people's dignity, and demanding accountability from institutions who breach public trust."

- [Digital Defenders Partnership](https://www.digitaldefenders.org) - "The Digital Defenders Partnership offers support to human rights defenders under digital threat, and works to strengthen local rapid response networks."  

## Security-focused groups

- [Rarenet](https://www.rarenet.org) - "Rarenet (Rapid Response Network) is an active network of organisations and individuals that are working on digital emergency response. 

- [CiviCERT](https://www.civicert.org) - "CiviCERT is a network of Computer Emergency Response Teams (CERTs), Rapid Response teams, and independent Internet Content and Service Providers who help the civil society prevent and address digital security issues."

    - [Digital First Aid Kit](https://digitalfirstaid.org/) - "The Digital First Aid Kit is a free resource to help rapid responders, digital security trainers, and tech-savvy activists to better protect themselves and the communities they support against the most common types of digital emergencies. "

##	Comprehensive Guides

- [Restore Privacy](https://restoreprivacy.com/privacy-tools/) - Blog and lists of resources related to privacy and security.

- [The Hitchhiker’s Guide to Online Anonymity ](https://anonymousplanet.org) - "a maintained guide with the aim of providing an introduction to various online tracking techniques, online ID verification techniques, and detailed guidance to creating and maintaining (truly) anonymous online identities." NOTE: This site appears to be currently down due to the main author's situation in Kyiv.  You can see an archived version of the site at: https://web.archive.org/web/20220227172107/https://anonymousplanet.org/ 

- [Security in a Box](https://securityinabox.org/en/) - Digital security tools and tactics

- [*privacy not included](https://foundation.mozilla.org/en/privacynotincluded/) - Guide from Mozilla that lists privacy concerns for many well-known products.


## Lists of Software and Services

- [Privacy Guide](https://www.privacyguides.org) - "Privacy Guides is your central privacy and security resource to protect yourself online." Privacy Guide was formerly [privacytools.io](https://www.privacytools.io/).  [r/PrivacyGuides/ on Reddit](https://www.reddit.com/r/PrivacyGuides/) is also a good resource.

- [Awesome Privacy](https://github.com/pluja/awesome-privacy) - A "list of free, open source and privacy respecting services and alternatives to privative services."

- [PRISM Break](https://prism-break.org/) - Tools to help you "Opt out of global data surveillance programs like PRISM, XKeyscore and Tempora."

- [Switching.Software](https://switching.software) - List of privacy-conscious alternatives to well-known software.

- [(Cryptoparty) Tools](https://www.cryptoparty.in/learn/tools) - a curated list of tools to improve your security, privacy, and anonymity.

--------------------
