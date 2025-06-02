---
title: "Diffusion models, Score based models, Rectiflow, Heirrachical VAEs: Basics and a unified View"
date: 2025-02-6T10:02:00+00:00
slug: dmsbmrhvsbaau
category: Diffusion, SDEs, Rectiflow, VAEs
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

## Introduction

This blog contains the basics, derivations and idea behind diffusion models, score based models, Heirrachical VAEs and Rectiflow. I have also explained how these formulations relate to one another and comes under the same umberala. I will start with each formulation independently and at the end we will see how all of these are a variant of each other. 

### Contents
- Diffuions Models

## Diffuions Models

To understand this section knowldge of Stochastic differential equation is required. I have provided only a brief intro and some results. You can read more about SDE in these blog posts: [SDE](https://ludwigwinkler.github.io/blog/SDE/), [Ito's lemma](https://ludwigwinkler.github.io/blog/ItosLemma/), [OU process](https://ludwigwinkler.github.io/blog/SolvingSDEs/), [Forward And Backward](https://ludwigwinkler.github.io/blog/Kramers/). The author also has other related SDE posts if you want to know more.

### Brief intro about SDEs