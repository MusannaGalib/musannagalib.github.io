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
  <div class="card mt-3 p-3">
    <h3 class="card-title font-weight-medium">Softwares</h3>
    <div>
      <!-- Create the content using the same structure as cv.yml -->
      <ul class="list-group">
        <li class="list-group-item">
          <strong>Name:</strong> Surftrack<br>
          <strong>Description:</strong> Software for tracking waves and surf conditions.<br>
          <a href="https://surftrack.com" target="_blank" class="software-link">Visit Surftrack</a>
        </li>
        <li class="list-group-item">
          <strong>Name:</strong> pyMOOSE<br>
          <strong>Description:</strong> Python-based software for simulating neuron models.<br>
          <a href="https://pyMOOSE.com" target="_blank" class="software-link">Visit pyMOOSE</a>
        </li>
        <li class="list-group-item">
          <strong>Name:</strong> Atom<br>
          <strong>Description:</strong> A hackable text editor for modern programming.<br>
          <a href="https://atom.io" target="_blank" class="software-link">Visit Atom</a>
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
