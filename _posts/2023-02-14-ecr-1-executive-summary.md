---
title: "Chapter 1: Executive Summary"
date: 2023-02-14
published: true
tags: [dataviz, folium]
excerpt: "Let's learn about Marina in 3 mins."
folium-loader:
  folium-chart-1: ["charts/lu_barchart.html", "400"] # second argument is the height
  folium-chart-2: ["charts/lu_piechart.html", "400"] # second argument is the height
  folium-chart-3: ["charts/streetmap.html", "600"] # second argument is the height
  folium-chart-4: ["charts/Vacancy Rate.html", "400"] # second argument is the height
  folium-chart-5: ["charts/lu_treemapchart_2.html", "600"] # second argument is the height
  folium-chart-6: ["charts/Tenure condition 2011.html", "500"]
  folium-chart-7: ["charts/Tenure condition 2021.html", "500"]
  folium-chart-8: ["charts/Vacancy Rate (pct)_2011.html", "400"]
  folium-chart-9: ["charts/vcnt_and_under_parcels.html", "600"]
toc: true
toc_sticky: true
---
# Existing Land Use
## Existing Land Use Map
The following map was generated from the ECR python script:
![Existing Land Use Map](https://raw.githubusercontent.com/raimiassociates/ecr_dashboard/main/assets/images/Existing%20Land%20Use%20Category%20(L1).png)

# Housing
## Aging Housing Stock
The following charts were generated from the ECR python script:
The City's Median Year Built is 1978 in 2021, younger than those of the state and county average year built.
![Median Year Built](https://raw.githubusercontent.com/raimiassociates/ecr_dashboard/main/assets/images/Median%20Year%20Structure%20Built.png)

## Relatively Low Vacancy Rate
In 2021, a relatively small share of housing units are vacant (4.7%), compared to 9.2% in the county and 7.8% statewide.
<div id="folium-chart-4"></div>
This has descreased from 6.6% in 2011.
<div id="folium-chart-8"></div>
<!--![The San Juan Mountains are beautiful!](/assets/images/san-juan-mountains.jpg "San Juan Mountains")-->

## Home Value
The City's Median Housing Value is $593,700, slightly lower than the county's median value and higher than that of the state's.
![Median Value](https://raw.githubusercontent.com/raimiassociates/ecr_dashboard/main/assets/images/Median%20Value%20(Dollars).png)

## Changing Housing Tenure
Based on ACS2011 5yr and ACS2021 5yr estimates, the City of Marina Percent of vacant units in the City:
* Marina has a lower rate of homeownership than Monterey County or the state ??? approximately 41.1 percent of Marina???s housing units were owner-occupied in 2021, as opposed to 51.7 percent in the county and 55.5 percent statewide.
<div id="folium-chart-7"></div>
* Despite these relatively low rates of owner occupancy, homeownership rates have slightly increased in Marina over the last 10 years. The percentage of owner-occupied homes in 2021 was up about 1 percent from 2011, when 40.1 percent of units were owner-occupied.
<div id="folium-chart-6"></div>

## Cost of Housing
The City's Median Gross Rent is is $1,762, higher than the county's and state's values.
![Median Gross Rent](https://raw.githubusercontent.com/raimiassociates/ecr_dashboard/main/assets/images/Median%20Gross%20Rent.png)

The City's Median Monthly Housing Costs is $1,799, slightly higher than that of the state's and the county's values.
![Median Monthly Housing Costs](https://raw.githubusercontent.com/raimiassociates/ecr_dashboard/main/assets/images/Median%20Monthly%20Housing%20Costs.png)


# Interactive View of Existing Land Use
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

# Transportation
## Street Network Interactive Map

Streets around Marina City center:

<div id="folium-chart-3"></div>

# Opportunity Sites
Vacant and underutilized parcels (based on assessor parcels):

<div id="folium-chart-9"></div>


