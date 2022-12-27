---
title: "GDP Changes"
description: "Quarterly change in U.S. GDP from 2017 to 2020, compared to the preceding quarter."
excerpt: "Quarterly change in U.S. GDP from 2017 to 2020, compared to the preceding quarter."
date: 2020-11-04T09:19:42+01:00
lastmod: 2020-11-04T09:19:42+01:00
draft: false
weight: 50
images: [BarChartVert.png]
categories: ["News"]
tags: ["security", "performance", "SEO"]
contributors: ["Henk Verlinde"]
pinned: false
homepage: false
dataset: "GDP%20Change"
msc: "BarChartVert"
chartType: "Grouped Bar Chart"
---
This visualization shows the percent change of U.S. Real Gross Domestic Product (GDP) in each quarter from 2017 to 2020, compared to the preceding quarter. Data source: U.S. Bureau of Economic Analysis

First, we draw a rectangle, set its fill color, repeat it by "Quarter", then repeat the resulting collection again by "Year". 

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/gdp-change-1.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

Next, we select any rectangle and bind its height to "% Change". We then customize the axis position and style. 

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/gdp-change-2.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}
