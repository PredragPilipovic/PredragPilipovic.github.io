---
layout: page
permalink: /publications/
title: publications
description: 
years: [2024]
nav: true
---

<!-- _pages/publications.md -->
<div class="publications">

  {%- for y in page.years %}
    <h2 class="year">{{y}}</h2>

    <!-- published papers -->
    <h3>published papers</h3>
    {% bibliography -f papers -q @article*[year={{y}}] %}

    <!-- preprints -->
    <h3>preprints</h3>
    {% bibliography -f papers -q @misc*[year={{y}}] %}
    
  {%- endfor %}

</div>