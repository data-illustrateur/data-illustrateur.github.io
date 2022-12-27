---
title: "Twenty Years of NBA Draft Picks"
description: "NBA players ordered by draft pick and colored by their overall contributions from 1989 to 2008."
excerpt: "NBA players ordered by draft pick and colored by their overall contributions from 1989 to 2008."
date: 2020-11-04T09:19:42+01:00
lastmod: 2020-11-04T09:19:42+01:00
draft: false
weight: 50
images: [figure.png]
categories: ["News"]
tags: ["security", "performance", "SEO"]
contributors: ["Henk Verlinde"]
pinned: false
homepage: false
dataset: "nbaRedraft"
msc: "HeatMap"
chartType: "Heatmap"
---
This heatmap colors each player by VORP (Value over Replacement Player), which converts the BPM rate into an estimate of each player's overall contribution to the team, measured vs. what a theoretical 'replacement player' would provide, where the 'replacement player' is defined as a player onminimum salary or not a normal vmember of a team's rotation. A VORP of -20 is used for players that did not play enough minutes.

[Original visualization](https://pudding.cool/2017/03/redraft/) by [Russell Goldenberg](http://russellgoldenberg.com/) at The Pudding.


First, we draw a thin rectangle, repeat it by each row of data, bind its x position to "Draft_Year", and bind the y position to "Draft_Pick". Let's first make the x scale wider by dragging the axis handle. Since we want the first draft picks to appear on top, we need to flip the y axis. To do this, we can drag the axis handle past the starting point.

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/nba-redraft-1.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}

Next, we encode the fill color using "VORP". Since the VORP values include both positive and negative numbers, Data Illustrateur chooses a diverging color scale by default. We then set the background color to black, and change the x axis' orientation to top. Finally, we change the axis and legend colors to light gray, so that they stand out from the dark background. 

{{< rawhtml >}} 
<video width=700px class="tutorial-video" controls>
    <source src="/videos/gallery/nba-redraft-2.mov" type="video/mp4">
    Your browser does not support the video tag.  
</video>
{{< /rawhtml >}}