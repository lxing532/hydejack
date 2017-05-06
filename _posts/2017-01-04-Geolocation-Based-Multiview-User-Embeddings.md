---
layout: post
title: Geolocation Based Multiview User Embedding for Twitter
tags: [PROJECT]
description: >
  Final project of [CSCI5622](http://www.colorado.edu/catalog/2014-15/courses/engr/b-csci/5622-machine-learning) with Xiaolei Huang and Yoshinari Fujinuma.
---
- **Member**: Linzi Xing, Xiaolei Huang, Yoshinari Fujinuma
- **Project page**: Since some private datasets in Github repository. We didn't set it as public source. For report, [click here](http://deanxing.net/public/paper/mlfinal.pdf)

There are various methods to get user representations of social media. It depends on what kind of source we can reach and the properties and attributes of social media we focus on. Here, our study object is Twitter. This research is based on original publication *"[Learning Multiview Embeddings of Twitter Users](http://www.cs.jhu.edu/~mdredze/datasets/multiview_embeddings/)"* by *Adrian Benton et al.*. In their work, [WGCCA embedding model](http://aclweb.org/anthology/P/P16/P16-2003.pdf) was applied and unlike the other main approach similar to paragraph vector embedding, it can include multiple views and user attributes at the same time. To improve embedding process, the gist of this project is to add geolocation info into model and we found for some tasks like hashtag prediction, accuracy can be improved in some level.
