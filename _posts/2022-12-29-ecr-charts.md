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
  folium-chart-5: ["charts/lu_treemapchart_1.html", "400"] # second argument is the height
toc: true
toc_sticky: true
---
# Static Images
## Existing Land Use Map
The following map was generated from the ECR script:
![Existing Land Use Map](https://raw.githubusercontent.com/raimiassociates/ecr_dashboard/main/assets/images/Existing%20Land%20Use%20Category%20(L1).png)

## Existing Condition of Housing
The following charts were generated from the ECR script:
The City's Median Year Built is 1978, younger than those of the state and county average year built.
![Median Year Built](https://raw.githubusercontent.com/raimiassociates/ecr_dashboard/main/assets/images/Median%20Year%20Structure%20Built.png)

<!--![The San Juan Mountains are beautiful!](/assets/images/san-juan-mountains.jpg "San Juan Mountains")-->

The City's Median Housing Value is $593,700, slightly lower than the county's median value and higher than that of the state's.
![Median Value](https://raw.githubusercontent.com/raimiassociates/ecr_dashboard/main/assets/images/Median%20Value%20(Dollars).png)

The City's Median Gross Rent is is $1,762, higher than the county's and state's values.
![Median Gross Rent](https://raw.githubusercontent.com/raimiassociates/ecr_dashboard/main/assets/images/Median%20Gross%20Rent.png)

The City's Median Monthly Housing Costs is $1,799, slightly higher than that of the state's and the county's values.
![Median Monthly Housing Costs](https://raw.githubusercontent.com/raimiassociates/ecr_dashboard/main/assets/images/Median%20Monthly%20Housing%20Costs.png)


# Interactive Images
Following show examples of embedding interactive charts produced using plotly.

## Land Use Acreage Interactive Bar Chart

Total acreage of land by land use (L1):

<div id="folium-chart-1"></div>

## Land Use Acreage Interactive Pie Chart

Total acreage of land by land use (L1):

<div id="folium-chart-2"></div>

## Land Use Acreage Interactive Treemap Chart

Total acreage of land by land use from general to defined types:

<div id="folium-chart-5"></div>


## Street Network Interactive Map

Streets around Marina City center:

<div id="folium-chart-3"></div>

## Vacancy Rate Interactive Chart

Percent of vacant units in the City:

<div id="folium-chart-4"></div>

