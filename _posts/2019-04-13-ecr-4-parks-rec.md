---
title: "Chapter 4: Parks and Recreation"
date: 2019-04-13
published: true
tags: [dataviz, altair, hvplot, holoviews]
excerpt: "Enhance quality of life with abundant resources for parks and recreation."
altair-loader:
  altair-chart-1: "charts/measlesAltair.json"
hv-loader:
  hv-chart-1: ["charts/measlesHvplot.html", "500"] # second argument is the height
toc: true
toc_sticky: true
---

This post will show examples of embedding interactive charts produced using [Altair](https://altair-viz.github.io) and [Hvplot](https://hvplot.pyviz.org/).

## Altair Example

Below is a chart of the incidence of measles since 1928 for the 50 US states.

<div id="altair-chart-1"></div>

This was produced using Altair and embedded in this static web page. Note that you can also display Python code on this page:

```python
import altair as alt
alt.renderers.enable('notebook')
```

## HvPlot Example

Lastly, the measles incidence produced using the HvPlot package:

<div id="hv-chart-1"></div>

## Notes

**Important: When embedding charts, you will likely need to adjust the width/height of the charts before embedding them in the page so they fit nicely when embedded.**
