---
layout: post
title:  "Flash Attention in C"
date:   2024-04-01 00:00:00 +00:00
image: /images/deeppoly.jpg
categories: projects
website: "https://github.com/kilianhae/FlashAttention.C"
authors: "Kilian Haefeli"
---
A cuda C implementation of [Flash Attenton](https://arxiv.org/abs/2205.14135) without using any libraries such as cublas or cutlass. In ~300 lines of code this kernel is faster and more memory efficient than the standard PyTorch attention module.