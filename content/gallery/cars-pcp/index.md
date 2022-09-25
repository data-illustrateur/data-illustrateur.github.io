---
title: "Features of Cars"
description: "Feature values of cars from the '70s and '80s."
excerpt: "Feature values of cars from the '70s and '80s in the form of a parallel coordinates plot."
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
dataset: "/app/csv/cars.csv"

---
This parallel coordinates plot shows the features of 406 cars. Original visualization appeared in Robert Spence's book [Information Visualization: an Introduction](https://books.google.com/books?id=uOosBQAAQBAJ&dq=406+cars+visualization&source=gbs_navlinks_s), page 69.

First, we draw a path consisting of six vertices. To make the path flat and horizontal, press the "Shift" key when drawing the path. Press the "Esc" key after drawing the last vertex. We then select the path, and repeat it for each row of data. The resulting collection contains 406 paths. Let's change the gap between the path to 1 pixel, and also set the layout to "none", so that we can proceed with data binding. 

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/pcp-1.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

Next, we use the direct selection tool to select each of the vertices in a path, and bind the y position to "economy(mpg)", "cylinders", "displacement(cc)", "power(hp)", "weight(lb)", and "year" respectively.   

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/pcp-2.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

Finally, we select any path to customize its stroke color and opacity. We can also customize the label format for the "year" axis.

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/pcp-3.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}