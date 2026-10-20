---
layout: page
title: AI-System Threat Modeling
description: design reviews of LLM applications and agents before they go live
importance: 1
---

LLM applications and agents add trust boundaries that classic threat models do not cover. Model output drives tools and API calls. Context is pulled from documents, tickets, e-mail and the web, and every one of those sources can carry attacker-controlled text. Agents often run with far broader permissions than their task needs. Many of these problems are cheap to fix on the whiteboard and expensive to fix after release, so I review the design of your AI system before it goes live, or before its next major change.

## Background

Since 2022 my research has been about the attacker's side of LLMs: how far language-model agents can get when they are pointed at real systems, and what makes them succeed or fail. Part of that work looks at how untrusted input steers LLM-based tooling. For example, adversarial bug reports can push automated program repair into introducing vulnerabilities {% cite przymus2026adversarial %}. Before that I spent a decade as a security consultant doing threat modeling, application-security reviews and penetration tests. This service combines both: a structured threat model, informed by what LLM-driven attacks actually look like in practice.

## What I look at

- **Trust boundaries and data flows:** which components see untrusted input, and where model output is treated as trusted
- **Context sources:** RAG indexes, files, e-mail, tickets and web content your system consumes, and who can write to them
- **Tools and permissions:** what an agent can reach, change or send, on whose behalf, and with which credentials
- **Propagation:** how a single untrusted input can travel through prompts, tools and downstream systems
- **Human oversight:** where a person approves an action, and whether that approval is informed or a rubber stamp

## What you get

- A prioritised threat list, each threat with its attack path and its impact on your business
- Concrete architectural and operational controls, ordered by risk reduction and implementation effort
- A debrief with your engineers so the threat model becomes something the team maintains, not a one-off document

[Back to all services]({{ '/services/' | relative_url }}) · [Get in touch](mailto:andreas@offensive.one)
