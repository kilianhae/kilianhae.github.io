---
layout: post
title:  "Flash Attention in C CUDA"
date:   2024-04-01 00:00:00 +00:00
image: /images/light.jpeg
categories: projects
website: "https://github.com/kilianhae/FlashAttention.C"
authors: "Kilian Haefeli"
---
[Flash Attenton](https://arxiv.org/abs/2205.14135) in ~300 lines of pure Cuda C, outperforming native PyTorch Attention.
Manually implemented and profiled methods such as SMEM tiling, SMEM padding for reduced bank conflicts, 2D Blocktiling and  vectorized memory access.
