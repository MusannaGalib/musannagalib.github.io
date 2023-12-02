---
layout: post
title: Supercapacitor Research
date: 2020-03-23 14:37:00-0400
description: Supercapacitor Research
tags: formatting tables
categories: sample-posts
giscus_comments: true
related_posts: true
datatable: true
related_publications: 10.1007/s00894-020-04483-5

---

In this study, molecular dynamics (MD) simulations have been performed to explore the variation of ion density and electric potential due to electrode surface modification. Two different surface morphologies, having planer and slit pore with different conditions of surface charge, have been studied for graphene-MnO2 surface using LAMMPS. For different pore widths, the concentration of ions in the double layer is observed to be very low when the surface of the graphene-MnO2 electrode is charged. With a view to identify the optimal pore size for the simulation domain considered, three different widths for the nano-slit type pores and the corresponding ion-ion interactions are examined. Though this effect is negligible for pores with 9.23 and 3.55 Å widths, a considerable increase in the ionic concentration within the 7.10 Å pores is observed when the electrode is kept neutral. The edge region of these nano-slit pores leads to effective energy storage by promoting ion separation and a significantly higher charge accumulation is found to occur on the edges compared to the basal planes. For the simulation domain of the present study, partition coefficient is maximum for a pore size of 7.10 Å, indicating that the ions’ penetration and movement into nano-slit pores are most favorable for this optimum pore size for MnO2-graphene electrodes with aqueous NaCl electrolyte.

Using markdown to display tables is easy. Just use the following syntax:

```markdown
| Left aligned | Center aligned | Right aligned |
| :----------- | :------------: | ------------: |
| Left 1       | center 1       | right 1       |
| Left 2       | center 2       | right 2       |
| Left 3       | center 3       | right 3       |
```

That will generate:

| Left aligned | Center aligned | Right aligned |
| :----------- | :------------: | ------------: |
| Left 1       | center 1       | right 1       |
| Left 2       | center 2       | right 2       |
| Left 3       | center 3       | right 3       |

<p></p>

It is also possible to use HTML to display tables. For example, the following HTML code will display a table with [Bootstrap Table](https://bootstrap-table.com/), loaded from a JSON file:

{% raw  %}
```html
<table
  id="table"
  data-toggle="table"
  data-url="{{ '/assets/json/table_data.json' | relative_url }}">
  <thead>
    <tr>
      <th data-field="id">ID</th>
      <th data-field="name">Item Name</th>
      <th data-field="price">Item Price</th>
    </tr>
  </thead>
</table>
```
{% endraw  %}

<table
  data-toggle="table"
  data-url="{{ '/assets/json/table_data.json' | relative_url }}">
  <thead>
    <tr>
      <th data-field="id">ID</th>
      <th data-field="name">Item Name</th>
      <th data-field="price">Item Price</th>
    </tr>
  </thead>
</table>

<p></p>

By using [Bootstrap Table](https://bootstrap-table.com/) it is possible to create pretty complex tables, with pagination, search, and more. For example, the following HTML code will display a table, loaded from a JSON file, with pagination, search, checkboxes, and header/content alignment. For more information, check the [documentation](https://examples.bootstrap-table.com/index.html).

{% raw  %}
```html
<table
  data-click-to-select="true"
  data-height="460"
  data-pagination="true"
  data-search="true"
  data-toggle="table"
  data-url="{{ '/assets/json/table_data.json' | relative_url }}">
  <thead>
    <tr>
      <th data-checkbox="true"></th>
      <th data-field="id" data-halign="left" data-align="center" data-sortable="true">ID</th>
      <th data-field="name" data-halign="center" data-align="right" data-sortable="true">Item Name</th>
      <th data-field="price" data-halign="right" data-align="left" data-sortable="true">Item Price</th>
    </tr>
  </thead>
</table>
```
{% endraw  %}

<table
  data-click-to-select="true"
  data-height="460"
  data-pagination="true"
  data-search="true"
  data-toggle="table"
  data-url="{{ '/assets/json/table_data.json' | relative_url }}">
  <thead>
    <tr>
      <th data-checkbox="true"></th>
      <th data-field="id" data-halign="left" data-align="center" data-sortable="true">ID</th>
      <th data-field="name" data-halign="center" data-align="right" data-sortable="true">Item Name</th>
      <th data-field="price" data-halign="right" data-align="left" data-sortable="true">Item Price</th>
    </tr>
  </thead>
</table>
