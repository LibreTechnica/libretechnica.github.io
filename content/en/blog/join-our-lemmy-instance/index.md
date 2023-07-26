---
title: "Join our Lemmy instance"
description: "Come join LibreTechnica in the Fediverse at our very own Lemmy instance.  There you can explore hundreds of communities on the decentralized alternative to Reddit."
lead: "Come join LibreTechnica in the Fediverse at our very own Lemmy instance.  There you can explore hundreds of communities on the decentralized alternative to Reddit."
date: 2023-07-10T00:00:00+01:00
lastmod: 2023-07-10T16:00:00+01:00
draft: false
weight: 40
images: ["480px-Lemmy_Logo.svg.png"]
contributors: ["LibreTechnica"]
---
![Image](480px-Lemmy_Logo.svg.png "Lemmy Logo")

# TLDR

Lemmy is a free-and-open-source and federated link aggregator like Reddit.  We set up a Lemmy instance at [https://libretechni.ca](https://libretechni.ca).  Sign-ups are open and and we're ready to start creating communities.

# Background

## The Reddit APIcalypse

In April of 2023, Reddit announced many changes to their API access policies and pricing.  Many of these changes hurt third-party app developers who had to shut down their apps or pay exuberant API fees.  A backlash ensued, moderators protested with blackout, and the Reddit's CEO, , doubled down on their changes.  Here's a good article summarizing it all: [Why everyone is freaking out about the Reddit API and blackout right now](https://www.digitaltrends.com/computing/reddit-api-changes-explained/).

## What is Lemmy

[Lemmy](https://join-lemmy.org/) is to Reddit what [Mastodon](https://joinmastodon.org/) is to Twitter.  As a federated service, you are free to sign up at one instance and view content and updates from another.  The Reddit APIcalypse, as it's become known as, has caused a massive wave of early adopters to the Lemmy platform, similar to when Elon Musk's changes to Twitter cause many users to move to Mastodon.  

The [History of Lemmy](https://join-lemmy.org/docs/users/07-history-of-lemmy.html) shows that Lemmy shares many of the same genes as LibreTechnica, so it was almost inevitable that the two philosophy and the platform would meet. So with that, the domain [libretechni.ca](libretechni.ca) was purchased and pointed to a brand new fresh Lemmy server!  This is so fresh, the server was up the Friday night before this blog post.

## How does it compare to Reddit?

A Lemmy site looks and feels just like Reddit, but without ads or exclusive premium accounts.  Link aggregation and conversation trees a the main focus and there's not much more to that.  Everything should feel intuitive if you're coming from Reddit.  The project is still relatively new, but it does its basic functions pretty well.  Here are a few more selected features ripped from [project website](https://join-lemmy.org):

- Self hostable, easy to deploy, via Docker, or Ansible.
- Clean, mobile-friendly interface.
- Mobile apps for iOS and Android.
- User avatar support.
- Full vote scores (+/-) like old Reddit.
- User tagging using @, Community tagging using !.
- Notifications, including via email.
- NSFW post / community support.

# Getting Started

[LibreTechni.ca](https://libretechni.ca) was created to let you experiment with federated services, so feel free to join and start exploring!

## Choosing a Server

Two popular lists of Lemmy servers/instances are at [Awesome Lemmy Instances](https://github.com/maltfield/awesome-lemmy-instances) and [the-federation.info Lemmy Instances Page](https://the-federation.info/platform/73).  You can do join one of the larger instances that cater to a breadth of interests or you can an instance that is for attracts a certain interest, like solarpunk ([SLRPNK](https://slrpnk.net)) for example. Keep in mind that regarless whichever instance you choose to be your home instance, you'll still be able to see content from other instances becuase it's federated.  That's the whole point!  Of course, you'll can always find d home at [LibreTechni.ca](https://libretechni.ca).  

## Discovering communities

Sub-reddits are called **Communities** in Lemmy.  When you click on "Explore Communities" on a Lemmy instance, you will see three tabs.

- Subscribed - These are the communities you have susbscribed to, obviously.
- Local - These communitites are local to the instance you're viewing. Or, if you're using a mobile app, the instance that you're logged onto.
- All - Here are communities across multiple instances.  However, a community will only show up on this list once a user searches for it for the first time.  For example, searching for "privacy" on the https://libretechni.ca instance only shows a few communities on that topic (as of the date of this post).  But searching for "privacy" on https://lemmy.world shows a wealth of commuhities across numerous instances.  Over time, this list of will grow as subscribers who seek out and subscribe to more communities make their home instance "aware" of them.

As you go about looking for Communities to subscribe to, I recommend checking out some of the larger instances, searching for communities on there, and then subscribing from your home instance.  Start from one of the lista pages of Lemmy instances mentioned in [Choosing a Server](#choosing-a-server).  You can also use one of these below to find communities.
- [Lemmy Community-Browser](https://browse.feddit.de)
- This [post](https://lemmy.world/post/143683) on lemmy.world listing many Reddit equivalents.

## Subscribing

Here's a little rundown on how to find and subscribe to, say, a Community for cooking.  

1.  Go to [Awesome Lemmy Instances](https://github.com/maltfield/awesome-lemmy-instances).  The instance [Lemmy.world](https://lemmy.world/) has a lot of users, so go there and click on "Explore Communities".
2.  Search for "cooking".  Check out some of the Communities and see which one(s) you like.  The subscriber count there indicates how many subscribers the community has _from the local instance_. That's why those numbers don't match when you view the community from its home instance.
3.  Copy the link.  Note: these links are all views from the current instance.  So if you like "Science of Cooking@mander.xyz" community, the link on the search page will take you to **https://lemmy.world/c/cooking@mander.xyz**.
4.  Go back to your home instance and go to "Explore Communities".  Paste the copied URL in the search box, but take out the first part of the URL "https://lemmy.world/c/" and leave in "cooking@mander.xyz". Add an exclamation point to the beginning so it looks like "!cooking@mander.xyz".  Click "Search" and the Community will appear.
5.  Follow the link and subscribe.  This link will take you to "https://**libretechni.ca**/c/cooking@mander.xyz".

If no one else has subscribed to that Community before, the page might be blank.  But over time, the instance will add more posts and comments as they're federated to your home one.  So if you don't want to check out every Community on it's home instance, just go crazy on subscriptions and the content will steaadly come in after a day or so.

## Posting

Go to the Community you want to post in and post!  Just be sure you're logged into your home account.

## Learn More

Learn more in the [Lemmy Documentation](https://join-lemmy.org/docs/index.html) which includes information for users, admins, and contributors.
