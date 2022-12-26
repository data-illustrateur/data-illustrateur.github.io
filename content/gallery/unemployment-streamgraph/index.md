---
title: "Unemployment by Industry"
description: "Number of unemployed people in four industries from 2000 to 2010."
excerpt: "Number of unemployed people in four industries from 2000 to 2010."
date: 2020-11-04T09:19:42+01:00
lastmod: 2020-11-04T09:19:42+01:00
draft: false
weight: 50
images: [figure.png]
categories: ["News"]
tags: ["security", "performance", "SEO"]
contributors: ["Henk Verlinde"]
pinned: false
homepage: false
dataset: "/app/csv/unemployment-2.csv"
msc: "StreamGraph"
chartType: "Stream Graph"
---
This visualization shows the number of unemployed people in four industries (Manufacturing, Leisure and hospitality, Business services and Construction) from 2000 to 2010 in the form of a streamgraph. [Original visualization](https://observablehq.com/@d3/streamgraph) is from observablehq.com.

First, we draw a rectangle, divide it by "industry", then select any resulting rectangle and densify it by "date". 

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/streamgraph-1.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

Next, with the resulting area mark selected, we bind its x position to "date", height to "unemployments", and fill color to "industry". Finally, we select the collection of area marks, which is organized using a stack layout, and change the vertical gravity to "middle".  

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/streamgraph-2.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

