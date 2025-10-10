---
layout: page
title: >
  Prof. Yun's paper "DeCo-MeSC: Deep Compression-Based Memory-Constrained Split Computing Framework for Cooperative Inference of Neural Network" got accepted to IEEE Transactions on Vehicular Technology (IF 6.1, JCR Q1 Rank 12.2%)!
image: 
  path: /assets/img/blog/jeremy-bishop@0,5x.jpg
description: >
  
sitemap: false
# link: https://ieeexplore.ieee.org/document/10946233
---

Split computing (SC) of a deep neural network (DNN) across end nodes is a key enabling technology to realize energy-efficient and low-latency cooperative inference in wireless networks and Internet-of-Things (IoT). In this paper, we propose a novel SC framework based on the concept of deep compression (DC) of DNN considering the strictly limited memory footprint of a mobile device, namely, DeCo-MeSC. In our proposed DeCo-MeSC framework, an initial part of a target DNN (up to so-called the split layer) for the mobile device is compressed with the DC technique to satisfy the memory constraint, while the remaining part of the target DNN (after the split layer) for a cloud server is uncompressed, yet fine-tuned to compensate for the performance loss due to the compression of the initial part. Furthermore, the jointly optimal pair of the split layer and data rate is determined efficiently to maximize the end-to-end inference accuracy under both the end-to-end inference latency and memory constraints. Extensive experimental results demonstrate that the proposed scheme performs markedly better than the existing schemes.

[Learn more](https://ieeexplore.ieee.org/document/10946233)