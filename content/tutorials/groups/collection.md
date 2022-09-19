---
title: "Collection & Children Order"
description: ""
date: 2020-08-27T19:23:18+02:00
lastmod: 2020-08-27T19:23:18+02:00
draft: false
images: []
menu:
  tutorials:
    parent: "groups"
weight: 90
toc: false
---
The repeat and divide actions generate a **collection** of shapes. You may think of a collection as a "group" of shapes, where all the shapes in a collection have the same type (e.g., rectangle, line, path) and represent values of the same categorical variable. Each shape in a collection represents a unique value of the categorical variable. 

In Data Illustrateur, a selected collection is drawn with a green dashed border, as shown in the figure below. 
To select a shape inside a collection, double click on the shape. This will "open up" the collection, and its border is changed to a lighter shade of green.

{{< figure src="../collection.png" width="600px" alt="divide by data" caption="" class="border-0 mx-auto text-center" >}}

#### Children Order
By default, the order of the shapes in a collection is determined by the order of the categorical variable values they represent in the data table. You can use any variable in the data table to sort the shapes in a collection, either in ascending or descending order. To do this, select the collection, and choose the data variable to sort the children, and click the toggle button to switch between ascending or descending order.

{{< rawhtml >}} 
<video width=800px class="tutorial-video" controls>
    <source src="/videos/children-order.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}