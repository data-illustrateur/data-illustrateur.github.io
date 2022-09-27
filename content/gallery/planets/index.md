---
title: "Goldilocks Worlds"
description: "Which planets are habitable and just right for life? Temperature and mass matter."
excerpt: "Which planets are habitable and just right for life? Temperature and mass matter."
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
dataset: "/app/csv/planets.csv"

---
This bubble plot shows 1626 planets and which ones are habitable. Temperature should not be too hot or too cold. The mass also plays a role: a small planet can't have an atmosphere, while a large one will have a crushing atmosphere. [Original visualization](http://www.nationalgeographic.com/astrobiology/goldilocks-worlds/) by John Tomanio and Xaquin G.V., NGM STAFF. Source: Abel Méndez, Planetary Habitability Laboratory, University of Puerto Rico at Arecibo.


First, we draw a circle, repeat it by each row of data, bind its x position to "hzd" (habitable zone distance), and bind the y position to "mass". Since we want the planets with greater masses to be shown towards the bottom, we need to flip the y axis. To do this, we can drag the axis handle past the starting point. We also want the planets with small masses to spread out more, so we customize the y encoding by choosing a log scale. 

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/planets-1.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

Next, we encode the radius of the circles using the "radius" data attribute, and the fill color using "hzd". Since the hzd values range from -3.0 to 3.0, Data Illustrateur chooses a diverging color scale by default. We can customize it by choosing a red-yellow-blue scale. We then set the opacity of the circles to 0.5, and set the background color to black. We can also directly drag the circles to resize them, and the size encoding will be maintained. Finally, we change the axis and legend colors to light gray, so that they stand out from the dark background. 

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/planets-2.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}