---
title: "Local learning rules to attenuate forgetting in neural networks"
layout: post
date: 2018-04-07 11:00
tag: University of Edinburgh
image: https://michaeldeistler.github.io/assets/images/edinburgh_old_c.jpg
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "The human brain can keep memories for an entire life while constantly learning something new. This project at the University of Edinburgh at Matthias Hennig's group at the institute for Computational Neuroscience explored this phenomenon and shows a possibility to attenuate the forgetting process in artificial neural networks."
category: project
author: michaeldeistler
externalLink: false
---

## Introduction

The human brain can keep memories for an entire life while constantly learning something new. This project at the University of Edinburgh at Matthias Hennig's group at the institute for Computational Neuroscience explored this phenomenon and shows a possibility to attenuate the forgetting process in artificial neural networks.

---

## What were the results?

We found that in the network that we used, namely Hopfield networks, it can be derived that the most important weights (i.e. the weights with the highest Fisher Information) are those the are the largest. By keeping those weights rather stiff and the other weights rather sloppy, our networks can perform local learning and strongly alleviate forgetting of previously stored patterns.
