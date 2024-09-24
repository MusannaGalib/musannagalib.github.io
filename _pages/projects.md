---
layout: page
title: teaching
permalink: /teaching/
description: Materials and information related to courses/research
nav: false
nav_order: 2
display_categories: [work] #[work, fun]
horizontal: false
---
# Personal Profiles:
* Research Website Profiles: <a href="https://orcid.org/0000-0002-1735-7546">ORCID</a>, <a href="https://www.scopus.com/authid/detail.uri?authorId=57195515362">Scopus</a>, <a href="https://buet.academia.edu/MusannaGalib">Academia</a>

# Useful Links:
* How to Select a Journal: <a href="https://mjl.clarivate.com/home">Web of Science</a>, <a href="https://www.scimagojr.com/">Scimago</a>, <a href="https://journalfinder.elsevier.com/">Elsevier</a>, <a href="https://journalfinder.wiley.com/search?type=match">Wiley</a>
* Technical Writing Management: <a href="https://www.wolframalpha.com/">WolframAlpha</a>, <a href="https://www.overleaf.com/">Overleaf</a>, <a href="https://miktex.org/download">MiKTeX</a>, <a href="https://automeris.io/WebPlotDigitizer/">WebPlotDigitizer</a>, <a href="https://www.xm1math.net/texmaker/">TEXMAKER</a>, <a href="https://mathpix.com/">Mathpix</a>, <a href="https://www.connectedpapers.com/">Connected Papers</a>
* Technical Resources-Structure Repositories: <a href="https://www.crystallography.net/cod/search.html">Crystallography Open Database</a>, <a href="https://www.ccdc.cam.ac.uk/">Cambridge Crystallographic Data Centre</a>, <a href="http://rruff.geo.arizona.edu/AMS/amcsd.php"> American Mineralogist Crystal Structure Database</a>, <a href="https://pubpeer.com/"> Pubpeer</a>, <a href="https://jp-minerals.org/vesta/en/"> Vesta</a>

# Recommended Books:
* Theory of Dislocations by Peter M. Anderson, John P. Hirth, Jens Lothe
* Thin Film Materials by L. B. Freund, and S. Suresh

  
<!-- pages/projects.md -->
<div class="projects">
{%- if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_projects = site.projects | where: "category", category -%}
  {%- assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
  {% endfor %}

{%- else -%}
<!-- Display projects without categories -->
  {%- assign sorted_projects = site.projects | sort: "importance" -%}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
{%- endif -%}
</div>
