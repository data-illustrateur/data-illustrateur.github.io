---
title: "Olympic Medals 2012"
description: "The number of gold, silver and bronze medals by country in 2012 Summer Olympics."
excerpt: "The number of gold, silver and bronze medals by country in 2012 Summer Olympics."
date: 2020-11-04T09:19:42+01:00
lastmod: 2020-11-04T09:19:42+01:00
draft: false
weight: 50
images: [medals.png]
categories: ["News"]
tags: ["security", "performance", "SEO"]
contributors: ["Henk Verlinde"]
pinned: false
homepage: false
dataset: "olympic-medals"
msc: "StackedBarChart"
chartType: "Stacked Bar Chart"
---
This visualization shows 2012 Summer Olympic Medal Counts by National Olympic Committees (NOCs). Of the 204 NOCs participating, 85 received at least one medal. In this visualization, we show the top 20 NOCs.

First, we draw a rectangle, repeat it by "Country_Code", then divide it by "Medal_Type". 

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/olympic-medals-1.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

Next, we select any rectangle and bind its width to "Count" and fill color to "Medal_Type". We then customize the color mapping using the interactive legend.

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/olympic-medals-2.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

Finally, we change the horizontal gravity of the top collection's grid layout to "right" to align the bars to the right. Note how the x axis is flipped automatically. We also change the orientation of the y axis to "right" and hide the axis path.


{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/olympic-medals-3.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}