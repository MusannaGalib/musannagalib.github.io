---
layout: about
title: about
permalink: /
subtitle: <a href='#'>Ph.D. Candidate</a>. The University of British Columbia

profile:
  align: right
  image: Musanna_Galib_Photo.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Photo taken at Vancouver, British Columbia, Canada</p>

selected_papers: false # includes a list of papers marked as "selected={true}"
news: false  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
social: true  # includes social icons at the bottom of the page
---

Musanna Galib’s research interests encompass exploring the core mechanisms that emerge in materials under different conditions using multiscale modeling and experiments. Currently, Musanna is working on solving the dendrite problem in rechargeable batteries at UBC. This work exists at the intersection of mechanics of materials, materials science, and electrochemical phenomena.  

Musanna Galib completed his M.Sc. (2019) and B.Sc. (2017) in Mechanical Engineering from Bangladesh University of Engineering and Technology (BUET).

For any query, suggestion, or collaboration, please contact: galibubc at student.ubc.ca



<!-- pages/projects.md -->
<!-- Featured Research Section -->
<h2>Featured Research</h2>

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
