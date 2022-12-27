---
title: "Obesity vs. Education in U.S. States"
description: "Obesity is inversely correlated with education level across US states."
excerpt: "The inverse relationship between the obesity level and education level across US states."
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
dataset: "obesityEducation"
msc: "SlopeGraph"
chartType: "Slope Graph"
---
This visualization shows that on average, percentage of obesity is inversely correlated with the percentage of population having a bachelor degree or higher. Each line represents a U.S. state. The left axis represents the obesity percentages, the right axis represents the percentages of people with a higher education. [Original visualization](http://www.thefunctionalart.com/2012/03/functional-art-has-cover_21.html) created by Alberto Cairo.


First, we draw a line, repeat it by "State", then set the resulting collection's layout to "none". We then select the first vertex of every line, and bind its y position to "Obesity Percentage"; similarly, we bind the y position of the second vertex to "BA Degree Percentage". Since we want these two encodings to share the same scale, we choose the option "Merge with Obesity Percentage" when binding to "BA Degree Percentage".

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/slope-graph-1.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

Next, let's style the lines. We select the vertices, set their shapes to circle with a radius of 4 pixels. We then select the lines, bind their stroke color to the categorical field "Obesity vs. Higher Education". The default color scale is not what we want exactly, so we can customize the colors for the two categories. Let's also thicken the stroke width and change the opacity of the lines.

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/slope-graph-2.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

Finally, let's drag the axis handle to increase the range extent. Since the scales are merged, dragging one axis handle also affects the other. We can flip the orientation of the y axis for "BA Degree Percentage" to the right, so that the two axes look more symmetrical. 

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/slope-graph-3.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}


