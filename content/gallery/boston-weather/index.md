---
title: "Boston Weather 2015"
description: "Daily max and min temperatures in Boston for year 2015."
excerpt: "Daily max, min and mean temperatures in Boston, MA for year 2015."
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
dataset: "bostonWeather"
chartType: "Range Chart"
msc: "RangeChart"
---
This range chart shows daily maximum, minimum and mean temperatures for a year in Boston. [Original visualization](http://weather-radials.com/) by [Timm Kekeritz](http://kekeritz.com/) of [Raureif](https://raureif.net/) was in the polar space, we demonstrate how to create similar designs in the Cartesian space.

First, we draw a vertical line (by holding down the Shift key), set its stroke width to 3, then repeat it by "date". 

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/boston-weather-1.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

Next, we select any line in the resulting collection, and bind its x position to "date". This will break the lines from the collection's grid layout, and create an x-axis. We then use the direct select tool to select the top vertex of any line, and bind its y position to "maxTemp". Next, we direct select the bottom vertex of any line, and bind its y position to "minTemp". Note here we have the option to either create a new scale, or merge with the existing scale created from "maxTemp. Let's merge the scale, and drag the y axis handle to make its range extent larger.

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/boston-weather-2.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

Finally, we select any line, and bind its stroke color to "meanTemp". Data Illustrateur automatically chooses a color scheme and a legend. We can change the orientation of the legend to "Horizontal", and move the legend below the chart. 

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/boston-weather-3.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}
