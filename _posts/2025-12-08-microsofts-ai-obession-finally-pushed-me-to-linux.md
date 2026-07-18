---
title: "Microsoft's AI Obsession Finally Pushed Me to Linux Full-Time"
date: 2025-12-08 08:00:00
last_modified_at: 2026-07-18 08:00:00
categories: [Blog]
comments: false
tags: [linux, windows, ai, os, linux mint, gaming, privacy]     # TAG names should always be lowercase
---

## The Breaking Point: AI
What finally made me delete Windows from my personal computers? AI. Specifically, Microsoft's insistence on pushing unwanted AI features onto my personal desktop. So, after years of toying around with the idea, I finally took the leap and replaced Windows with Linux as my primary and only operating system.

About a month ago, I was reading the most recent release notes for Windows 11 and realized that almost every change or update was a new AI feature. Sure, there were a few mentions of bug fixes and security patches, but everything else was "Copilot this" and "AI component that." This bothered me for two reasons:
1. Privacy: remember Microsoft Recall? Exactly. I could probably end the blog here. I want my personal data and files to stay private, and having built-in AI agents with direct access to my files and OS doesn't fit the bill.
2. Control over what's running on my devices: I don't want a bunch of AI features baked into the OS I use every day and not have the option to easily remove them. I want to be choosing when and where to use AI.

## A Decade of Experimenting With Linux
I'm not new to the world of Linux. My first encounter with Linux was over 10 years ago, when a friend showed me his new laptop, freshly installed with Ubuntu, on the bus ride home from school. I'd never seen anything like it and was immediately hooked. I knew very little about computers at the time, so I followed some online tutorials and ended up installing Ubuntu to dual boot on an old Windows XP desktop we had sitting at home. Every time the system would boot, the Grub menu would glitch and only show a blank screen before booting into Ubuntu. I was convinced for months that there was no way to get back into Windows XP, until one day I stumbled onto a video talking about using the Grub menu for dual-booting. It's crazy looking back now at how little I knew back then.

In the years since then, I have dual-booted several distros with Windows, run headless servers to host my homelab (including a full Proxmox server), and spun up countless Kali VMs for pentesting and various school projects. What I hadn't done, until now, is completely switch to Linux on my laptop or desktop.

These are my three main reasons I put off switching to Linux for so long:
1. Gaming
2. Microsoft Office Suite (and other Windows dependent apps)
3. Comfort

### Gaming
Subpar gaming performance on Linux was always a big deterrent for me. I'm not a huge gamer, but the games I play used to not perform as well on Linux as on Windows. I remember trying to play one game on Linux in 2017 after the developers released a native Vulkan port, and it performed so badly compared to the Windows version that I couldn't stand playing it. Recently, after hearing about advancements in Linux gaming like [Proton](https://github.com/ValveSoftware/Proton) and the [Steam Deck](https://store.steampowered.com/steamdeck), I was willing to give gaming on Linux another shot. That same game now performs just as well on my computer running Linux as it does on Windows.

### Microsoft Office
I relied heavily on Microsoft Word and Excel during college to write reports and couldn't tear myself away from their ecosystem. LibreOffice works well enough for my personal needs these days, now that I'm not in college, and alternatives to Word Online like Google Docs have improved greatly (privacy issues aside). That being said, Excel is still the premier spreadsheet software in my opinion and I miss the smoothness of the native Windows app. LibreOffice Calc just isn't as refined as Excel and while the UI can be tweaked to look and function more like Excel, it just isn't as good.

### Comfort
I grew up using Windows everywhere and became very comfortable with it. I know how Windows works and how to troubleshoot issues, so why would I move to an unfamiliar OS and risk bricking my main system because I didn't understand it? To be fair, early on I'd broken several Ubuntu installs by messing up the APT repos and other system config files, and my troubleshooting skills at the time were not what they are today. My Linux knowledge and troubleshooting have come a long, long way since then. Moving completely over to Linux has still been a slight learning curve, but has been great for furthering my knowledge of how the platform works. I still wouldn't call myself an expert; after all, I am using Linux Mint, not Arch Linux.

## Linux Mint Just Works
I started off installing [Pop!_OS](https://system76.com/pop/) 22.04 from System76 because I'd heard it referenced a lot in tech videos and forums online. It worked well out of the box and I had no major issues at the start. After a couple weeks I started to notice that the desktop environment wasn't as refined as other distros I've used, and decided to switch to [Linux Mint](https://linuxmint.com/) when I learned that the next release of Pop!_OS would be switching to their own COSMIC DE (a custom desktop environment build by System76). I tested the beta release of COSMIC and was not impressed with the UI or running such a poorly supported DE.

Linux Mint was an easy choice for me. My first experience with it was Linux Mint 18 (~2016) and I immediately enjoyed the simplicity of the distro. I installed Linux Mint 22.2 about a month ago and was pleased to be dropped right back into the same experience I remembered, just refined more over time. The best way I can summarize my experience is that the OS doesn't get in my way, which is exactly how I want it to be. The entire OS has been stable and smooth from the start, without me needing to tweak it to get good gaming performance or set up a development environment.

## The Path Forward
My complete transition to Linux has been almost flawless (except for the issue with outdated graphics firmware) and I don't see myself switching back to Windows anytime soon, if ever. I could be convinced to reconsider my decision if Microsoft created a way for users to completely, and easily, opt out of and remove their AI features, but I won't be holding my breath waiting for that to happen.

I'm not against AI. AI has a lot of practical use cases and is something I use periodically. I just want to be able to choose when and where to use it, and most importantly, retain control over what personal data I'm giving to companies behind the AI products.
