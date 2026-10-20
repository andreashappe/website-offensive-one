---
layout: page
permalink: /services/
title: services
description: AI-system threat modeling, agents for security, penetration testing, source-code audits and ISO 27001 advisory through offensive.one GmbH.
nav: true
nav_order: 4
---

**A good offense is the best defense.** Through [offensive.one](https://offensive.one) I help companies find and fix security problems before attackers do. Every engagement is senior-led: you work directly with me, from scoping to the final debrief. The methods come from two decades of security practice and from my [research]({{ '/publications/' | relative_url }}) and [open-source tooling]({{ '/projects/' | relative_url }}) on LLM-driven offensive security.

## AI-System Threat Modeling

LLM applications and agents add new trust boundaries: model output that drives tools, context pulled from documents and the web, and permissions that are often much broader than the task needs. I review the design of your AI system before it goes live, or before its next major change.

- Map trust boundaries, data flows and the context sources (RAG, files, e-mail, web) your system consumes
- Review tool scope and permissions: what an agent can reach, change or send on whose behalf
- Trace how a single untrusted input can propagate through the system
- Deliver a prioritised threat list with concrete architectural and operational controls

## Agents for Security

I build and evaluate LLM agents for offensive security, including [hackingBuddyGPT]({% link _projects/hackingbuddygpt.md %}) and [Cochise]({% link _projects/cochise.md %}). I help security teams apply that work to their own processes.

- Identify where agents genuinely help in your security work, and where they do not
- Prototype and evaluate agent-based automation against your own environment
- Assess vendor claims about "autonomous pentesting" with reproducible, realistic testbeds

## Penetration Testing

Manual, adversary-driven testing rather than scanner output.

- Web applications and APIs, cloud environments, internal networks and Active Directory
- Assumed-breach scenarios starting from a single compromised account or host
- Risk-ranked findings with proof-of-concepts and no CVSS inflation
- A retest to verify that fixes work

Certifications: OSCP, PNPT, CRTE, CARTP.

## Source-Code Audits

A manual review of the code paths that matter, focused on the flaws automated tools miss.

- Authorization and access-control logic, business-logic flaws, cryptography usage
- Findings with concrete, code-level fix guidance for your developers
- Secure-development recommendations based on the [OWASP Top 10 Proactive Controls]({% link _projects/owasp-proactive-controls.md %}), which I lead

## ISO 27001

Pragmatic security management for organisations that need to comply without drowning in paperwork.

- Gap analysis of your current security practice against ISO 27001
- Building an ISMS that fits your organisation: scope, risk assessment, policies and controls
- Preparing for the certification audit

I am a certified ISO 27001 auditor. I do not audit organisations I have advised.

## How Engagements Work

- **Fixed-scope assessments** (penetration tests, code audits, threat models) end with a written report, a debrief and a retest.
- **Ongoing work** (advisory, recurring testing) runs under a framework agreement and is billed monthly for the hours you approve.

## Contact and Next Steps

No two customers have the same requirements, so I scope each project individually.

Please contact me at [andreas@offensive.one](mailto:andreas@offensive.one) and include a rough description of your project and any specific requirements.

I will get back to you within two working days to schedule an initial call, by phone or video conference, to discuss your needs. Based on that conversation you receive a tailored proposal with the scope and next steps.

Services are provided by Offensive.One GmbH under its [terms and conditions]({{ '/terms/' | relative_url }}). See also the [Impressum]({{ '/impressum/' | relative_url }}).
