---
layout: page
permalink: /research/
title: Research
description: Selected Research Highlights
nav: true
nav_order: 3
---

![Research Highlights](https://hazratali.github.io/assets/img/research.jpeg)

<div style="text-align: center;">
  <img src="https://hazratali.github.io/assets/img/research.jpeg" alt="Research Highlights" style="display: block; margin: auto;">
</div>

# Generative Adversarial Networks for Medical Imaging 
## Medical Image Super-Resolution using GANs
For medical image analysis, there is always an immense need for rich details in an image. In medical imaging, acquiring high-resolution images is challenging and costly as it requires sophisticated and expensive instruments, trained human resources, and often causes operation delays. Deep learning based super resolution techniques can help us to extract rich details from a low-resolution image acquired using the existing devices. We propose a new Generative Adversarial Network (GAN) based architecture for medical images, which maps low-resolution medical images to high-resolution images. The proposed architecture is divided into three steps. In the first step, we use a multi-path architecture to extract shallow features on multiple scales instead of single scale. In the second step, we use a ResNet34 architecture to extract deep features and upscale the features map by a factor of two. In the third step, we extract features of the upscaled version of the image using a residual connection-based mini-CNN and again upscale the feature map by a factor of two. The progressive upscaling overcomes the limitation for previous methods in generating true colors. Finally, we use a reconstruction convolutional layer to map back the upscaled features to a high-resolution image. Our addition of an extra loss term helps in overcoming large errors, thus, generating more realistic and smooth images. We evaluate the proposed architecture on four different medical image modalities: (1) the DRIVE and STARE datasets of retinal fundoscopy images, (2) the BraTS dataset of brain MRI, (3) the ISIC skin cancer dataset of dermoscopy images, and (4) the CAMUS dataset of cardiac ultrasound images. The proposed architecture achieves superior accuracy compared to other state-of-the-art super-resolution architectures.
Read about this work in Nature Scientific Reports