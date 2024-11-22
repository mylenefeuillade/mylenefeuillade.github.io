---
layout: page
permalink: /research/
title: research
description: ongoing research
years: [2025,2024]
type: [WP soon, in progress]
nav: true
nav_order: 2
---


### Ongoing research
<div class="publications">

{% for y in page.years %}
  <!-- <h2 class="year">{{y}}</h2> -->
  {% bibliography -f ongoing -q @*[year={{y}}]* %}
{% endfor %}

</div>
