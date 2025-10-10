---
layout: page
title: >
  Prof. Yun's paper "DASK-Net: A Lightweight Dual Attention Selective Kernel Network for Efficient Dense Prediction in Remote Sensing Imagery" got accepted to IEEE Transactions on Geoscience and Remote Sensing (IF 8.6, JCR Q1 Rank 6.7%)!
image: 
  path: /assets/img/blog/jeremy-bishop@0,5x.jpg
description: >
  
sitemap: false
# link: https://ieeexplore.ieee.org/document/10981800
---

The precise and efficient extraction of buildings and road networks from aerial imagery is crucial for remote sensing applications, such as map building, urban development, and autonomous driving guidance systems. However, accurately extracting buildings and roads from remote sensing imagery is challenging due to varying resolutions, object scale variation, and diverse appearances of buildings and roads. While sophisticated models achieve high accuracy, their computational demands limit practical use on resource-constrained devices. Conversely, mainstream lightweight models often fail to generate high-quality segmentation maps for remote sensing data. To address these challenges, we introduce a dual-attention selective kernel network (DASK-Net), a novel lightweight architecture for efficient pixel-wise dense prediction. DASK-Net’s core features a dual-attention selective kernel (DASK) module that integrates multiscale feature extraction with adaptive receptive fields and dual-attention mechanisms. This design captures diverse scales and orientations of features while focusing on salient input aspects. We conducted experiments on the Massachusetts roads, DeepGlobe, and WHU building datasets, comparing DASK-Net with numerous methods. The results demonstrate that DASK-Net outperforms these networks while significantly reducing computational complexity. With only 0.48M parameters, DASK-Net achieves an 89.54% intersection over union (IoU) and a 94.48% F1 score on the WHU building dataset, setting new performance standards for lightweight methods.

[Learn more](https://ieeexplore.ieee.org/document/10981800)