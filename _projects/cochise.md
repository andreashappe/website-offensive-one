---
layout: page
title: Cochise
description: autonomous assumed-breach penetration testing of Active Directory networks
img: assets/img/projects/cochise.png
github: https://github.com/andreashappe/cochise
featured: true
importance: 2
category: LLMs for Offensive Security
related_publications: true
---

[Cochise](https://github.com/andreashappe/cochise) is an open-source prototype for autonomous assumed-breach penetration testing: given low-privileged access to a Windows/Active Directory network, an LLM-driven agent performs privilege escalation, lateral movement and, eventually, domain dominance on its own. It was evaluated against the [GOAD](https://github.com/Orange-Cyberdefense/GOAD) (Game of Active Directory) testbed.

Cochise is deliberately small — a few hundred lines of Python scaffolding around the model — and prioritises simplicity and readability over feature count. It is meant as a *reference harness*: a baseline and starting point for researchers working on LLM-based offensive security, rather than a product.

The accompanying journal paper appeared in ACM TOSEM {% cite happe2026enterprise %} (with a replicated computational results report {% cite happe2026enterprise_rcr %}), and the harness itself was presented in the ASE 2026 tool track {% cite happe2026cochise %}.

- Source: [github.com/andreashappe/cochise](https://github.com/andreashappe/cochise)

<!-- live GitHub stats for the repository (stars, forks, language); hidden if the stats service is unreachable -->
<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center" style="max-width: 420px">
  {% include repository/repo.liquid repository="andreashappe/cochise" %}
</div>
