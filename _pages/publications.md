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
      <a href="" target="_blank" class="software-link" style="color: inherit;">SurfTrack</a>
      <a href="" target="_blank" class="software-link" style="color: inherit;">MOOSEanalyze</a>
      <a href="" target="_blank" class="software-link" style="color: inherit;">pyVASPNN</a>
    </div>
  </div>
</div>



<!-- Dendrite Inhibition Section -->
<div style="display: flex; justify-content: space-between; align-items: center;">
  <h3 style="color: #1785b6;">Interatomic Potential for Materials Science</h3>
  <span style="background-color: #6a0dad; color: white; padding: 5px 10px; border-radius: 0; box-shadow: 2px 2px 5px rgba(0,0,0,0.2); font-weight: bold;">2023 - 2025</span>
</div>
<p>This project focuses on developing machine learning interatomic potential, especially using an equivariant graph neural network.</p>




<!-- Dendrite Inhibition Section -->
<div style="display: flex; justify-content: space-between; align-items: center;">
  <h3 style="color: #1785b6;">Better Batteries: Dendrite Inhibition</h3>
  <span style="background-color: #6a0dad; color: white; padding: 5px 10px; border-radius: 0; box-shadow: 2px 2px 5px rgba(0,0,0,0.2); font-weight: bold;">2021 - 2025</span>
</div>
<p>This project focuses on solving one of the biggest bottlenecks of rechargeable metal batteries: short-circuiting.</p>

<!-- Image and Video Section -->
<div class="row">
  <div class="col-md-3">
    <!-- Thumbnail for the project -->
        <img src="/assets/img/NASICON_AZIB.jpg" alt="Dendrite Inhibition" class="img-thumbnail mb-2" style="width: 100%; height: auto;">
        <img src="/assets/img/Alucone.jpeg" alt="Dendrite Inhibition" class="img-thumbnail mb-2" style="width: 100%; height: auto;">
    
    <!-- Video embedded just after the image -->
    <iframe src="https://www.youtube.com/embed/4Q30xnX-hcc?si=nMsWbI9-BakjvUfX" class="img-fluid img-thumbnail mb-2" style="width: 100%; height: auto; border: none;" allowfullscreen></iframe>
  </div>
  <div class="col-md-9">
    <!-- List of related publications -->
    {% bibliography -f {{ site.scholar.bibliography }} -q @*[project=Dendrite] %}
  </div>
</div>





    <!-- Supercapacitor Section -->
<div style="display: flex; justify-content: space-between; align-items: center;">
  <h3 style="color: #1785b6;">Supercapacitor</h3>
    <span style="background-color: #6a0dad; color: white; padding: 5px 10px; border-radius: 0; box-shadow: 2px 2px 5px rgba(0,0,0,0.2); font-weight: bold;">2019 - 2024</span>
</div>    
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
