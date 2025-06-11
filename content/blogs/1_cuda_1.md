---
title: "Getting Started: Cuda C++"
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
# Getting Started: Cuda C++

This chapter comprises of: 

1) GPU Intro. 
2) Transfer Of Data From CPU to GPU.
3) GPU Kernels.
4) Streaming Multiprocessor and GPU features. 
5) What are Threads, Blocks and Grids?
6) Writing our first program.
7) Cuda Error Checking.
8) Putting it all together: Vector Addition.

## GPU Intro

When a C++ program complied, the program is converted into machine code which can be executed on the CPU. When a program is written for CPU the machine code is excecuted sequentially inside a core. If there are multiple cores present then each core can be used to perform the desired operation parallely(using OpenMp in C++) but the instructions inside each core will be exceuted sequentially.  


To read more click the link below. Since writing math using plain html is time consuming, I use jupyter-book for wrtiing my blogs.
(To read comfortably please toggle the side  bar)      

**[https://yogheswaran-a.github.io/cuda-notes/01-getting-started.html](https://yogheswaran-a.github.io/blogs/01-weiner-process.html)**

More Cuda blogs:   
**[https://yogheswaran-a.github.io/cuda-notes/00-landing-page.html](https://yogheswaran-a.github.io/cuda-notes/00-landing-page.html)**