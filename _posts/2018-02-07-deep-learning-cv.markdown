---
title: "Deep Learning for Nerve Fibre Segmentation from Ultrasound Images"
layout: post
date: 2018-02-07 11:00
tag: TU Munich
image: https://michaeldeistler.github.io/assets/images/tum.jpg
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "Deep Learning Project"
category: project
author: michaeldeistler
externalLink: false
---

## Introduction
In order to reach the goal of relieving patients from surgical pain, correct identification of nerve tissue is essential for successful placement of an anaesthetic catheter. This project  carried out in the realm of the course 'Deep Learning for Computer Vision' targeted this issue by segmenting the nerve fibres using the so-called U-net architecture.

---

## Results
We found that a pretrained SegNet cannot compete on this task with a U-Net-inspired architecture that is designed for medical image segmentation. Further, it was feasible to train the U-Net from scratch, without using pre-trained weights. An added binary classification significantly increased the accuracy and sensitivity of our prediction. Integrating a GAN by training the decoder as generator with help of an external discriminator seemed to stabilize training. Since the discriminator could help the decoder to generalize underlying anatomical information that is contained in the masks, we argue that applying this method is plausible in medical image segmentation.
