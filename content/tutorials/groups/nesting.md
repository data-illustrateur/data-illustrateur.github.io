---
title: "Nesting"
description: ""
date: 2020-08-27T19:23:18+02:00
lastmod: 2020-08-27T19:23:18+02:00
draft: false
images: []
menu:
  tutorials:
    parent: "groups"
weight: 100
toc: false
---
Collections can be nested: the children of a collection do not have to be shaped, they can be collections as well. To create nested collections, we can apply the [repeat](../../generate/repeat) operation on a collection, or apply the [divide](../../generate/divide) operation on shapes inside a collection. 

### Repeat a Collection
In this example, we first create a collection of pies by dividing a circle. Then we can repeat the pie collection to form a nested collection.

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/divide-repeat.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

### Divide Shapes in a Collection
In this example, we first create a collection of rectangles using repeat. Then we can divide the rectangles in the collection to form a nested collection.

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/repeat-divide.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}