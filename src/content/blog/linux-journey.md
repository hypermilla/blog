---
title: 'My Chaotic Journey to Daily Driving Linux in 2026'
description: 'A personal history of trying to daily drive Linux, from Live CDs and Slackware to Fedora, Hyprland, NVIDIA, Proton, and AI-assisted troubleshooting.'
date: '2026-05-24T21:45:55-03:00'
draft: true
heroImage: '/src/assets/figure/lotus.png'
showHeroImage: true
tags:
  - 'linux'
  - 'fedora'
  - 'kde'
  - 'hyprland'
  - 'nvidia'
  - 'wayland'
  - 'proton'
  - 'desktop'
comments: true
sidebar:
  enable: true
  toc: true
  relatedPosts: true
---

# My Chaotic Journey to Daily Driving Linux in 2026

[Open with the present-day hook: you recently started daily driving Linux, and this time it actually stuck. Mention that you had known Linux for years, but this was the first time it became your real everyday desktop.]

[Set the emotional thesis: this is not just about Linux becoming usable, but about your computer feeling personal, controllable, and pleasant again.]

## The Setup I Wanted Linux to Handle

Before we go on, my current setup:

- Desktop with 2 LG 4k60 HDR10 27" monitors
- AMD Ryzen 7 5800X
- RTX 3070 8GB
- 32 GB RAM
- Fedora KDE Plasma Desktop 44
- Hyprland

[Explain why this setup matters: NVIDIA, multiple 4K monitors, HDR, gaming/dev builds, Wayland, screen sharing, and drawing tablets are exactly the kinds of things that made Linux feel risky before.]

[I have been wanting to try Hyprland for longer than I would like to admit, but many problems stood in my way. But we will get there.]

## My First Linux Memories

I was born in 1989, and as a lot of people from my generation, I grew up watching computers and the internet grow and change the world. I was always on my PC and online as much as I could, since I can remember. And somehow, I learned about Linux.

Back in the early 2000s I remember I used Live CDs with Ubuntu, Mint or Slax, which became my favorite, as a recovery tool for Windows.

My grandmother would sometimes bust her PC, often by shutting it down by unplugging the electricity cord, and it wouldn't turn on anymore. I would use a live CD with Slax to backup her files or run recovery tools, to avoid her losing all her data.

[Add a short reflection: Linux first appeared in your life less as a main OS and more as a strange, powerful rescue tool.]

## The Slackware Adventure

The first time I installed Linux was with a friend from high school. We used to hang out and talk about nerdy stuff and play video games, and he was very interested in programming at the time.

We had been talking about Linux for a while and one day he invited me to his house for a crazy adventure he wanted help with: installing Linux. And not any Linux, he chose to try Slackware, which was going to be a harder installation.

At that time, that was the only computer in his house, as would be the case for most households, so that was a big commitment. He did a lot of preparation and I remember he printed, in paper, the whole installation guide. This was before smartphones, so there was no other way.

In the end, it worked out. And we had sooooo much fun.

[Add why this memory matters: Linux felt risky, physical, irreversible, and exciting. It was not a casual app install.]

## The Mint Dual-Boot Years

I don't think I got to trying a real Linux installation on my PC until around 2008. I got a new PC and did a dual-boot Windows + Mint.

I wanted to daily drive Mint, but between design school and lots of apps that didn't work, I only used it to try things out, and the experience was riddled with issues and infinite Stack Overflow tabs.

I remember one day I got home from university to find my father yelling at me. He had tried to use my PC to print something, and Mint booted automatically instead of Windows, so obviously that didn't work.

[Add the broader point: at that time, the problem was not only Linux itself, but the app ecosystem, printers, design tools, and sharing a household computer with people who expected Windows.]

## Why Manjaro Failed for Me in 2021

The last time I tried daily driving Linux was in 2021. I wanted to run Manjaro.

I had just bought my current machine, equipped with 2 4K monitors and an RTX 3070. I tried a lot, spent hours in Stack Overflow, and gave up having Manjaro work with my NVIDIA and monitors setup.

[Insert your memory of NVIDIA drivers back then: choosing between open-source and proprietary drivers, proprietary drivers being better for the hardware but also more fragile/confusing.]

[Insert what specifically failed or felt exhausting: monitors, resolution, scaling, driver install, boot issues, Wayland/X11, black screens, or whatever you remember.]

[Close the section with the feeling: you did not stop because you disliked Linux, but because the cost of making it work was too high.]

## Why Windows Stopped Feeling Like My Computer

Now in 2026, I was getting really tired of using Windows.

I do game dev in my daily job, running a small game studio creating PC games. Our main platform is Steam, and most of the time our builds are Windows-only. That means I can do some of my work on other platforms, but eventually have to go back to Windows to test builds.

[Insert why Windows was annoying you: interface, ads, lack of control and customization, performance, distance from macOS/Unix, bad terminal experience.]

[Insert the webdev/AI terminal angle: you were doing more work in terminals, web projects, homelab, AI tools, etc., and Windows felt misaligned with that.]

I had been doing more and more work on my MacBook Pro and got sick of going back to Windows.

[Insert comparison with macOS: not that you wanted macOS exactly, but you wanted a system that felt cohesive, scriptable, keyboard-friendly, and pleasant.]

So I decided to give Linux a try. It had been years since I last tried, and I was very excited about it: recently I had been working on my homelab with Ubuntu, and installed Omarchy on an old laptop.

I thought this could finally be the time I could run Linux well on my desktop, and could even play Steam games on it with Proton.

## Why I Started With Fedora KDE

So I used a lot of AI to guide me through the process: I definitely wanted Hyprland, so I needed a distro with native Wayland, preferably.

