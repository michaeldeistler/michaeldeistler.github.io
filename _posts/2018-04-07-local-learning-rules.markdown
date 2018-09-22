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

## Methods

We use hebbian learning in a Hopfield networks at the sparse coding limit to store patterns and evaluate retrieval by using the dice-coefficient. In order to prevent the previously learned patterns to be forgotten, we identify the important weights of the network by calculating their respective Fisher information. We then demonstrate that in the given network architecture, the weights with a high Fisher information correspond to the large weights of the network. Hence, keeping the large weights constant allows for a local and hence biologically plausible way to attenuate the forgetting in neural networks.

---

## Results

Using the above given approach, we are able to continuously store patterns in the Hopfield networks and thereby nearly approach the theoretical limit for the capacity when using 'instant' learning.

---

## Discussion

Our approach thereby not only shows a possibility to attenuate forgetting in artificial neural networks, but also proposes a reason for the biological observation that strong synapses undergo a smaller relative change than smaller synapses
