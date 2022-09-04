---
title: "Scale: Type, Aggregator, Reuse"
description: ""
date: 2020-08-27T19:23:18+02:00
lastmod: 2020-08-27T19:23:18+02:00
draft: false
images: []
menu:
  tutorials:
    parent: "encode"
weight: 115
toc: false
---

Whenever a [data binding](../bind) action is performed, Data Illustrateur creates an underlying scale, which specifies how the data values of the variable are mapped to the values of the visual property. If the data variable is numerical, by default, Data Illustrateur chooses a linear scale type. In the example below, we perfom divide twice to create a basic [Nightingale's rose chart](https://www.historyofinformation.com/detail.php?entryid=3815). We then bind the "Death" variable to the thickness of the arcs. The default scale type is linear, but the resulting visualization can be misleading: what we really want is to show the death count using the area of the arcs. To do so, we can click on the settings icon in the thickness property control and change the scale type to "square root". 

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/scale-type.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

<!-- When an object represents multiple rows of data, how the data is aggregated determines the final value that gets bound to a visual property. In the example below, each rectangle in the collection represents a country, corresponding to three rows of data. When we bind the variable "Count" to the width of the rectangles, Data Illustrator uses "Mean" as the default aggregator, and calculates the average of "Count" values for the three rows for each rectangle. This average value is used to create the scale. To change the aggregator, select the shape, and click the aggregator button in the property control. You can choose a different aggregator from the drop-down menu. The visualization and axis will be updated accordingly. -->



Certain visualization designs involve multiple data bindings, and sometimes it makes sense that these bindings share the same scale. In the example below, we want to create a Gantt Chart. We first repeat the rectangle by "Task", so that each rectangle represents a task. Then we direct select the left segments, bind "Start Date" to their x positions. Next, direct select the right segments, and as we are choosing the variable to bind to their x positions, the drop-down menus provide options: 1) to create a new scale, 2) to merge with the existing "Start Date" scale. In this design, merging the scales makes more sense. When we choose to bind "End Date" to the x positions of the right segments and merge scale, we have a single scale and axis that control the positions of both left and right segments.

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/scale-reuse.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}