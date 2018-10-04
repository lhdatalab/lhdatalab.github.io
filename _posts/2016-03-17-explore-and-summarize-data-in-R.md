---
layout: inner
position: left
title: 'Explore and Summarize Data in R (beta)'
date: 2016-08-08 21:15:00
categories: R EDA exploratory data analysis
tags: data R ggplot2 EDA exploratory data-analysis data-munging dplyr tidyr jsonlite lubridate cluster hierarchical-clustering regos rgdal sp SpatialPoints SpatialDataFrames JSON GeoJSON maps MongoDB mongolite rmongodb sqldf sampling undersampling New-York-City taxi
featured_image: 'img/posts/edav2.png'
project_link: 'https://github.com/lhdatalab/exploredatainR'
button_icon: 'github'
button_text: 'View on Github'
lead_text: "Use R and apply exploratory data analysis and data science techniques to New York City taxi data (open data). Investigate relationships from univariate to multivariate and explore distributions, outliers, and anomalies."

Recomendations:
# Recommendations

Yellow taxis dominate the sector in New York City. However, there are three possible clusters wit higher earnings where green taxis could compete with yellow taxis and possibly earn higher revenue per trip (on average $10).

1. Cluster 2 - Queens to Manhattan, Credit card, Standard rate, Street-hail, weekday trips earning median fares of $38.50.
2. Cluster 15 - Queens to Queens, Cash, Standard rate, Street-hail, weekend trips earning median fares $25.75
3. Cluster 14 - Manhattan to Brooklyn, Credit card, Standard rate, Street-hail, weekend trips with median fares $19.


Two of the three groups also bypass the JFK and Manhattan restrictions in place for the green taxi sector. To ascertain if 3. is outside of the Upper Manhattan pickup restrictions, we will have to drill down to the community level using the longitude and latitude coordinates provided.

The data actually showed an interesting, unexpected pattern of high average fare trips that are not in fact JFK-based. These are standard rate trips from Queens and are high for both cash and credit card customers serviced by the yellow taxi sector. 
The green sector can target the segment(s) in which yellow taxis make the most money.

In regards to JFK trips, it might not make sense for green taxis to target this segment as the increase in average fares is only $5-$6 than that earned from standard rate customers. They would also have the additional challenge of overcoming existing JFK street-hail regulation prohibiting them from targeting these customers.
---
