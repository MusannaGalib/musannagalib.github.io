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


<!-- Softwares Section -->
<h2 class="section-title">Softwares</h2>

<div class="software-list">
  <!-- Software Item -->
  <div class="software-item">
    <a href="https://example-link-surftrack.com" class="software-link">Surftrack</a>
  </div>

  <div class="software-item">
    <a href="https://example-link-pymoose.com" class="software-link">pyMOOSE</a>
  </div>

  <div class="software-item">
    <a href="https://example-link-atom.com" class="software-link">Atom</a>
  </div>
</div>

<style>
  .section-title {
    font-size: 24px;
    font-weight: bold;
    margin-bottom: 20px;
  }
  
  .software-list {
    display: flex;
    flex-wrap: wrap;
  }

  .software-item {
    margin-right: 20px; /* Adds space between software items */
    margin-bottom: 10px;
  }

  .software-link {
    text-decoration: none;
    font-size: 18px;
    color: #000;
    transition: color 0.3s;
  }

  .software-link:hover {
    color: #007bff;
  }
</style>



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
