---
title: "Nightingale's Rose Chart"
description: "Florence Nightingale's rose diagram showing the causes of death in the Crimean War."
excerpt: "Florence Nightingale's rose diagram showing the causes of death in the Crimean War."
date: 2020-11-04T09:19:42+01:00
lastmod: 2020-11-04T09:19:42+01:00
draft: false
weight: 50
images: [RoseChart.png]
categories: ["News"]
tags: ["security", "performance", "SEO"]
contributors: ["Henk Verlinde"]
pinned: false
homepage: false
dataset: "nightingale"
msc: "RoseChart"
chartType: "Rose Chart / Coxcomb Chart"
---
A reproduction of [Florence Nightingale’s rose diagram](https://www.historyofinformation.com/detail.php?entryid=3815). Data Source: Nightingale, F., Farr, W., & Smith, A. (1859). A contribution to the sanitary history of the British army during the late war with Russia. John W. Parker and Son.

First, we draw a circle, divide it by "Month", then divide the resulting pie by "Type". 

{{<demo-video>}}k5uRvZO3-tw{{</demo-video>}}

<!-- {{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/rose-chart-1.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}} -->

Next, we select any arc and bind its thickness to "Death". The default scale type is linear, we change it to "Square Root" so that the area represents the death count.

{{<demo-video>}}y60deFGMp-I{{</demo-video>}}

<!-- {{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/rose-chart-2.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}} -->

Finally, we bind the fill color of each arc to "Type", and customize the color mapping.

{{<demo-video>}}JDI1-iqndUM{{</demo-video>}}

<!-- {{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/rose-chart-3.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}} -->