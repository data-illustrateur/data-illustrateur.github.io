---
title: "Stock Prices"
description: "Monthly Stock Prices of four companies: Amazon, Apple, IBM and Microsoft from Jan 1, 2000 to Mar 1, 2010. Original visualization was composed using d3.js on d3noob.org"
excerpt: "Monthly average stock prices of four companies from Jan 1, 2000 to Mar 1, 2010."
date: 2020-11-04T09:19:42+01:00
lastmod: 2020-11-04T09:19:42+01:00
draft: false
weight: 50
images: [stocks.png]
categories: ["News"]
tags: ["security", "performance", "SEO"]
contributors: ["Henk Verlinde"]
pinned: false
homepage: false
dataset: "/app/csv/stocks.csv"
msc: "MultiLineGraph"
chartType: "Multi-Line Graph"
---
Monthly Stock Prices of four companies: Amazon, Apple, IBM and Microsoft from Jan 1, 2000 to Mar 1, 2010. Original visualization was composed using d3.js on [d3noob.org](https://bl.ocks.org/d3noob/08af723fe615c08f9536f656b55755b4).

First, we draw a line, repeat it by "Company", then densify each line by "Date". 

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/stocks-1.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

Next, we select any line and bind its stroke color to "Company". Let's also change the stroke width to make it thicker.

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/stocks-2.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

We then use the direct selection tool to select any vertex in a line, and bind its x position to "Date" and y position to "Price".


{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/stocks-3.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

Finally, we want all the lines to be displayed in the same chart, sharing the same scale. To do this, we select the top level collection, and change the layout from "Grid" to "None". We can then adjust the axis range to make the chart more readable.

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/stocks-4.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}