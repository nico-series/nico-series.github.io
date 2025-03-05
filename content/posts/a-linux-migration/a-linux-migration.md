---
title: A Linux Migration
description: Recently I've been wondering if I should continue using Windows for my personal projects or try something else.
date: 2025-03-04
modified: 2025-03-04
draft: false
tags: [development]
---

# Priorities
For quite a long time, I've been a Windows user. I paint, I game, I use Microsoft staples like Visual Studio and Office. At work my story is more of the same, with the addition of Microsoft 365 and Teams. I'd say I've gotten pretty complacent with my apps _just working_ and Windows Defender taking care of preventing potential nasties from running loose on my machine.

Lately, I've been a bit less content with that arrangement. Like media, tools have _audiences_ or intended user bases. Tools as they are designed make assumptions about their users and cater to those assumptions. Windows assumes that its users prioritize convenience and are willing to exchange increasing degrees of autonomy and data for it. You can tinker with how Windows operates, but tinker-ability isn't its priority. If you are living in the Windows ecosystem you likely aren't really thinking about alternative desktops or audio or video drivers. Over the last few years I've come to value these things which are less prioritized more and more.
# Alternatives
This brings me to alternatives. I've used **macOS** on a few occasions for media and app development, and while it is nice for both I wouldn't say it satisfies my desire for tinkering. This leaves **Linux-based** operating systems, which have apparently changed dramatically since my college Unix and Ubuntu course in 2012 or 2013. From my position on the periphery, it seemed to have the reputation of being for specific development or infrastructure uses only. Scary! Not for beginners!

A decade later I am both not a beginner and the Linux space has become a lot more varied in what it offers, how it markets itself, and who it is for. Top 10 lists of distributions include suggestions for users coming from Windows or macOS, users that want to game, and those pursuing creative projects. If anything is discouraging, it is the overabundance of choice. Casually wiki-diving for the distributions and tech available, you can quickly end up with a map that looks like this:

{{< figure
  src="../linux-obsidian-local-graph.png"
  alt="A local graph in the Obsidian note-taking app showing how many topics tie back to the Linux kernel"
  class="ma0 w-75"
>}}

I built this map slowly over the course of months, and I can see how to someone else looking to get started with a migration it might look like a massive learning curve. I'll boil down what I've learned to a couple statements that are both more representative and more optimistic:
1. Learning as you go is perfectly fine
2. You should play with your tech, your PC is probably not going to explode
3. If you install something and don't like it, try something else
# Scooting on Over
~~Once I'd filled in my charts and become a SME~~ Once I'd decided I should just get on with it, I needed to tinker, specifically to install and run one of these distributions. The first step was identifying which apps I could bring with me and which ones you I couldn't. In my case, the only real casualty was **Corel Painter**, which used .riff files which I had to convert to something I could open with another app. I also used **Scrivener**, but **Wine** translation was available for it so in theory I'd be safe to leave those files be. _I backed everything I cared about up_.

I decided on a few options based on the following priorities:
- Versatility, it should be good for entertainment AND work
- Favor popular and supported distros to build confidence
- Customization should be encouraged

For me that resulted in 3 options:
1. **Linux Mint** for its friendliness to Windows users
2. **Pop!\_OS** for its friendliness to games and my NVIDIA GPU
3. **Fedora** on recommendation from a developer friend

There are 3 ways to run a secondary operating system: live boot from a USB, dual booting, and running in a VM, each with their own limitations. Briefly:
1. Local VMs are low commitment and good for quickly trying out many options but tend to be slow and limited in what hardware they can access
2. Live USBs are portable and can fully utilize hardware but require lightweight operating systems or else they will be slow
3. Dual booted OSs have full access to resources and will be the best performing but require a committed installation

My first experiment was with Mint: I ran it from a flash drive and surprise, surprise - Mint was slow. Not because Mint is slow, but because it was an inappropriate choice for a live USB. It was also familiar. I spent enough time poking around the desktop and menus to realize that maybe, with this change, I wanted to step a bit further from what I was used to.

My second experiment was with Pop. I decided I wanted to give it a fairer shake and actually run it from a partition on my machine rather than starving it on a flash drive as I had with Mint. I set up a small partition for Pop alongside my Windows installation partition and began the install. Pop comes with GNOME or (soon) **COSMIC**. It is an amicable install complete with GUI, hand-holding, and minimal questions. At this point I ran into two issues:
1. After playing with GNOME, I realized I was more interested in trying KDE
2. I could no longer access my Windows install

The first was a useful realization, but the second was and is a bit of an issue. I discovered at that point that Pop is in theory fairly easy to dual boot with Windows if you are using **EFI** partitions. _I did not do that._ I was using a legacy **BIOS** which I have not yet been willing to upgrade to **UEFI** out of fear of an incredibly unlikely but not unprecedented temporary and localized power outage. Universe, I would like to request a UPS for my birthday. 
# Pivoting to Arch
While building up courage to convert my BIOS to UEFI, I decided to go in a completely new direction and install **Arch Linux** on another drive. This is a complete pivot in that it is not even slightly beginner friendly, and it has also gone _surprisingly well_.

_To be continued_
