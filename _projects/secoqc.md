---
layout: page
title: SECOQC
description: the first metropolitan quantum key distribution network, Vienna 2008
img:
importance: 1
category: AIT
related_publications: true
---

[SECOQC](https://en.wikipedia.org/wiki/SECOQC) (*Secure Communication based on Quantum Cryptography*) was an EU research project (2004–2008) that brought together 41 research and industrial organisations to turn quantum key distribution from a laboratory point-to-point link into a usable *network*. The result was a trusted-repeater QKD network with eight links spanning Vienna and St. Pölten, operated for the first time in 2008 and demonstrated publicly at the SECOQC conference in Vienna in October 2008 — including one-time-pad encrypted phone calls, an AES-protected video conference across all nodes, and key rerouting around failed links.

The Austrian Institute of Technology (then ARC) was a central partner and built the networking layer: the node software that sits on top of the heterogeneous QKD devices, manages the key stores, routes keys through the network and exposes them to applications. I worked on exactly that part from 2006 to 2012, first as a contractor during the build-up to the 2008 demonstration (Linux, Python and C), and afterwards on maintenance and further development of the open-source QKD software stack.

The network is described in {% cite peev2009secoqc %}; the later software releases in {% cite maurhart2012qkd maurhart2013qkd %}.
