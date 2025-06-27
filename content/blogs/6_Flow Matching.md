---
title: "Flow Matching: The Theory Behind Stable Diffusion - 3."
date: 2025-06-25T10:02:00+00:00
slug: 
category: Flow Matching
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


Most of the posts start with a pic or a qoute, I'm going to start with a lame joke.

A gaussian noise and MINST dataset fell in love with each other. How did they meet?   
They used flow matching app.

## What is the post about?

Diffusion models and flow matching have improved image generation(they both can be wriiten under the same formulation). In this blog post I will write my learnings about flow matching from the ground up, which was used to develop SD3, open ai SORA, Meta's movie gen video, etc. The topis covered are:

1. Flow matching theory with self contained proofs.
2. Guidance.
2. Training a model on MINST dataset.

I think the MIT's course [Introduction to Flow Matching and Diffusion Models](https://diffusion.csail.mit.edu/) (thanks a lot!!) is much better than what I have written, I learned from it, please take a look at it, they have notes, codes and video lectures. This post is inspired from it.

## Introduction

We want to generate images belonging to $P_{data}$. How can we go about this? 

To read more please click the link below. Since writing math using plain html is time consuming, I use jupyter-book for wrtiing my blogs.
(To read comfortably please toggle the side bar)      

**[https://yogheswaran-a.github.io/blogs/02_Flow_Matching_I.html](https://yogheswaran-a.github.io/blogs/02_Flow_Matching_I.html)**


