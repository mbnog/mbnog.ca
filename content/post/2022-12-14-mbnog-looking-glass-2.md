---
layout: post
title: MBNOG Looking Glass 2.0
subtitle: ... so popular we revamped it!
tags: [bgp, announcements]
date: 2022-12-14
---

We now have a shiny new BGP Looking Glass! [MBNOG Looking Glass 2.0](https://lg.mbnog.ca) was launched just today.

This new looking glass is based on the exact same one that NLNOG runs on the [NLNOG Ring Looking Glass](https://lg.ring.nlnog.net), which is using a brand new BGP Looking Glass API in OpenBSD 7.2 to pull live routing information without having to scrape.

Because OpenBSD's looking glass is so "defacto" and supports really useful things like `source-as` and `detail as`, we are also making the backend OpenBSD looking glass available directly as well at [lg2.mbnog.ca](https://lg2.mbnog.ca).

If you run a network with full or partial routes (more than default only) MBNOG wants to peer with you. More information is available on the [Looking Glass](/looking-glass) page. 

