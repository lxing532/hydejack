---
layout: post
title: Infomap Community Detection Algorithm (Matlab version)
tags: [PROJECT]
description: >
  Final project of [CSCI5352](http://tuvalu.santafe.edu/~aaronc/courses/5352/).
---
- **Member**: Linzi Xing
- **Project page**: [Click here](https://github.com/lxing532/infoMap_project).

In the area of Network Science, community detection is always a very significant task. There are several mainstream methods wildly used like Modularity and Infomap. In this project, i try to implement Infomap algorithm on my own with Matlab which hasn't been used to implement and posted on [official website](http://www.mapequation.org/code.html).\\[0.5cm]
In 2007, Rosvall, Bergstrom and some other researchers proposed a brand new way in paper [An information-theoretic framework for resolving community structure in complex networks](http://www.pnas.org/content/104/18/7327.short) to solve community detection problem. Before their method, tasks of community detection always just focused on the links and edges of a network separately. It worked well, but no one treated the whole network as a system or map and had eye on the connection of interaction between nodes in network. Rosvall and Bergstrom tried to transfer the community discover problem into how to compress and encode the topological information of a network in the most efficient way to lose the least information and can get the most similar network compared to the original one after decoding the compression of network.\\[0.5cm]
After finishing implementation work, i also tested it with some famous datasets like Karate Club and Contigous States of USA and compared with greedy modularity. In some datasets, it has better performance. Final writeup paper can be found [HERE](https://github.com/lxing532/infoMap_project/blob/master/infomap_project%20writeup.pdf).


