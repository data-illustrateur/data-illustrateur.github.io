---
title: "Bind Data to Visual Property"
description: ""
date: 2020-08-27T19:23:18+02:00
lastmod: 2020-08-27T19:23:18+02:00
draft: false
images: []
menu:
  tutorials:
    parent: "encode"
weight: 105
toc: false
---
By default, objects (i.e. shapes and collections) behave exactly like those found in a typical vector editor. You can move them around, change their size and color, or delete them by pressing the "delete" button. To create data visualizations, we can manually alter the visual properties of objects. But this process is laborious and error-prone. Data Illustrateur provides automated support for binding data to visual properties of shapes, vertices, segments and collections.

To perform data binding, you need to first attach data to an object through the [repeat](../../generate/repeat), [divide](../../generate/divide), or [densify](../../generate/densify) operations. With a shape or a collection selected, the Property Inspector will display its visual properties. If a property can be bound to data, a binding button <img width="16px" src="../DI_Bind.png"> will appear next to the property control. Clicking on the binding button shows a drop-down menu of all the applicable variables (column names) that can be bound to the property. 

{{< figure src="../PropertyInspector.png" width="600px" alt="divide by data" caption="" class="border-0 mx-auto text-center" >}}

In the example below, we create a collection of rectangles, and then bind the variable "count" to the width of the rectangles. You can consider binding as a constraint on that property. Once the binding is created, you can no longer manipulate or change that property.

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/bind.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

After binding, the property control for "width" updates to show the binding variable, and the binding button is replaced by a "remove binding" button <img width="16px" src="../DI_Unbind.png">. Clicking on this button will remove the binding, and the constraint on rectangle width will be removed. Now you can freely change the width of the recangles.
