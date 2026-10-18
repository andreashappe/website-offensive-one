---
layout: about
title: about
permalink: /
subtitle: <a href='https://www.tuwien.at/'>TU Wien</a> · <a href='https://offensive.one'>offensive.one</a> · Vienna, Austria

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: # text shown under the profile picture; left empty on purpose

selected_papers: true # includes a list of papers marked as "selected={true}"
social: false # social icons live in the navbar instead (enable_navbar_social in _config.yml)

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<!-- The about layout has no per-page style hook, so this stays inline. It only affects this page:
     the navbar social icons (enable_navbar_social) default to 1.7rem, which is taller than the nav links. -->
<style>
  .navbar .navbar-brand.social {
    font-size: 1.15rem;
    line-height: 1;
    display: flex;
    align-items: center;
    gap: 0.6rem;
    margin-right: 0;
  }
  .navbar .navbar-brand.social a {
    display: inline-flex;
    align-items: center;
  }
  .navbar .navbar-brand.social a img,
  .navbar .navbar-brand.social a svg,
  .navbar .navbar-brand.social a svg image {
    width: 1.15rem;
    height: 1.15rem;
    margin-bottom: 0;
  }
</style>

I am a security researcher and consultant working at the intersection of AI and offensive security. As a PhD student at [TU Wien](https://www.tuwien.at/) (advised by [Jürgen Cito](https://informatics.tuwien.ac.at/people/juergen-cito)), I study how large language models can be used — and misused — for penetration testing: from autonomous Linux privilege escalation and Active Directory attacks to benchmarking practices and the ethics of autonomous offensive agents. I am the original author of [hackingBuddyGPT](https://github.com/ipa-lab/hackingBuddyGPT), a framework for LLM-driven security research that was part of the 2024 GitHub AI Accelerator.

Alongside research, I run [offensive.one](https://offensive.one), where I help companies improve their security posture and secure software development practice, and I work as an ISO 27001 auditor. Before that I spent two decades in security engineering and software development: as a senior security consultant and penetration tester, as an engineer on privacy-preserving multi-cloud storage at the Austrian Institute of Technology, and as a developer on the SECOQC quantum key distribution network. I also lecture on web and application security and lead OWASP projects and chapters in Austria.
