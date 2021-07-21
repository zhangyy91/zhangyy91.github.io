---
layout: page
title: "BIGAT2VEC: Attributed Bipartite Network Embedding"
description: >
  This work investigates the modeling of attributes along with network structure for representation learning of the bipartite networks.
  Most of the attributed network representation learning (NRL) works consider the homogeneous type network only.
  However, these methods, when apply to bipartite type networks, may not be beneficial to learn an informative representation of nodes for predictive analysis. Hence, we propose a BIGAT2VEC framework that examines the internode relationships in the form of direct and indirect relations between two different
  as well as the same node type of bipartite network to preserve both structure and attribute context. 

  In BIGAT2VEC, learning is enforced on two levels: 
  1. Direct inter-node relationship between nodes of different type (either through the edge or attribute similarities perspective) by minimizing the probabilities through KL divergence;
  2. Indirect inter-node relationship within same node type (either through 2nd order neighborhood proximity and attributes similarities perspective) by employing shallow neural network model through maximizing the probabilities.

  These two levels are separately optimized,
  and we leverage its learned embeddings through late fusion to further execute the network mining tasks
  such as link prediction, node classification (multi-class and multilabel), and visualization.
  We perform extensive experiments on various datasets and evaluate our method with several baselines.
  The results show the BIGAT2VEC efficacy as compare to other (non)attributed representation learning methods.
img: 
importance: 3
category: learning
---

This work investigates the modeling of attributes along with network structure for representation learning of the bipartite networks.
Most of the attributed network representation learning (NRL) works consider the homogeneous type network only.
However, these methods, when apply to bipartite type networks, may not be beneficial to learn an informative representation of nodes for predictive analysis. Hence, we propose a BIGAT2VEC framework that examines the internode relationships in the form of direct and indirect relations between two different
as well as the same node type of bipartite network to preserve both structure and attribute context. 

In BIGAT2VEC, learning is enforced on two levels: 
 1. Direct inter-node relationship between nodes of different type (either through the edge or attribute similarities perspective) by minimizing the probabilities through KL divergence;
 2. Indirect inter-node relationship within same node type (either through 2nd order neighborhood proximity and attributes similarities perspective) by employing shallow neural network model through maximizing the probabilities.

These two levels are separately optimized,
and we leverage its learned embeddings through late fusion to further execute the network mining tasks
such as link prediction, node classification (multi-class and multilabel), and visualization.
We perform extensive experiments on various datasets and evaluate our method with several baselines.
The results show the BIGAT2VEC efficacy as compare to other (non)attributed representation learning methods.
