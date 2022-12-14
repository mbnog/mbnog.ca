---
layout: page
title: Looking Glass
subtitle: A Manitoban BGP View
---

The Manitoba Network Operators Group operates a BGP multihop looking glass with a distinctly Manitoban view of the Internet.

[MBNOG Looking Glass 2.0](https://lg.mbnog.ca/)

[MBNOG Looking Glass 2.0 Backend OpenBSD](https://lg2.mbnog.ca/)

[Old MBNOG Looking Glass 1.0](https://lg.mbnog.net/)

## Peering

To peer with the looking glass please setup a session with the looking glass using the settings below and contact lookingglass@mbnog.ca

### LG Peering Settings:

- AS: 65204
- eBGP Multihop
  - default (32 hops) should be enough in most cases
- IPv4:
  - IP: 192.160.102.94
- IPv6:
  - IP: 2620:132:3003:520::2
- `ADD_PATH` is supported, feel free to enable on your side.

MRT rib and update dumps will be saved at some point.
