---
layout: collection
title: "My projects"
permalink: /projects/
collection: projects
entries_layout: grid
classes: wide
---

{% for project in site.projects %}
  {% include archive-single.html %}
{% endfor %}
