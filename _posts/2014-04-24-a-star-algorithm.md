---
layout: post
title: "A Star Algorithm"
description: ""
category: algorithms
tags: [computer_science,algorithms]
---
{% include JB/setup %}

**A* Algorithm**

A Star is probably one of the most important and most used path find algorithms. Used in many destinations like online maps or even games!

One thing I would recommend you read is [heuristic function][1]

Now that you are ready! basically A* consists of

1. Start node
2. Destination node
3. H Score/Value (Heuristic value)  = Shortest distance from current node to destination node, there are many approaches to this, Manhattan distance is a famous one.
4. G Score = Shortest distance from start node to the current node.
5. F Score = H + G

One a given map of connected nodes/tiles, A* algorithm would go along the smallest value of F. Ofcourse there could be obstacles that would prohibit the passage on a tile/s.

Here is a great video that explains this in further details.

<iframe width="420" height="315" src="//www.youtube.com/embed/Kw8AMmyc6vg" frameborder="0" allowfullscreen></iframe>


  [1]: /concepts/2014/04/23/heuristic-function/