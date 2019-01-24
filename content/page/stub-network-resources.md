---
layout: page
title: Stub Network Resources
subtitle: Default Route Networks
---

Abridged from [Wikipedia](https://en.wikipedia.org/wiki/Stub_network):

> A stub network is a somewhat casual term describing a computer network, with no knowledge of other networks, that will typically send much or all of its non-local traffic out via a single path, with the network aware only of a default route to non-local destinations.

We will refer to those BGP networks which use a default route only, or a default plus a selection of routes (perhaps from an IX). Networks which do not run in the default-free-zone (DFZ).

## List of things to be written about

1. using ecmp to load balance more than one default route (including 2 default routes of inequal AS-path length)
1. taking full routes + default and doing your own filtering
1. expanding from 1 to 2 BGP routers
1. expanding from 2 to n BGP routers
1. interacting with your IGP (OSPF, EIGRP)

## Web resources

*	[NLNOG BGP Filter Guide](http://bgpfilterguide.nlnog.net/guides/)

