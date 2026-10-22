---
title: "Projects"
permalink: /projects/
layout: archive
author_profile: true
---

Below are my ongoing research projects and studies:

Projects found: {{ site.projects.size }}

{% for project in site.projects %}
- {{ project.title }}
{% endfor %}

{% for project in site.projects %}
  {% include archive-single.html %}
{% endfor %}