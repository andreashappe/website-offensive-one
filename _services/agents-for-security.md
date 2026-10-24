---
layout: page
title: Agents for Security
description: using LLM agents in your own security work, grounded in research
importance: 2
img: assets/img/services/agents.png
---

LLM agents can now carry out parts of a penetration test on their own, from Linux privilege escalation to lateral movement in Active Directory. At the same time, the market is full of "autonomous pentesting" claims that are hard to verify. I help security teams separate what works from what demos well, and put agents to use where they actually help.

## Background

I build and evaluate LLM agents for offensive security as part of my [PhD research]({{ '/publications/' | relative_url }}) at TU Wien:

- [hackingBuddyGPT]({% link _projects/hackingbuddygpt.md %}), a framework for LLM-driven security agents, was part of the 2024 GitHub AI Accelerator. It backs my work on autonomous Linux privilege escalation {% cite happe2023pwnd happe2026llmhackers %}.
- [Cochise]({% link _projects/cochise.md %}) is a reference harness for autonomous assumed-breach testing of Active Directory networks {% cite happe2026enterprise happe2026cochise %}.
- I have also published on how such systems should be measured: testbeds, metrics and experiment design {% cite happe2025benchmarking %}.

That research gives a realistic picture of where agents are strong, where they fail, and how easily a benchmark result overstates real-world capability.

## What I help with

- **Use-case selection:** identifying where agents genuinely help in your security work (triage, reconnaissance, repetitive test steps) and where they do not
- **Prototypes:** building and evaluating agent-based automation against your own environment, with your data staying under your control
- **Vendor evaluation:** checking claims about "autonomous pentesting" products with reproducible, realistic testbeds instead of vendor demos
- **Safe operation:** scoping, logging and guardrails so that an agent running against your systems stays within its mandate

[Back to all services]({{ '/services/' | relative_url }}) · [Get in touch](mailto:andreas@offensive.one)
