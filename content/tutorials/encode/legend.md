---
title: "Color Scheme and Legend"
description: ""
date: 2020-08-27T19:23:18+02:00
lastmod: 2020-08-27T19:23:18+02:00
draft: false
images: []
menu:
  tutorials:
    parent: "encode"
weight: 120
toc: false
---
When a [data binding](../bind) action is performed to encode a variable using fill color or stroke color, Data Illustrateur tries to automatically choose a color scheme and create a legend. You can freely move the legend around in the canvas.

If the variable is categorical, a categorical color scheme is chosen. You can edit the color mapping by clicking each color in the legend and choosing a desired color in the color picker. 

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/legend-categorical.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

If the variable is quantitative, Data Illustrateur will try to choose an appropriate color scheme based on the data values. For example, if the data values comprise both positive and negative values, the default color scheme will be diverging, with a mid point corresponding to 0. Otherwise, the default color scheme will be sequential. You can choose a different color scheme by click on the settings icon <img width="18px" src="../DI_ScaleSetting.png"> in the respective color property control and change the color scheme from a list of available options.  

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/legend-quant.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}