---
title: "Layout"
description: ""
date: 2020-08-27T19:23:18+02:00
lastmod: 2020-08-27T19:23:18+02:00
draft: false
images: []
menu:
  tutorials:
    parent: "groups"
weight: 95
toc: true
---
Items in a collection can be positioned using a **layout**. Data Illustrateur provides the following layouts: grid, stack, pack, treemap, and none. You can change the layout applied to a collection through the control in the Property Inspector panel.

### Grid Layout
By default, shapes generated using the [repeat](../../generate/repeat) operation are placed in a grid layout. Parameters of a grid layout include: number of rows, row gap, number of columns, column gap, horizontal & vertical gravity. The gravity parameters determine if the shape inside each grid cell is aligned to the left, center, right, top, middle or bottom of the cell. In Data Illustrateur, all the parameters can be changed through the controls in the Property Inspector. In addition, the row gap and column gap can be changed by dragging the pink rectangles between the grid rows and columns. 

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/grid.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

### Stack Layout
By default, shapes generated using the [divide](../../generate/divide) operation are placed in a stack layout. 
Parameters of a stack layout include: orientation, horizontal & vertical gravity. The gravity parameters determine if the shape inside each grid cell is aligned to the left, center, right, top, middle or bottom of the cell. In Data Illustrateur, all the parameters can be changed through the controls in the Property Inspector.

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/stack.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

### Pack Layout
The pack layout is applicable to a collection of circles, as shown in the figure below.

{{< figure src="../pack.png" width="400px" alt="divide by data" caption="" class="border-0 mx-auto text-center" >}}

### Treemap Layout
The treemap layout is applicable to a collection of rectangles, as shown in the figure below.

{{< figure src="../treemap.png" width="400px" alt="divide by data" caption="" class="border-0 mx-auto text-center" >}}

### None
You can also change the layout of a collection to "None", doing so will allow you to freely move the shapes around, and apply data encodings to the shapes' visual properties. 

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/none.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}