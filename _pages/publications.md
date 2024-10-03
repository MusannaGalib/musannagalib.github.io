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
<h2>Softwares</h2>
<div class="cv">
  <!-- Reuse the list style from CV -->
  <div class="card mt-3 p-3">
    <h3 class="card-title font-weight-medium">Softwares</h3>
    <div>
      <!-- Mimic the list structure from cv/list.html -->
      <ul class="list-group">
        <li class="list-group-item">
          <a href="https://surftrack.com" target="_blank" class="software-link">Surftrack</a>
        </li>
        <li class="list-group-item">
          <a href="https://pyMOOSE.com" target="_blank" class="software-link">pyMOOSE</a>
        </li>
        <li class="list-group-item">
          <a href="https://atom.io" target="_blank" class="software-link">Atom</a>
        </li>
      </ul>
    </div>
  </div>
</div>




<!-- Dendrite Inhibition Section -->
  <h3 style="color: #007bff;">Dendrite Inhibition</h3>
  <div class="row">
    <div class="col-md-3">
      <!-- Thumbnail for the project -->
      <img src="/assets/img/Alucone.jpeg" alt="Dendrite Inhibition" class="img-thumbnail mb-2">
      <img src="/assets/img/supercapacitor.jpeg" alt="Dendrite Inhibition - Experiment" class="img-thumbnail mb-2">
    </div>
    <div class="col-md-9">
      <!-- List of related publications -->
          {% bibliography -f {{ site.scholar.bibliography }} -q @*[project=Dendrite] %}
    </div>
  </div> 


    <!-- Supercapacitor Section -->
  <h3 style="color: #007bff;">Supercapacitor</h3>
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
