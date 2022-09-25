---
title: "Bitcoin Prices: 2013 - 2018 "
description: "Evolution of the bitcoin price from Apr 28, 2013 to Apr 23, 2018."
excerpt: "Time series data about the price of Bitcoin from Apr 28, 2013 to Apr 23, 2018."
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
dataset: "/app/csv/bitcoin-price.csv"

---
This area chart shows how the bitcoin prices are changing from 4/28/2013 to 4/23/2018. [Original visualization](https://d3-graph-gallery.com/graph/area_basic.html) is from https://d3-graph-gallery.com/.

First, we draw a rectangle, set its fill color to gold, then densify it by "date". 

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/bitcoin-prices-1.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

Next, we select the resulting area mark, and bind its x position to "date", and height to "value". By default, the area chart's baseline is at the bottom, we can change the baseline to top or middle through the "baseline" property control. 

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/bitcoin-prices-2.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}