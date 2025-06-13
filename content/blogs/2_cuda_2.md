---
title: "Cuda C++: Instruction Dispatch and Memory"
date: 2025-06-02T10:02:00+00:00
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
# Instruction Dispatch and Memory

This chapter comprises of: 

1) Wrap And Wrap Scheduler.
2) Types of Memories.
3) Why coalesing matters?
4) Matirx Multiplication Using Shared Memory.
5) More About Shared Memory.

## Wrap And Wrap Scheduler
Hope you remember what Wrap scheduler is, it was defined in the previous chapter. Its defined here again,
1) **Wrap Scheduler**: Wrap scheduler simply put is the one which issues the instructions to the SM. It tells which instructions needs to be executed and when. *Warp schedulers are dual issue capable*. This means that the wrap scheduler can issue two instructions to the same SM in the same clock, if the two instructions do not depend on each other.

To read more click the link below. Since writing math using plain html is time consuming, I use jupyter-book for wrtiing my blogs.
(To read comfortably please toggle the side  bar)      

**[https://yogheswaran-a.github.io/cuda-notes/02-instruction-dispatch-and-memory.html](https://yogheswaran-a.github.io/cuda-notes/02-instruction-dispatch-and-memory.html)** 

More Cuda blogs:   
**[https://yogheswaran-a.github.io/cuda-notes/00-landing-page.html](https://yogheswaran-a.github.io/cuda-notes/00-landing-page.html)**