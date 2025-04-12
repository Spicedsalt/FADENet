# FADE-Net: Decoupled Foreground-Background Representation with Edge Reconstruction for Precise Polyp Segmentation

## Abstract
In colonoscopy examinations, accurate polyp identification is vital for early cancer diagnosis. However, polyp morphological diversity, uneven illumination, and noise create interference between foreground and background features, while edge regions often appear blurred and fragmented. To address these challenges, we propose Foreground-Adaptive Decoupling and Edge Network (FADE-Net) to improve segmentation accuracy and robustness.
Our approach features three key components: First, the Dynamic Subspace Decoupling Module (DSDM) separates features into foreground and background subspaces, maximizing their differences to reduce mutual interference. Second, the Adaptive Foreground Enhancement Module (AFEM) leverages contextual consistency and dynamic weight allocation to strengthen attention to critical areas, ensuring robust foreground representation. Finally, the Multi-Frequency Edge Reconstruction Module (MFERM) establishes feedback paths that combine high-frequency features for edge refinement with low-frequency features for semantic consistency, recovering boundary information lost during downsampling.
By effectively decoupling interfering information and enhancing edge detail capture, FADE-Net demonstrates improved performance on polyp segmentation tasks. Extensive experiments on five public datasets show that FADE-Net outperforms thirteen competing methods in terms of both effectiveness and generalization ability.

![Architecture](./Figure1.png)
## Overview
This repository contains the official implementation of FADE-Net, including:
- Model
- Pre-trained models

Code Coming soon...
