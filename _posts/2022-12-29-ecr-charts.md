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

This post will show examples of embedding interactive charts produced using plotly.

## Land Use Acreage Bar Chart

Total acreage of land by land use (L1):

<div id="folium-chart-1"></div>

## Land Use Acreage Pie Chart

Total acreage of land by land use (L1):

<div id="folium-chart-2"></div>

## Street Network Map

Streets around Marina City center:

<div id="folium-chart-3"></div>

## Vacancy Rate Chart

Percent of vacant units in the City:

<div id="folium-chart-4"></div>

