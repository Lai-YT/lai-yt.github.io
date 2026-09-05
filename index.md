---
layout: page
title: About
hide_title: true
lang: en
ref: about
---

Hi there! I'm Lai-YT :smile:

I've been working on GPU architecture and compiler optimization, with a particular focus on how warp-level memory access patterns interact with the GPU memory hierarchy, especially the L1 cache. This work eventually became my [master thesis](#master-thesis), where I explored how a compiler can select memory layouts that better match different access patterns. Along the way, I became quite familiar with conventional SIMT execution and GPU performance analysis.

Now, I'm shifting my focus toward large language models (LLMs). Modern GPUs increasingly rely on specialized hardware[^specialized-hardware] and asynchronous execution mechanisms that play an important role in LLM computation. I'm interested in understanding these newer execution models and how they can be used to optimize LLM workloads. I'm also interested in the related hardware-software co-design.

[^specialized-hardware]: For example, tensor cores for high-throughput matrix operations and the Tensor Memory Accelerator (TMA) for asynchronous data movement.

## Interest

- Coffee :coffee:
  - Like acidity more than bitterness.
  - [Coffee Review (Chinese)](/zh/coffee-review.html)
- Books :books:
  - [Book Recommendations (Chinese)](/zh/book-recommendations.html)
- Table Tennis :ping_pong:
  - Blade: _Nittaku Acoustic_, F: _XIOM Vega Pro_ (Max), B: _Nittaku Fastarc C-1_

## Other

- <a id="master-thesis"></a>Master Thesis: _Improving Intra-Warp Cache Utilization on GPUs through Compiler-Guided Exploitation of Texture Hardware_
  - [Thesis](/assets/files/yi-ting-lai-master-thesis.pdf) (158 pages)
  - [Slides](/assets/files/yi-ting-lai-master-thesis-slides.pdf)
- [Resume](/assets/files/resume.pdf) :page_with_curl:

---
