---
layout: page
permalink: /research/
title: research
description: publications are in reverse chronological order for featured research
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


<!-- Softwares Section in Publications.md -->
<h3 style="color: #1785b6;">Research Softwares</h3>
<div class="cv">
  <div class="card mt-3 p-3">
    <h3 class="card-title font-weight-medium"></h3>
    <div class="d-flex justify-content-between">
      <a href="" target="_blank" class="software-link" style="color: inherit;">Surftrack</a>
      <a href="" target="_blank" class="software-link" style="color: inherit;">pyMOOSE</a>
      <a href="" target="_blank" class="software-link" style="color: inherit;">pyVASPNN</a>
    </div>
  </div>
</div>






<!-- Dendrite Inhibition Section -->
<h3 style="color: #1785b6;">Dendrite Inhibition</h3>
<p>This project focuses on solving one of the biggest bottlenecks of rechargeable metal batteries: short-circuiting.</p>

<!-- Image and Publications Section -->
<div class="row">
  <div class="col-md-3">
    <!-- Thumbnail for the project -->
    <img src="/assets/img/Alucone.jpeg" alt="Dendrite Inhibition" class="img-thumbnail mb-2">
  </div>
  <div class="col-md-9">
    <!-- List of related publications -->
    {% bibliography -f {{ site.scholar.bibliography }} -q @*[project=Dendrite] %}
  </div>
</div>

<!-- Video Section -->
<div class="row mt-3">
  <div class="col-sm mt-3 mt-md-0">
    {% include video.html path="https://www.youtube.com/embed/4Q30xnX-hcc?si=nMsWbI9-BakjvUfX" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

<!-- Twitter Section -->
<div class="row mt-3">
  <div class="col-sm">
    <h4>Tweet</h4>
    {% twitter https://twitter.com/galib_musanna/status/1624818564128710656 %}
  </div>
</div>



    <!-- Supercapacitor Section -->
  <h3 style="color: #1785b6;">Supercapacitor</h3>
  <p>This project focuses on the development and optimization of supercapacitors, a crucial technology for energy storage systems.</p>
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
