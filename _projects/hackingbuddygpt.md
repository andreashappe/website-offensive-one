---
layout: page
title: hackingBuddyGPT
description: helping security researchers use LLMs for hacking in 50 lines of code or less
img: assets/img/projects/hackingbuddygpt.png
github: https://github.com/ipa-lab/hackingBuddyGPT
featured: true
importance: 1
category: LLMs for Offensive Security
related_publications: true
---

[hackingBuddyGPT](https://github.com/ipa-lab/hackingBuddyGPT) is a research framework for building LLM-driven offensive-security agents. I started it in 2023 as the vehicle for my PhD experiments; it has since grown into a community project with its own contributors and was part of the 2024 [GitHub AI Accelerator](https://accelerator.github.com/).

The core idea is minimalism: a new agent — say, one that tries to escalate privileges on a Linux host — should fit in roughly 50 lines of Python, so that the *interesting* part (how the LLM is prompted, what context it sees, how its output is turned into actions) stays readable and easy to change. The framework takes care of the plumbing: LLM connectors, tool execution, SSH/shell access to targets, logging, and a capability system that lets agents share building blocks.

Agents built on hackingBuddyGPT back several of my papers, including the original FSE 2023 vision paper {% cite happe2023pwnd %}, the Linux privilege-escalation study in Empirical Software Engineering {% cite happe2026llmhackers %}, the *Got Root?* benchmark {% cite happe2024gotroot %}, and follow-up work on local models {% cite probst2026privesc normann2026reliable %}.

- Source: [github.com/ipa-lab/hackingBuddyGPT](https://github.com/ipa-lab/hackingBuddyGPT)
- Documentation: [docs.hackingbuddy.ai](https://docs.hackingbuddy.ai)

<!-- live GitHub stats for the repository (stars, forks, language); hidden if the stats service is unreachable -->
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center" style="max-width: 420px">
  {% include repository/repo.liquid repository="ipa-lab/hackingBuddyGPT" %}
</div>
