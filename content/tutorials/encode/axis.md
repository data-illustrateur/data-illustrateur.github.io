---
title: "Axis"
description: ""
date: 2020-08-27T19:23:18+02:00
lastmod: 2020-08-27T19:23:18+02:00
draft: false
images: []
menu:
  tutorials:
    parent: "encode"
weight: 107
toc: false
---
When a [repeat](../../generate/repeat) action or a [data binding](../bind) action is performed, Data Illustrateur tries to automatically create an axis. An x-axis can be freely moved vertically, and a y-axis can be freely moved horizontally. You can also customize the following properties of an axis through the Property Inspector: whether to show axis path, whether to show axis ticks, whether to show axis title, axis orientation, stroke color, text color, position of axis path, tick offset, tick size, label offset, and label format. The figure below illustrates some of these properties:

{{< figure src="../axis.png" width="650px" alt="axis components" caption="" class="border-0 mx-auto text-center" >}}

If an axis is created as a result of binding a variable to position, you can customize the axis range. To do so, hover over the axis, a green range control will appear. Dragging the control will adjust the axis range extent. 

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/axis-range.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

By default, a horizontal numerical axis goes from left to right, and a vertical one goes from bottom to top. If you need to change the direction of axis, dragging the range control past the starting point flips the axis. 

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/axis-flip.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

Data Illustrateur also automatically changes the direction of numerical axes based on the layout's gravity property. If shapes are aligned to the top inside a collection with a grid layout, for example, the axis will flip to start from the top.

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/axis-gravity.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

