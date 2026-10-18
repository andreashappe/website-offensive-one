---
layout: page
title: Archistar
description: secure multi-cloud storage with secret sharing and Byzantine fault tolerance
img:
importance: 2
category: AIT
related_publications: true
---

[Archistar](https://en.wikipedia.org/wiki/Archistar) is a research project and software framework from the Austrian Institute of Technology, funded by the Austrian Federal Ministry for Transport, Innovation and Technology (2012–2014), for building secure distributed cloud storage. Instead of trusting a single provider, data is split with secret sharing into fragments that are spread across several independent clouds; no single provider holds enough to read it, and the data can still be reconstructed if some providers fail or misbehave. A Byzantine-fault-tolerant protocol layer keeps the fragments consistent across providers even under active attacks.

I was software architect on the project (2013–2015) and responsible for the architecture and implementation of the storage system. The open-source secret-sharing library that came out of it, [archistar-smc](https://github.com/ait-crypto/archistar-smc) (Java), is still available, and the ideas were carried forward into PRISMACLOUD.

Related publications: the architecture in {% cite loruenser2015archistar %}, the threat of malicious clients in {% cite happe2016malicious %}, and the S3-compatible backup proxy that plugs multi-cloud storage into legacy enterprise systems in {% cite happe2017archistar %}.
