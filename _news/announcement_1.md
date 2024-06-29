---
layout: post
title: Our paper "TorchGT':' A Holistic System for Large-scale Graph Transformer Training" was accepted by <b>SC 2024</b>.
date: 2024-06-29 16:11:00-0400 
inline: false
related_posts: false
---

Graph Transformer is a new architecture that surpasses GNNs in graph learning. While there emerge inspiring algorithm advancements, their practical adoption is still limited, particularly on real-world graphs involving up to millions of nodes. We observe existing graph transformers fail on large-scale graphs mainly due to heavy computation, limited scalability and inferior model quality. Motivated by these observations, we propose TorchGT, the first efficient, scalable, and accurate graph transformer training system. TorchGT optimizes training at different levels. At algorithm level, by harnessing the graph sparsity, TorchGT introduces a Dual-interleaved Attention which is computation-efficient and accuracy-maintained. At runtime level, TorchGT scales training across workers with a communication-light Cluster-aware Graph Parallelism. At kernel level, an Elastic Computation Reformation further optimizes the computation by reducing memory access latency in a dynamic way. Extensive experiments demonstrate that TorchGT boosts training by up to 62.7x and supports graph sequence lengths of up to 1M.

<a>https://sc24.conference-program.com/presentation/?id=pap224&sess=sess396</a>