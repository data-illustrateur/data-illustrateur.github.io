---
title: "Percentage of Women Across Job Levels"
description: "The percentage of women declines as the job level goes higher."
excerpt: "The percentage of women declines as the job level goes higher in US corporations."
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
dataset: "/app/csv/gender-job-level.csv"

---
This mosaic plot shows that the percentage of women declines as the job level goes higher in US corporations, based on a 2016 survey. [Original visualization](http://www.womanindata.co.uk/2017/02/workout-wednesday-week-8-marimekko.html) by Emma Whyte.

First, we draw a rectangle, divide it by "Job Type", then select any resulting rectangle and divide it again by "Gender". 

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/mosaic-1.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

Next, with the resulting rectangle mark selected, we bind its width to "Percent Total", height to "Percent Gender", and drag the axis handles to customze the scale range extent.  

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/mosaic-2.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

We then select the width axis and change its orientation, so that it appears on top and does not overlap with the job type axis. We also perform additional axis customization such as removing titles and rotating labels for the job type axis.


{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/mosaic-3.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

Finally, we select any rectangle and bind its fill color to "Gender". We can customize the color mapping, and change the rectangle border color to white to show the boundaries more clearly.

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/mosaic-4.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

