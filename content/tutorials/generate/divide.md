---
title: "Divide"
description: ""
date: 2020-08-27T19:23:18+02:00
lastmod: 2020-08-27T19:23:18+02:00
draft: false
images: []
menu:
  tutorials:
    parent: "generate"
weight: 80
toc: false
---
Like the repeat action, the divide action also requires a shape and a categorical variable to run. Given a categorical variable and a shape to start with, the divide action divides the shape, and associates each shape with a distinct value and the corresponding data rows.

Using the 2012 Olympic Medal dataset as an example again, let's say we want to divide a rectangle by the variable "Country". In this dataset, there are 20 distinct Country values. The divide action will divide the rectangle into 20 smaller rectangles. The first of these rectangles is associated with the first value ("United States") and the three data rows which share "United States" as their "Country" value; the second rectangle is associated with the second value ("China") and the three data rows representing China, and so on.

{{< figure src="../divide.png" width="400px" alt="divide by data" caption="" class="border-0 mx-auto text-center" >}}

To divide a shape by data in Data Illustrateur, select the shape and click the "divide" button in the Tool Bar. A dialog will appear, asking you which variable you want to divide the shape by. Data Illustrateur will also show you a preview of how the shape will be divided. Changing the variable will update the preview. After dividing, double click on an individual shape to select it and see the data rows attached to it in the Data Panel.

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/divide.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

The outcome of a divide operation depends on the shape and the orientation. The figure below illustrates how divide works for different shapes and orientations.

{{< figure src="../divide-outcomes.png" width="660px" alt="divide by data" caption="" class="border-0 mx-auto text-center" >}}