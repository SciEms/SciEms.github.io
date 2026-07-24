---
layout: page
permalink: /research/
title: research
description: Conservation social science spanning communication, behaviour change, and beyond.
nav: true
nav_order: 4
---

{% include bib_search.liquid %}

## My favourites

<div class="publications">
  {% bibliography --group_by none --query @*[selected=true]* %}
</div>

## Highly cited

<div class="publications">
  {% include highly_cited_papers.liquid %}
</div>

## All publications

<div class="publications">
  {% bibliography %}
</div>