---
layout: page
permalink: /services/
title: services
description: AI-system threat modeling, agents for security, penetration testing, source-code audits and ISO 27001 advisory through offensive.one GmbH.
nav: true
nav_order: 4
---

**A good offense is the best defense.** Through [offensive.one](https://offensive.one) I help companies find and fix security problems before attackers do. Every engagement is senior-led: you work directly with me, from scoping to the final debrief. The methods come from two decades of security practice and from my [research]({{ '/publications/' | relative_url }}) and [open-source tooling]({{ '/projects/' | relative_url }}) on LLM-driven offensive security.

<!-- service cards reuse the projects card include -->
<div class="projects">
  {% assign sorted_services = site.services | sort: "importance" %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_services %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
</div>

## Contact and Next Steps

No two customers have the same requirements, so I scope each project individually. Please contact me at [andreas@offensive.one](mailto:andreas@offensive.one) and include a rough description of your project and any specific requirements.

I will get back to you within two working days to schedule an initial call, by phone or video conference, to discuss your needs. Based on that conversation you receive a tailored proposal in one of two forms:

- **Fixed-scope assessments** (penetration tests, code audits, threat models) end with a written report, a debrief and a retest.
- **Ongoing work** (advisory, recurring testing) runs under a framework agreement and is billed monthly for the hours you approve.

Services are provided by Offensive.One GmbH under its [terms and conditions]({{ '/terms/' | relative_url }}). See also the [Impressum]({{ '/impressum/' | relative_url }}).
