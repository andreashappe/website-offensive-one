---
layout: page
title: Source-Code Audits
description: manual review of the code paths that matter, focused on what tools miss
importance: 4
img: assets/img/services/source-code.png
---

Static-analysis tools are good at finding known bug patterns. They are poor at finding a missing authorization check, a business rule that can be bypassed, or cryptography that is used correctly line by line but wrongly as a whole. A source-code audit is a manual review of the code paths that matter, by someone who reads code like a developer and thinks like an attacker.

## Background

Before moving into security full-time I spent twelve years as a software engineer and architect at the Austrian Institute of Technology. There I worked on the Vienna SECOQC quantum-key-distribution network and on secure, secret-sharing-based cloud storage, so I have built cryptographic systems as well as reviewed them. I lectured on web application security at FH Technikum Wien from 2019 to 2023. Since 2023 I have led the [OWASP Top 10 Proactive Controls]({% link _projects/owasp-proactive-controls.md %}), OWASP's guidance on what developers should build into every application.

## What I look at

- **Authorization and access control:** who can read or change what, across all entry points
- **Business logic:** workflows, state transitions and assumptions an attacker can break
- **Cryptography usage:** algorithm choice, key handling, randomness and protocol composition
- **Trust boundaries:** input handling, deserialization, and calls into external systems
- **Secure-coding standards:** whether the code follows your own secure-coding guidelines

## What you get

- Findings with code references and concrete, code-level fix guidance your developers can apply directly
- A debrief with your developers that explains the root cause behind each finding, not just the instance, which also reduces technical debt and long-term maintenance risk
- Secure-development recommendations based on the OWASP Top 10 Proactive Controls, so the same class of bug does not come back

[Back to all services]({{ '/services/' | relative_url }}) · [Get in touch](mailto:andreas@offensive.one)
