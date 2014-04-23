---
layout: post
title: "Breadth First Search"
description: ""
category: algorithms
tags: [computer_science,algorithms]
---
{% include JB/setup %}

**Breadth-First Search**

One of the most basic graph and tree traversal/search algorithms out there is BFS. In typical cases, BFS is used to traverse the entire graph.

From the standpoint of the algorithm, all child nodes obtained by expanding a node are added to a FIFO (i.e., First In, First Out) queue. In typical implementations, nodes that have not yet been examined for their neighbors are placed in some container (such as a queue or linked list) called "open" and then once examined are placed in the container "closed".

Space Complexity of BFS is O(V + E)
Time Complexity of BFS is O(V + E)

You can [read more here][1] and [here][2]

Also note, [Depth First Search][3]


  [1]: https://www.princeton.edu/~achaney/tmve/wiki100k/docs/Breadth-first_search.html
  [2]: http://en.wikipedia.org/wiki/Breadth-first_search
  [3]: /algorithms/2014/04/11/depthfirstsearch/