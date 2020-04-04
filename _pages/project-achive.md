---
layout: archive
title: "My projects"
permalink: /projects/
collection: projects
entries_layout: grid
author_profile: true
---
Professional and hobby projects, and more 


{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
