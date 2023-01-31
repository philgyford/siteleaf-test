---
title: Projects
date: 2023-01-31 14:31:00 Z
---

Here are my projects:

<ul>
{% for project in site.projects %}
  <li><a href="{{ project.url }}">{{ project.title }}</a> for {{ project['client name'] }}</li>
{% endfor %}
</ul>