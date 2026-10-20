---
layout: page
title: AI-System Threat Modeling
description: design reviews of LLM applications and agents before they go live
importance: 1
---

LLM applications and agents add new trust boundaries: model output that drives tools, context pulled from documents and the web, and permissions that are often much broader than the task needs. I review the design of your AI system before it goes live, or before its next major change.

## What I look at

- Trust boundaries, data flows and the context sources (RAG, files, e-mail, web) your system consumes
- Tool scope and permissions: what an agent can reach, change or send, and on whose behalf
- How a single untrusted input can propagate through the system

## What you get

A prioritised threat list with concrete architectural and operational controls, discussed with your engineers in a debrief.

[Back to all services]({{ '/services/' | relative_url }}) · [Get in touch](mailto:andreas@offensive.one)
