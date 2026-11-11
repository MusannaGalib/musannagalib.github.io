---
layout: page
permalink: /research/
title: research
description: Selected projects and publications.
nav: true
nav_order: 1
---

<div class="publications">

<h3>Software</h3>
<p class="software-line">
  <a href="https://github.com/MusannaGalib/AtomProNet">AtomProNet</a> ·
  <a href="https://github.com/MusannaGalib/SurfTrack">SurfTrack</a> ·
  <a href="https://github.com/MusannaGalib/MOOSEanalyze">MOOSEanalyze</a> ·
  <a href="https://data.energystoragera.org/data">ESRA Data Platform</a>
</p>

<div class="project-head">
  <h3>FAIR Data Infrastructure for Energy Storage</h3>
  <span class="period">2026 – present</span>
</div>
<p>The <a href="https://data.energystoragera.org/data">ESRA Data Platform</a> at Argonne National Laboratory, built end to end: data ingestion and a FAIR (findable, accessible, interoperable, reusable) catalog, a web interface, an MCP server that connects the catalog to AI assistants, and analysis agents that turn raw instrument files into audited, traceable results.</p>
<p class="stack">Backend · Frontend · DevOps · MCP server · Data catalog · Analysis agents · Audit trails</p>
<div class="row">
  <div class="col-md-3">
    <a href="https://data.energystoragera.org/data"><img src="/assets/img/ESRA_logo.svg" alt="ESRA logo" class="project-figure project-logo"></a>
  </div>
  <div class="col-md-9">
    {% bibliography -f {{ site.scholar.bibliography }} -q @*[project=ESRA] %}
  </div>
</div>

<div class="project-head">
  <h3>Interatomic Potentials for Materials Science</h3>
  <span class="period">2023 – 2025</span>
</div>
<p>Machine-learning interatomic potentials, built on equivariant graph neural networks. <a href="https://www.youtube.com/watch?v=na10M4NbdfM">Talk (video) ↗</a></p>
<div class="row">
  <div class="col-md-3">
    <a href="https://github.com/MusannaGalib/AtomProNet"><img src="/assets/img/AtomProNet_logo.jpg" alt="AtomProNet logo" class="project-figure project-logo"></a>
  </div>
  <div class="col-md-9">
    {% bibliography -f {{ site.scholar.bibliography }} -q @*[project=MLIP] %}
  </div>
</div>

<div class="project-head">
  <h3>Dendrite Inhibition</h3>
  <span class="period">2021 – 2025</span>
</div>
<p>Suppressing dendrite-driven short circuits in rechargeable metal batteries. <a href="https://www.youtube.com/watch?v=4Q30xnX-hcc">Talk (video) ↗</a></p>
<div class="row">
  <div class="col-md-3">
    <img src="/assets/img/NASICON_AZIB.jpg" alt="NASICON cathode for aqueous zinc-ion batteries" class="project-figure">
    <img src="/assets/img/Alucone.jpeg" alt="Alucone coating on zinc" class="project-figure">
  </div>
  <div class="col-md-9">
    {% bibliography -f {{ site.scholar.bibliography }} -q @*[project=Dendrite] %}
  </div>
</div>

<div class="project-head">
  <h3>Supercapacitors</h3>
  <span class="period">2019 – 2024</span>
</div>
<p>Electrode design for supercapacitors.</p>
<div class="row">
  <div class="col-md-3">
    <img src="/assets/img/supercapacitor.jpeg" alt="Supercapacitor" class="project-figure">
  </div>
  <div class="col-md-9">
    {% bibliography -f {{ site.scholar.bibliography }} -q @*[project=Supercapacitor] %}
  </div>
</div>

<div class="project-head">
  <h3>Other Publications</h3>
</div>
<p>Book chapter, thermal and energy systems, and engineering education.</p>
{% bibliography -f {{ site.scholar.bibliography }} -q @*[project=Other] %}

<p class="equal-contrib">* equal contribution</p>

</div>
