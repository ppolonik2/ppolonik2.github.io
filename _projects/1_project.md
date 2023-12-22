---
layout: page
title: Impact models meet physical science
description: Exploring how physical science influence statistical climate impact models
img: assets/img/Smoke_thumbnail.jpg
importance: 1
category: work
related_publications: 
---

Statistical climate impact models estimate how climatic factors like temperature and precipitation influence a human outcome of interest like economic activity (GDP) or agricultural output. In this project we explore how considerations from the physical Earth sciences bias these models and how those biases could potentially be adressed. 

We consider the role of:
 - measurement error
 - correlation between independent variables
 - mean climate state

Paper in prep!

Measurement error in this context often occurs because of interpolation used for gridded data products. Correlation between temperature (T) and precipitation (P) comes from physical coupling through mechanisms like evapotranspiration, but can lead to bias. Means are often subtracted as part of the statistical analysis (through the use of spatial fixed effects), but this may obscure a substantial part of the longer term climate signal.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/MeasurementFig.png" title="Global stations" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The length scales of temperature and precipitation are different and measurement systems are heterogeneous. (a-b) Measurement station locations for temperature (T) and precipitation (P) in the Global Historical Climatology Network (GHCN) database and their most recent year of reported data in color. (c) The distance [km] from every location on Earth to the nearest 2021 P measurement (note >100km is grouped). (d-i) Correlations between monthly local P and T anomalies measured in three regions. The pair-wise correlations between station anomalies are shown with an exponential fit to estimate the e-folding distance, or characteristic spatial scale. Horizontal axes differ. Unless otherwise specified, the rest of the study uses UDEL gridded T and P, which are largely based on the GHCN.
</div>


