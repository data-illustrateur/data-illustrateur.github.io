---
title: "Repeat"
description: ""
date: 2020-08-27T19:23:18+02:00
lastmod: 2020-08-27T19:23:18+02:00
draft: false
images: []
menu:
  tutorials:
    parent: "generate"
weight: 70
toc: false
---
The repeat action requires a shape and a categorical data variable to run. The shape can be of any type (e.g. line, rectangle, circle). The data variable must be categorical, containing more than one distinct values. Using the 2012 Olympic medal dataset as an example, "Row ID" is a categorical variable, containing 60 distinct values. "Country" is another categorical variable, containing 20 distinct values. "Count" is not a categorical variable, it is numerical.

{{< figure src="../repeat.png" width="400px" alt="repeat by data" caption="" class="border-0 mx-auto text-center" >}}

Given a categorical variable and a shape to start with, the repeat action duplicates the shape, and associate each shape with a distinct value and the corresponding data rows. For example, if the chosen variable is "Row ID", the first shape is associated with "R1" and the first data row, the second shape associated with "R2" and the second row, and so on. If the chosen variable is "Country", the first shape is associated with the first value ("United States") and the three data rows which share "United States" as their "Country" value; the second shape is associated with the second value ("China") and the three data rows representing China, and so on.

To repeat a shape by data in Data Illustrateur, you must have [imported a dataset first](../../data). Select the shape and then click the "Repeat" button in the Tool Bar. Data Illustrateur will show a preview of the repeat action, with one duplicated shape in addition to the original one. You can choose the data variable to repeat the shape by, and the preview will update accordingly. After repeating, double click on an individual shape to select it and see the data rows attached to it in the Data Panel.

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/repeat.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}