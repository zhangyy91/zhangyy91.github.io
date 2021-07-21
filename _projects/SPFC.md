---
layout: page
title: "SPFC: Asynchronous Graph Processing System"
description: >
  The real-world demands of mining big data and smart data of graph structure have led to an active research of distributed
  graph processing. Many distributed graph processing systems adopt a vertex-centric programming paradigm. In these
  systems, messages are passed between vertices to propagate the latest states. The communication efficiency and the high overhead
  of synchronization are two key considerations of these systems. In this work, we propose a Slow Passing Fast Consuming
  (SPFC) approach which can effectively improve the overall performance of vertex-centric graph processing systems. In our approach,
  the message passing is slow but the consuming is fast. More specifically, at the message sender side, priority is given to those smart
  messages which contribute more to the algorithm convergence, and at the message receiver side, messages are consumed right after
  arriving without any delay and intermediate buffer. Besides, by using a two-phase termination check protocol, the global synchronous
  barrier can be completely eliminated. In addition, based on the slow message passing strategy, further performance improvement can
  be achieved with some accuracy loss by eliminating those messages which are less useful for algorithm convergence. We implement
  our approach based on Apache Giraph and evaluate it on a 12-machine cluster. The experimental results show that our method can
  effectively reduce the amount of message traffic and achieve up to an order of magnitude performance improvement compared with
  Giraph and GraphLab.

img: 
importance: 3
category: system
---

The real-world demands of mining big data and smart data of graph structure have led to an active research of distributed
graph processing. Many distributed graph processing systems adopt a vertex-centric programming paradigm. In these
systems, messages are passed between vertices to propagate the latest states. The communication efficiency and the high overhead
of synchronization are two key considerations of these systems. In this work, we propose a Slow Passing Fast Consuming
(SPFC) approach which can effectively improve the overall performance of vertex-centric graph processing systems. In our approach,
the message passing is slow but the consuming is fast. More specifically, at the message sender side, priority is given to those smart
messages which contribute more to the algorithm convergence, and at the message receiver side, messages are consumed right after
arriving without any delay and intermediate buffer. Besides, by using a two-phase termination check protocol, the global synchronous
barrier can be completely eliminated. In addition, based on the slow message passing strategy, further performance improvement can
be achieved with some accuracy loss by eliminating those messages which are less useful for algorithm convergence. We implement
our approach based on Apache Giraph and evaluate it on a 12-machine cluster. The experimental results show that our method can
effectively reduce the amount of message traffic and achieve up to an order of magnitude performance improvement compared with
Giraph and GraphLab.
