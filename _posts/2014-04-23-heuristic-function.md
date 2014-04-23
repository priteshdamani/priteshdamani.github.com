---
layout: post
title: "Heuristic function"
description: ""
category: concepts
tags: [concepts,computer_science]
---
{% include JB/setup %}

**Heuristic Function**

Simply speaking a heuristic function is a way to rank alternatives/options in navigating a search algorithm at each of the branching alternative based on the information at hand.

Shortest Path Algorithm is a great example on how heuristic function is used. h(n) is defined on the nodes of a search tree. In case of the shortest path algorithm h(n) estimates of the cost of the cheapest path from that node to the goal node.

Greedy Best First will choose the lowest value of the h(n).

A* is another great one, but I will write a separate post about that!

