---
title: '[DRAFT] How I am using AI for learning'
description: 'AI for learning'
date: '2026-05-24T21:45:55-03:00'
draft: true
heroImage: '/src/assets/figure/lotus.png'
showHeroImage: true
tags:
  - 'purpose'
comments: true
sidebar:
  enable: true
  toc: true
  relatedPosts: true
---

### AI friends: Learning, Searching, Experimentation

While it was not my original intention, my homelab journey pretty much coincided with the rise of OpenClaw and other agents, and the release of some very interesting tools at the AI space.  At the same time, ChatGPT was my go-to assistant for setting up my homelab.  And I am really glad I did it like that.  I would encourage anyone dabbling with any new technology, but especially linux, servers and architecture, to try to use AI as a search and/or learning tool.

I have used linux in many shapes and forms before, but it was never my daily driver for long. And if you tried setting up any linux machine before (server or desktop), you know you probably will end up googling a lot, and troubleshooting. I love the troubleshooting process, but I am really glad we have AI now: instead of spending hours crunching through stackoverflow pages, ChatGPT just gave me an answer and a pointer. I sill wrote all commands and files myself, and asked the AI to explain to me why the solution worked, and I think that was a great tool and even better than a lot of random stackoverflow commands.

So as I had already been using AI like that, when I saw OpenClaw I was instantly struck with all the possibilities.  The ability to have an AI running as a self-hosted service, but connected to a telegram bot, surefl.  So, pretty quickly, a lot of my attention with my homelab went towards that.

I installed openclaw in docker, and had to learn a lot about how to build from a git clone, and also working with volumes and networks inside docker.  I wanted my agent in OpenClaw to have very limited access to folders and apps, and setting it up was a lot of fun.
