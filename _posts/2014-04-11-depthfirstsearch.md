---
layout: post
title: "DepthFirstSearch"
description: ""
category: 
tags: []
---
{% include JB/setup %}

**Depth First Search**

A quick refresher on graphs and trees, they are made of vertices V and these vertices are connected to each other via edges E. Depending on implementation, the edge could have other information such as direction of traversal.

One of the most basic graph and tree traversal/search algorithms out there is DFS.
In typical cases, DFS is used to traverse the entire graph. Basic idea behind DFS is to traverse the left-most (in most cases) child of the graph, until you hit a leaf (vertex with zero children). Once it hits the leaf, it backtraces to the immediate parent and visits the next left most vertex child. Important thing to remember here is a record of all visited vertices is kept and there are no repeat visits.
Here is an example of a [simple traversal.][1]

Time complexity of DFS is Θ(V + E)

Here is a nice in depth article for DFS [read here][2]


  [1]: http://en.wikipedia.org/wiki/Depth-first_search#Example
  [2]: http://www.personal.kent.edu/~rmuhamma/Algorithms/MyAlgorithms/GraphAlgor/depthSearch.htm