---
layout: page
permalink: /publications/
title: publications
description: 
years: [2024]
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->
<div class="publications">

  <!-- published papers -->
  <h3>published papers</h3>
  {% bibliography -f papers -q @article %}

  <!-- preprints -->
  <h3>preprints</h3>
  {% bibliography -f papers -q @misc %}
  
</div>