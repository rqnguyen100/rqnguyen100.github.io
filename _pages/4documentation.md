---
layout: page
permalink: /documentation/
title: documentation
description: various documentation I've written or helped write
years: [2022.03, 2022.02, 2021.12, 2021.03]
nav: true
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
