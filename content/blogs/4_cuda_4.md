---
title: "Flash Attention - II"
date: 2025-06-01T10:02:00+00:00
slug: 
category: Cuda,Cuda C++, C++
summary:
description:
cover:
  image: 
  alt:
  caption:
  relative: true
showtoc: true
draft: false
---
# Flash Attention - II
This chapter assumes that you know about attention mechanism. If not please see this video, which provides a lot of info about how to model, train a GPT-2 from ground up, [Andrej Karpathy video](https://www.youtube.com/watch?v=l8pRSuU81PU).
This chapter compromises of:
1) Attention Pytorch Code.
2) Attention From Scratch Using Cuda.


## The Vanilla Self-Attention: Math Refresher

Before we look at the code, let's quickly recap the math for a single attention head.

Given Query ($Q$), Key ($K$), and Value ($V$) matrices for a sequence of length $T$ and feature dimension $d_k$ (per head):
 


To read more click the link below. Since writing math using plain html is time consuming, I use jupyter-book for wrtiing my blogs.
(To read comfortably please toggle the side  bar)      

**[https://yogheswaran-a.github.io/cuda-notes/04-flash-attention-II.html](https://yogheswaran-a.github.io/blogs/01-weiner-process.html)**

More Cuda blogs:   
**[https://yogheswaran-a.github.io/cuda-notes/00-landing-page.html](https://yogheswaran-a.github.io/cuda-notes/00-landing-page.html)**