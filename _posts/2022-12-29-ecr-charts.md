---
title: "Existing Condition Analysis Charts Test"
date: 2022-12-29
published: true
tags: [dataviz, folium]
excerpt: "Embedding interactive Folium charts on static pages using Jekyll."
folium-loader:
  folium-chart-1: ["charts/lu_barchart.html", "400"] # second argument is the height
  folium-chart-2: ["charts/lu_piechart.html", "400"] # second argument is the height
  folium-chart-3: ["charts/streetmap.html", "600"] # second argument is the height
  folium-chart-4: ["charts/Vacancy Rate.html", "400"] # second argument is the height
toc: true
toc_sticky: true
---
### Static Images
## Existing Land Use Map
The following map was generated from the ECR script:
![Existing Land Use Map](assets/Existing Land Use Category (L1).png)


### Interactive Images
Following show examples of embedding interactive charts produced using plotly.

## Land Use Acreage Interactive Bar Chart

Total acreage of land by land use (L1):

<div id="folium-chart-1"></div>

## Land Use Acreage Interactive Pie Chart

Total acreage of land by land use (L1):

<div id="folium-chart-2"></div>

## Street Network Interactive Map

Streets around Marina City center:

<div id="folium-chart-3"></div>

## Vacancy Rate Interactive Chart

Percent of vacant units in the City:

<div id="folium-chart-4"></div>

