---
layout: page
title: impact
permalink: /impact/
description: Community and stakeholder engagement, capacity-building and knowledge translation that drives positive impacts for nature and people.
nav: false
nav_order: 2
horizontal: false
---

<div class="projects">
  <div class="row row-cols-1 row-cols-md-3">
    {% assign sorted_projects = site.projects | where: "category", "impact" | sort: "importance" %}
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}