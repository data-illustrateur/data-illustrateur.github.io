---
title: "Color Popularity among New Cars"
description: "How the rankings of new car colors change over the years in North America."
excerpt: "How the rankings of new car colors change over the years in North America."
date: 2020-11-04T09:19:42+01:00
lastmod: 2020-11-04T09:19:42+01:00
draft: false
weight: 50
images: [car-colors.png]
categories: ["News"]
tags: ["security", "performance", "SEO"]
contributors: ["Henk Verlinde"]
pinned: false
homepage: false
dataset: "/app/csv/newCarColors.csv"
msc: "BumpChart"
chartType: "Bump Chart"
---
This bump chart shows how the rankings of new car colors change over the years in North America. The magenta color denotes 'other' colors. [Original visualization](https://public.tableau.com/profile/rody.zakovich#!/vizhome/TheUntanglingofColorPopularityamongNewCarsinNorthAmerica/TheUntanglingofColorPopularityforNewCars) is designed by Rody Zakovich.

First, we draw a line, repeat it by "Color", then densify each line by "Year". 

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/car-colors-1.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

Next, we direct select any vertex on any line and bind the x position to "Year" and y position to "Rank".

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/car-colors-2.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

We then change the layout of the collection of polylines to "None", so that the lines share the same y axis. Let's rescale the axes to make the chart larger. Also, it is more intuitive to arrange the rankings from top to bottom, so we can drag the y axis handle to flip it. 


{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/car-colors-3.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

We then select any line, bind its stroke color to "Color", and make it thicker. These changes apply to all the other lines. Let's also customize the visual styles: change the curve mode of the lines to "Bump X", and update the vertex shape to circle with radius 4. Note that the vertex colors are consistent with the line stroke colors by default. 

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/car-colors-4.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

Finally, we change the background color, and customize the color mapping through the interactive legend, so that the colors match their names. We can also change the text color of the axes to make them easier to read.

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/car-colors-5.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}