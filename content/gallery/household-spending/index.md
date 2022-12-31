---
title: "Household Spending Comparison"
description: "Comparing household spending patterns in the UK and New Zealand in 1980 and 2008."
excerpt: "Comparing household spending patterns in the UK and New Zealand in 1980 and 2008."
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
dataset: "household_spending"
msc: "MultiplePieCharts"
chartType: "Small Multiples: Pie Chart"
---
This chart compares household spending patterns in the UK and New Zealand in 1980 and 2008. Data source is [here](https://www.ieltstrainingtips.com/the-charts-below-show-household-spending-patterns-in-two-countries-between-1980-and-2008/).


First, we draw a circle, set its fill color, repeat it by "Country", then repeat the resulting collection again by "Year". To customize the appearance of the x-axes, we make the path and ticks invisible, and change the orientation to "top". We can also increase the gap between the rows by dragging the pink gap area.

{{<demo-video>}}t9HVhb-p1bg{{</demo-video>}}


Next, we select any circle and divide it bt "Category". This gives us four pie charts. We then select any of the pies, and bind its angle to "Percentage" and fill color to "Category".

{{<demo-video>}}ps6i657_z7U{{</demo-video>}}

Finally, we customize the color mapping through the interactive legend, change the visual appearance and label format of the y-axis, and increase the gap between the columns. 

{{<demo-video>}}4kECuVb2svw{{</demo-video>}}
