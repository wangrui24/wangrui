---
layout: page
permalink: /publications/
title: publications and preprints
description: publications and preprints by categories in reversed chronological order.  
years: [2024,2023,2022,2021]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->


Check out [my Google Scholar](https://scholar.google.com/citations?user=OZeSbMEAAAAJ&hl=zh-CN) page for full publication list.

<div class="publications">
  
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}

</div>
