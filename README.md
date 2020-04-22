## SPADNet
SPADNet: Deep RGB-SPAD Sensor Fusion Assisted by Monocular Depth Estimation. 

Created by Zhanghao Sun, David Brian Lindell, [Olav Solgaard] and [Gordon Wetzstein] from Stanford University.

**We will make code and pre-trained models public soon.**

[Olav Solgaard]: https://solgaardlab.stanford.edu/#research
[Gordon Wetzstein]: http://www.computationalimaging.org

## Introduction
This repository is code release for our Optics Express paper "SPADNet: Deep RGB-SPAD Sensor Fusion Assisted by Monocular Depth Estimation". 

Construction of 3D scenes is essential for many applications. An emerging technique, single-photon-avalanche-diode (SPAD)-based 3D imaging, is attracting increasing attention. In this work, we aim at depth reconstruction from noisy SPAD measurements. Previous algorithms generally suffer from insufficient accuracy under low photon-flux conditions. 

In this paper, we introduce SPADnet—a neural network architecture for robust RGB-SPAD sensor fusion. We introduce monocular depth estimation into the network to assist the fusion process and also optimize the training procedure with a better objective function and log-scale rebinning. The proposed model achieves state-of-the-art performance in SPAD denoising. It is also more memory efficient and significantly faster than previous RGB-SPAD fusion approaches. This work can lead to the application of SPAD-based 3D reconstruction in broader contexts, such as 3D imaging with longer range and strong ambient light or 3D imaging on mobile devices. Also, the general insight that monocular depth estimator can facilitate fusion between 3D and 2D data modality may be helpful in other 3D sensing related scenarios.

For more details of our architecture, please refer to our paper or project website.
