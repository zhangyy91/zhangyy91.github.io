---
layout: page
title: "HotML: A DSM-based Machine Learning System"
description: >
  In big data era, social networks, such as Twitter, Weibo, Facebook, are becoming more and more popular worldwide. To help social networks analysis, many machine learning (ML) algorithms have been adopted, e.g. user classification, link prediction, sentiment analysis, recommendations, etc. However, the dataset could be so large that it might take even days to train a model on a machine learning system. Performance issues should be considered to boost the training process. In this paper, we proposed HotML, a general machine learning system. HotML is designed in the parameter server (PS) architecture where the servers manage the globally shared parameters organized in tabular structure, and the workers compute the dataset in parallel and update the global parameters. HotML supports high-level data abstraction and Map/Reduce-like data flow operations with user-friendly interface, flexible consistency models like SSP, fault tolerance including consistent server-side checkpoint and flexible worker-side checkpoint, and workload balancing. Experimental results show that HotML can reduce networking time by about 74%, and achieve up to 1.9× performance compared to the popular ML system, Petuum.
img: 
importance: 2
category: system
---

In big data era, social networks, such as Twitter, Weibo, Facebook, are becoming more and more popular worldwide. To help social networks analysis, many machine learning (ML) algorithms have been adopted, e.g. user classification, link prediction, sentiment analysis, recommendations, etc. However, the dataset could be so large that it might take even days to train a model on a machine learning system. Performance issues should be considered to boost the training process. In this paper, we proposed HotML, a general machine learning system. HotML is designed in the parameter server (PS) architecture where the servers manage the globally shared parameters organized in tabular structure, and the workers compute the dataset in parallel and update the global parameters. HotML supports high-level data abstraction and Map/Reduce-like data flow operations with user-friendly interface, flexible consistency models like SSP, fault tolerance including consistent server-side checkpoint and flexible worker-side checkpoint, and workload balancing. Experimental results show that HotML can reduce networking time by about 74%, and achieve up to 1.9× performance compared to the popular ML system, Petuum.