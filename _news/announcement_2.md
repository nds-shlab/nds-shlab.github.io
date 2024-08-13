---
layout: post
title: Our paper "LongGen Efficiently Serving Long-context Large Language Models with Elastic Sequence Parallelism" was accepted by <b>SOSP 2024</b>.
date: 2024-06-29 16:11:00-0400 
inline: false
related_posts: false
---

The context window of large language models (LLMs) is rapidly increasing, leading to a huge variance in resource usage between different requests as well as between different phases of the same request. Restricted by static parallelism strategies, existing LLM serving systems cannot efficiently utilize the underlying resources to serve variable-length requests in different phases. To address this problem, we propose a new parallelism paradigm, elastic sequence parallelism (ESP), to elastically adapt to the variance across different requests and phases. Based on ESP, we design and build LongGen, an LLM serving system that (1) improves computation efficiency by elastically adjusting the degree of parallelism in real-time, (2) improves communication efficiency by reducing key-value cache migration overhead and overlapping partial decoding communication with computation, and (3) improves GPU memory efficiency by reducing key-value cache fragmentation across instances. Our evaluation under diverse real-world datasets shows that LongGen improves the throughput by up to 3.85× compared to chunked prefill and 5.81x compared to prefill-decoding disaggregation.

<a>https://arxiv.org/abs/2404.09526</a>