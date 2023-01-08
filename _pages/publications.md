---
layout: page
permalink: /publications/
title: publications
description: 
years: [2021, 2020]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
[Google Scholar](https://scholar.google.com/citations?view_op=list_works&hl=en&hl=en&user=qxLzqagAAAAJ)

<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

