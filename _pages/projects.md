---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

Projects found: {{ site.projects.size }}

{% for project in site.projects %}
### {{ project.title }}

{{ project.excerpt }}

{% endfor %}