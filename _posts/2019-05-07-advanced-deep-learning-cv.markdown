---
title: "Continual Learning on Point Clouds"
layout: post
date: 2018-02-07 11:00
tag: TU Munich
image: https://michaeldeistler.github.io/assets/images/pointcloud.jpg
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "Continual Learning on Point Clouds"
category: project
author: michaeldeistler
externalLink: false
---

## Introduction
The detection of pedestrians, vehicles or fixed objects is a major task in autonomous driving. Data from a LiDAR can provide valuable information about the distance of these objects. In this work, Lucas Stoffl and I wanted to address the topic of object detection from point cloud data using Deep Learning. In particular, we wanted to investigate the potential of continual learning. Traditional CNNs face problems in real world scenarios and can hence benefit from continual learning in two ways. Firstly, continual learning allows for a steadily increasing dataset. Secondly, it can help the network in adapting to new circumstances or environments. However, in order to realize these possibilities, the newly collected data has to be integrated smoothly into the network without overwriting previously learned tasks. These tasks are tackled here using the KITTI dataset for autonomous driving.

---

## Results
We tested several ways of alleviating catastrophic forgetting in neural networks and allowing continual learning. While several approaches (Fisher information based regularization, L2 and dropout) seemed promising in a simple network classifying the MNIST digits, it did not work in the more complex Frustum PointNet. We could image several reasons for this behaviour, including a very sensitive dependence on the exact hyperparameter values and an instable behaviour of the optimizer when optimizing the Fisher information based regularization term.

---

## Supervision
Thanks a lot to [Prof Dr Matthias Nießner](https://niessnerlab.org) for giving us the chance to work on this project and for providing valuable feedback!
