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

The human brain can keep memories for an entire life while constantly learning something new. This is particularly surprising when considering that the lifetime of synaptic mechanisms such as long-term potentiation much shorter than that and is reported to be maximally one year under special conditions [1]. Additionally, the process of forgetting stored memories while learning new tasks is a crucial problem in artificial neural networks. This project at the University of Edinburgh at Matthias Hennig's group at the institute for Computational Neuroscience explored the phenomenon of continuous learning in the brain and shows a possibility to attenuate the process of forgetting in artificial neural networks.

---

## Methods

We use hebbian learning in a Hopfield network at the sparse coding limit to store patterns and evaluate retrieval by using the dice-coefficient. In order to prevent the previously learned patterns to be forgotten, we identify the important weights of the network by calculating their respective Fisher information [2]. We then demonstrate that in the given network architecture, the weights with a high Fisher information correspond to the large weights of the network. Hence, keeping the large weights rather stable allows for a local and hence biologically plausible way to attenuate the forgetting in neural networks.

---

## Results

Using the above given approach, we are able to continuously store patterns in the Hopfield networks and thereby approach the theoretical limit for the capacity when using 'instant' learning.

---

## Discussion

Our approach thereby not only shows a possibility to attenuate forgetting in artificial neural networks, but also proposes a reason for the biological observation that strong synapses undergo a smaller relative change than smaller synapses [3,4].

---

## Paper

The paper is currently in the review process. The manuscript on the arXiv can be found [here](https://arxiv.org/abs/1807.05097)

---

## References
[1] Abraham WC, Logan B, Greenwood JM, Dragunow M (2002) Induction
and experience-dependent consolidation of stable long-term potentia- tion lasting months in the hippocampus. J Neurosci 22:9626–9634. Medline<br/>
[2] Kirkpatrick, J., Pascanu, R., Rabinowitz, N., Veness, J., Desjardins, G., Rusu, A. A., Milan, K., Quan, J., Ramalho, T., Grabska-Barwinska, A., Hassabis, D., Clopath, C., Kumaran, D., and Hadsell, R. (2017). Overcoming catastrophic forgetting in neural networks. PNAS, 114(13):3521– 3526.<br/>
[3] A. J. G. D. Holtmaat, J. T. Trachtenberg, L. Wilbrecht, G. M. Shepherd, X. Zhang, G. W. Kno, and K. Svoboda. Transient and persistent dendritic spines in the neocortex in vivo. Neuron, 45(2):279–91, jan 2005.<br/>
[4] Y. Loewenstein, U. Yanover, and S. Rumpel. Predicting the Dynamics of Network Connectivity in the Neocortex. Journal of Neuroscience, 35(36):12535–12544, 2015.
