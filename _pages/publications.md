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

  <!-- published papers -->
  <h3>published papers</h3>
  {% bibliography -f papers -q @article %}

  <!-- preprints -->
  <h3>preprints</h3>
  {% bibliography -f papers -q @misc %}

  <!-- preprints -->
  <h3>thesis</h3>
  {% bibliography -f papers -q @phdthesis %}
  
</div>