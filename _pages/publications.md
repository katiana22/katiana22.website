---
layout: page
permalink: /publications/
title: publications
description: Journal publications in reversed chronological order.
years: [2022, 2021, 2019]
nav: true
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
