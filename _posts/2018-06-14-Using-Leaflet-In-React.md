---
layout: post
title:  "Using Leaflet in a React App"
date:   2018-06-14 16:01:00 -0500
categories: project app NSSL
---

When asked for a tool to display data visualizations in the context of geographic location where an overview was default, my response was to create a single page app in React, embedding a Leaflet map viewer where the viz product is displayed as an overlay.

At my suggestion, the viz was output in SVG since what matters to weather scientists using these images are pixel-granularity anomalies. My clients even included icons to assist with finding these anomalies for their intended users. 

![My helpful screenshot]({{site.url}}/images/leaflet_react.gif)
