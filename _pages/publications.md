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

  <!-- Preprints Section -->
  <h2 class="year">Preprints ({{y}})</h2>
  <div class="preprints">
    {% bibliography -f papers -q @*[year={{y}} and status="preprint"]* %}
  </div>

  <!-- Published Section -->
  <h2 class="year">Published ({{y}})</h2>
  <div class="published">
    {% bibliography -f papers -q @*[year={{y}} and status="published"]* %}
  </div>

  {%- endfor %}

</div>