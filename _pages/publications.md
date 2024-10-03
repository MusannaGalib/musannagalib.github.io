---
layout: page
permalink: /research/
title: research
description: publications by categories in reversed chronological order. 
nav: true
nav_order: 1
---


<!-- _pages/publications.md -->
{% comment %}
<div class="publications">

{% bibliography -f {{ site.scholar.bibliography }} %}

</div>
{% endcomment %}

<div class="publications">

  <!-- Dendrite Inhibition Section -->
  <h2>Dendrite Inhibition</h2>
  <div class="row">
    <div class="col-md-3">
      <!-- Thumbnail for the project -->
      <img src="/assets/img/Alucone.jpeg" alt="Dendrite Inhibition" class="img-thumbnail">
    </div>
    <div class="col-md-9">
      <!-- List of related publications -->
          {% bibliography -f {{ site.scholar.bibliography }} -q @*[project=Dendrite] %}
    </div>
  </div>

    <!-- Supercapacitor Section -->
  <h2>Supercapacitor</h2>
  <div class="row">
    <div class="col-md-3">
      <!-- Thumbnail for the project -->
      <img src="/assets/img/supercapacitor.jpeg" alt="Supercapacitor" class="img-thumbnail">
    </div>
    <div class="col-md-9">
      <!-- List of related publications -->
          {% bibliography -f {{ site.scholar.bibliography }} -q @*[project=Supercapacitor] %}
    </div>
  </div>

  <!-- Repeat for other projects -->
