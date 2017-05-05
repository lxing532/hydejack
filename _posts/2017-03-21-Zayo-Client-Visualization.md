---
layout: post
title: Zayo Client Visualization
tags: [PROJECT]
description: >
  Project of [INFO5602](http://danielleszafir.com/teaching.html).
---
- **Member**: Linzi Xing, Xiaolei Huang, Hayeong Song, Paige Johnson, Camille Owens
- **Project page**: [Click here](https://github.com/INFO-4602-5602/project1-zayo-project1).

This visualization can be mainly used to predict the Zayo's target clients' attributes. According to these customers' common features. Zayo can put more source into the correspond kinds of users and get the most profit.

The visualization tool is built by [d3.js](https://d3js.org/), [dc.js](https://dc-js.github.io/dc.js/) and [leaflet](http://leafletjs.com/). All these three are open-source javascript libraries. There are five different visualizations which combined as the final dashboard. They are: Map, Monthly Revenue and CPQ Analysis, MRR Analysis, Group Performance Analysis and Tabular Exploration. The first version was mainly created by dc.js. Marks on map can be filtered by the market, stage and clients' industry.

![800x400](http://deanxing.net/public/img/zayo3.png "Version 1 with dc.js"){:.lead}

Since some other visualization modules were based on the d3 v4, which was different from d3 v3 which dc.js was based on. Finally, we eliminated some dc parts to resolve the d3 versions conflict. The final version panel is shown below:

![800x400](http://deanxing.net/public/img/zayo2.png "Final Version")
