---
layout: page
title: >
  A paper titled "H2-Cache: A Novel Hierarchical Dual-Stage Cache for High-Performance Acceleration of Generative Diffusion Models" got accepted to IEEE Open Journal of the Computer Society (IF 8.2, JCR Q1 Rank 5.8%)!
image: 
  path: /assets/img/blog/jeremy-bishop@0,5x.jpg
description: >
  
sitemap: false
# link: https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11275637
---

Diffusion models have emerged as state-of-the-art in image generation, but their practical deployment is hindered by the significant computational cost of their iterative denoising process. While existing caching techniques can accelerate inference, they often create a challenging trade-off between speed and fidelity, suffering from quality degradation and high computational overhead. To address these limitations, we introduce H2-Cache, a novel hierarchical caching mechanism designed for modern generative diffusion model architectures. Our method is founded on the key insight that the denoising process can be functionally separated into a structure-defining stage and a detail-refining stage. H2-Cache leverages this by employing a dual-threshold system, using independent thresholds (τ_1, τ_2) to selectively cache each stage. To ensure the efficiency of our dual-check approach, we introduce pooled feature summarization (PFS), a lightweight technique for robust and fast similarity estimation. Extensive experiments demonstrate that H2-Cache achieves significant acceleration—up to 7.01x on COCO; 5.08x at 100 steps on CUTE80—while maintaining image quality nearly identical to the baseline, quantitatively and qualitatively outperforming existing caching methods. Our work presents a robust and practical solution that effectively resolves the speed-quality dilemma, significantly lowering the barrier for the real-world application of high-fidelity diffusion models.


[Learn more](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11275637)