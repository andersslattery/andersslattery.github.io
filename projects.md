---
layout: page
title: Projects
---

## GIS & Conservation Projects

{% for project in site.projects %}
  - [{{ project.title }}]({{ project.url }})
{% endfor %}
