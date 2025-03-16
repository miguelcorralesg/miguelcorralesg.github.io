---
layout: page
permalink: /publications/
title: publications
description: >
  Here you can find a list of my publications. I hope you enjoy reading them.
  For the most up-to-date information, please visit my <a href="https://scholar.google.com/citations?user=W4gtHSEAAAAJ&hl=en" target="_blank" rel="noopener noreferrer">Google Scholar</a>.
years: [2022, 2023, 2024, 2025]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
