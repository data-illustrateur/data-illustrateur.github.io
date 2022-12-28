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
dataset: "unemployment-2"
msc: "StreamGraph"
chartType: "Stream Graph"
---
This visualization shows the number of unemployed people in four industries (Manufacturing, Leisure and hospitality, Business services and Construction) from 2000 to 2010 in the form of a streamgraph. [Original visualization](https://observablehq.com/@d3/streamgraph) is from observablehq.com.

First, we draw a rectangle, divide it by "industry", then select any resulting rectangle and densify it by "date". 

{{<demo-video>}}6p6OzSW3W4o{{</demo-video>}}

<!-- {{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/streamgraph-1.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}} -->

Next, we select any of the top vertices in any resulting area mark, and bind its x-position to "date"; we do the same for the bottom vertices and choose to merge with the existing date scale. Data Illustrateur distinguishes between a vertex's x-position and an area mark's x-position, here we are using the former to encode "date". 

We then select any area mark and bind its height to "unemployments", and fill color to "industry". Finally, we select the collection of area marks, which is organized using a stack layout, and change the vertical gravity to "middle".  

{{<demo-video>}}sguV0pGgGcc{{</demo-video>}}

<!-- {{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/streamgraph-2.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}} -->

