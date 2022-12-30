---
title: "US Unemployment 1980 - 2015"
description: "The unemployment rate for each U.S. state from 1980 to 2015 at five-year intervals."
excerpt: "The unemployment rate for each U.S. state from 1980 to 2015 at five-year intervals."
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
dataset: "us_state_unemployment_final"
msc: "MultipleBarCharts"
chartType: "Small Multiples: Bar Chart"
---
This visualization shows how the unemployment rate for each U.S. state changed from 1980 to 2015 at five-year intervals.
The height of bar represents the difference of unemployment rate from the national average. Data source: [Federal Reserve Bank](https://fred.stlouisfed.org/release?rid=112).

First, we draw a rectangle, repeat it by "State", then select any resulting rectangle and bind its x-position and y-position to "MapX" and "MapY" respectively. We rescale the axes to spread out the rectangles.

{{<demo-video>}}XMEvPgMVWYs{{</demo-video>}}

Next, we select any of the rectangles and divide it by "Year". This gives us a bunch of rectangle collections, each representing the years for an individual state. We then select any of the rectangles in any of the collection, and bind its height to "Unemployment", fill color to "US Avg", and change its stroke color to white. We then customize the color mapping so that "Above Average" is red, and "Below Average" is green. We can also adjust the height axis as needed.

{{<demo-video>}}MtY1PEPK8UI{{</demo-video>}}

We then create a text item using the Text Tool, and repeat it by "State". Similar to what we did earlier for the rectangles, we bind the texts' x-position to "MapX" and y-position to "MapY". For "MapX", we want it to be using the same axis as the rectangle collections, so we choose the option "Merge with MapX" when binding. For "MapY", we choose the option "Create new scale" instead, because we don't want the text to be overlapping with the rectangles.

{{<demo-video>}}I4Q8YgJeXN8{{</demo-video>}}

Finally, we make some adjustment to the spacing of the text and rectangles by dragging the axis handles. To use the actual state names, we select any of the text items and bind its content to "State". 

{{<demo-video>}}gp-TEBZ4ptU{{</demo-video>}}
