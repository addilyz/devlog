---
title: "forests and stuff!"
date: 2025-07-19
---
<img src="{{ squick.dev }}/julynineteencontent.png">

heya! this week i got some good protyping done. this is a prototype of the isometric tiling module i'm going to be making, and next week i plan to show you a shiny new textbox module on top of it, too! i also found some relatively-useless-for-this-purpose angle math that i have turned into a library in my repo https://codeberg.org/addilyz/math where i'll be keeping all my useful math libraries i don't want to have to relearn! it is able to get the angle of a point that has been set up relative to an anchor treated as it's {0,0} coordinate, meaning you can subtract one point's x and y from another point's x and y and pass the resulting {x1-x2,y1-y2} table to get an angle. it also has functions for projectile support and vector rotation around an anchor if you would like that kind of thing. the default 0 direction you should point your vectors would be straight below the origin point! i should probably stop babbling on and on, see you next week!
