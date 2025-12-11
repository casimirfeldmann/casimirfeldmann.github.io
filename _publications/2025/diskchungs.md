---
title:          "DiskChunGS: Large-Scale 3D Gaussian SLAM Through Chunk-Based Memory Management"
date:           2025-11-28 00:01:00 +0800
selected:       true
# pub:            "SyntheticData4CV 2024 (Workshop at ECCV)"
# pub_pre:        "Submitted to IEEE Robotics and Automation Letters (RA-L)"
# pub_post:       'Under review.'
#pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
# pub_date:       "2025"

abstract: >-
  Recent advances in 3D Gaussian Splatting (3DGS) have demonstrated impressive results for novel view synthesis with real-time rendering capabilities. However, integrating 3DGS with SLAM systems faces a fundamental scalability limitation: methods are constrained by GPU memory capacity, restricting reconstruction to small-scale environments. We present DiskChunGS, a scalable 3DGS SLAM system that overcomes this bottleneck through an out-of-core approach that partitions scenes into spatial chunks and maintains only active regions in GPU memory while storing inactive areas on disk. Our architecture integrates seamlessly with existing SLAM frameworks for pose estimation and loop closure, enabling globally consistent reconstruction at scale. We validate DiskChunGS on indoor scenes (Replica, TUM-RGBD), urban driving scenarios (KITTI), and resource-constrained Nvidia Jetson platforms. Our method uniquely completes all 11 KITTI sequences without memory failures while achieving superior visual quality, demonstrating that algorithmic innovation can overcome the memory constraints that have limited previous 3DGS SLAM methods. 
cover:          /assets/images/covers/diskchungs.png
authors:
  - Casimir Feldmann
  - Maximum Wilder-Smith
  - Vaishakh Patil
  - Michael Oechsle
  - Michael Niemeyer
  - Keisuke Tateno
  - Marco Hutter
links:
  #Code: https://github.com/luost26/academic-homepage
  Webpage: https://rffr.leggedrobotics.com/works/diskchungs/
  Paper: https://www.arxiv.org/abs/2511.23030
---
