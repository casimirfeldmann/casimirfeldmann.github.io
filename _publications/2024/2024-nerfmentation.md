---
title:          "NeRFmentation: Improving Monocular Depth Estimation with NeRF-based Data Augmentation"
date:           2024-08-30 00:01:00 +0800
selected:       true
pub:            "SyntheticData4CV 2024 (Workshop at ECCV)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
#pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2024"

abstract: >-
  The capabilities of monocular depth estimation (MDE) models are limited by the availability of sufficient and diverse datasets. In the case of MDE models for autonomous driving, this issue is exacerbated by the linearity of the captured data trajectories. We propose a NeRF-based data augmentation pipeline to introduce synthetic data with more diverse viewing directions into training datasets and demonstrate the benefits of our approach to model performance and robustness. Our data augmentation pipeline, which we call NeRFmentation, trains NeRFs on each scene in a dataset, filters out subpar NeRFs based on relevant metrics, and uses them to generate synthetic RGB-D images captured from new viewing directions. In this work, we apply our technique in conjunction with three state-of-the-art MDE architectures on the popular autonomous driving dataset, KITTI, augmenting its training set of the Eigen split. We evaluate the resulting performance gain on the original test set, a separate popular driving dataset, and our own synthetic test set. 
cover:          /assets/images/covers/nerfmentation.png
authors:
  - Casimir Feldmann*
  - Niall Siegenheim*
  - Nikolas Hars
  - Lovro Rabuzin
  - Mert Ertugrul
  - Luca Wolfart
  - Marc Pollefeys
  - Zuria Bauer
  - Martin R. Oswald
links:
  #Code: https://github.com/luost26/academic-homepage
  Webpage: TODO
  Paper: https://arxiv.org/abs/2401.03771
---
