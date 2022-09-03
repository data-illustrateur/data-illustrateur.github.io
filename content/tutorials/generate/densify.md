---
title: "Densify"
description: ""
date: 2020-08-27T19:23:18+02:00
lastmod: 2020-08-27T19:23:18+02:00
draft: false
images: []
menu:
  tutorials:
    parent: "generate"
weight: 85
toc: false
---
The densify action also requires a shape and a categorical variable to run. Given a categorical variable and a shape to start with, the densify action adds vertices to a shape, and associates each vertex with a distinct value and the corresponding data rows.

For example, let's say we first repeat a line by "Company" in a dataset about companies' stock prices. Each line is associated with a distinct company value, and the data rows sharing the same company value. In the figure below, the blue line is associated with "Microsoft" while the orange line is associated with "Amazon".

Now assume we want to densify each line by "Date". The densify action divides each line into multiple segments, and each vertex is associated with a distinct date value. The first vertex is associated with "Jan 1, 2006" and the corresponding row, the second vertex associated with "Feb 1, 2006", and so on.

{{< figure src="../densify.png" width="500px" alt="divide by data" caption="" class="border-0 mx-auto text-center" >}}

To densify a shape by data in Data Illustrateur, select the shape and click the "densify" button in the Tool Bar. A dialog will appear, asking you which variable you want to densify the shape by. Data Illustrateur will also show you a preview of how the shape will be densified. Changing the variable will update the preview. After densifying, select an individual vertex and see the data rows attached to it in the Data Panel.

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/densify.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

The outcome of a densify operation depends on the shape and the orientation, as illustrated in the figure below. 

{{< figure src="../densify-outcomes.png" width="660px" alt="divide by data" caption="" class="border-0 mx-auto text-center" >}}