My initial idea would be Arch, but I didn't want to fall into a vortex installing and setting it up, and then end up not using it so much. So I went with ChatGPT and Claude's recommendation: Fedora.

Fedora felt like the best balance for me: a modern desktop stack, strong Wayland support, and a documented path for NVIDIA drivers.

KDE Plasma also looked like a great place to start, with lots of customization I could tweak easily, before diving into Hyprland.

[Insert your two-step strategy: first get used to Linux as an OS, then later get used to Hyprland as a new desktop/window manager.]

[Insert why KDE mattered aesthetically: themes, customization, dock, top bar, tray, macOS-like setup, making the system look nice enough that you would want to stay.]

Turns out the installation was super easy, my NVIDIA and monitors were working almost out of the box this time.

## What Changed in 2026

[This section should explain why this attempt worked where 2021 failed.]

[Insert driver/support angle: better overall hardware support, better NVIDIA situation, easier driver installation, Wayland being more mature, Fedora being current.]

[Insert careful factual note if you want: NVIDIA released open GPU kernel modules in 2022, and newer driver series made the Linux NVIDIA situation feel less obscure for supported GPUs.]

[Insert ecosystem angle: Steam/Proton, browser-based apps, Electron apps, Figma, Slack, Gmail, ClickUp, etc.]

[Insert personal angle: your own app needs changed; you no longer depend heavily on Photoshop/Illustrator in the same way.]

## What AI Changed About Troubleshooting Linux

[This is one of the most important sections.]

[Insert the contrast: before, troubleshooting meant 200 tabs, old forum posts, Stack Overflow threads, and commands without context.]

[Insert how you used AI during installation: "I have problem X", AI suggests hypothesis, command, log to inspect, or package to install.]

[Insert why Linux works especially well with AI: lots of public knowledge, stable commands, well-known patterns, decades of docs and forum posts.]

[Insert the important nuance: AI did not magically make Linux simple; it reduced the cost of troubleshooting and gave you better starting points.]

[Insert examples: NVIDIA, monitors, audio, Huion, Wacom, dotfiles, stow, documentation.]

[Optional idea: Linux desktop could benefit from an integrated AI assistant as an educational/troubleshooting tool for new users.]

## Steam, Proton, and Work

Testing games with Proton also worked better than expected. I was actually under the impression it would not work well, and I had some troubles: a few times the game just crashed on a black screen, but that could have been many things, and those were development builds.

All the games I tried on Steam worked pretty well so far. I have been using Proton Experimental on Steam, and that has been working well.

[Insert the concrete turning point: you created two users, one personal and one for work, and spent more than a week working and doing personal projects without logging into Windows.]

[Insert that your company game ran on Steam right away, and that made the switch feel possible.]

[Possible sentence idea, rewrite in your voice: "At some point I realized I was not testing Linux anymore. I was just using my computer."]

## From Magnet to Hyprland

[Start with Magnet on macOS: you used it for years, love 70/30 layouts, browser + terminal, editor + Telegram, etc.]

[Explain that this was also something you missed on Windows.]

[Explain that you started in KDE trying to reproduce that workflow.]

[Mention the KDE tiling plugin you tried. Placeholder until you confirm the name.]

[Explain that the plugin was a good bridge, but still not exactly what you wanted.]

[Then explain the realization: if you were trying to recreate a tiling window manager inside KDE, maybe it made more sense to go straight to Hyprland.]

[Insert r/unixporn/videos/inspiration context, but keep it personal rather than aesthetic-only.]

[Explain that Hyprland clicked quickly because you already liked keyboard-first workflows and shortcuts.]

In a few weeks I was already daily driving Hyprland.

[Insert that KDE remained available as fallback at login, but after installing Hyprland you basically never logged back into KDE.]

## What Still Does Not Work Perfectly

[This section gives the post credibility.]

[Insert Steam/game dev issues: your own game sometimes crashes or black screens.]

[Insert Hyprland popup/window issues: Bitwarden, Google Meet picture-in-picture, small floating windows opening huge or weird.]

[Insert browser/window issue: some links opening in new browser windows instead of the current one, probably Zen Browser rather than Linux.]

[Insert screen sharing: Google Meet mostly works, selecting the right window can be weird in Hyprland, Discord did not work well, Vesktop fixed it.]

[Insert audio issue: speakers popping, fixed with AI help, tools/config/frequency/bandwidth settings.]

[Insert dotfiles issue: useful but sometimes create their own problems.]

[Keep the tone honest: things are good, but not frictionless.]

## Drawing Tablets, Bluetooth, and Other Surprises

[Insert Huion Kamvas 20 Pro story: worked well thanks to AI help, now often used as a third monitor, but drawing works too.]

[Insert Intuos5 Pro story: official support not great, community tools were excellent, pressure configured.]

[Insert Bluetooth and Corsair Virtuoso: headset mostly worked out of the box, only audio frequency tweaks.]

[Insert broader reflection: you are in a favorable position because you do not currently depend on one irreplaceable Windows/macOS-only app.]

## Would I Recommend Daily Driving Linux in 2026?

[Answer yes, but not universally.]

[Recommend it for people who enjoy understanding their tools, mostly use browser/cross-platform apps, are willing to troubleshoot, and care about customization/control.]

[Warn against it for people who need specific Adobe apps, zero troubleshooting, or exact compatibility with every work tool.]

[Insert your honest position: for your current life, work, tools, and tolerance for tinkering, it finally makes sense.]

## Feeling at Home on a Computer Again

I have basically not logged back into Windows since, save for a few times to get some backup files, or when I really needed to play a build and it was crashing and I didn't have time to troubleshoot.

[Final personal conclusion: not just "Linux works now", but that your desktop feels yours again.]

[Close with the broader emotional idea: after years of tolerating operating systems, this setup makes you want to shape, understand, and live inside your computer again.]
