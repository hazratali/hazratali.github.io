---
layout: page
permalink: /research/
title: Research
description: Selected Research Highlights
nav: true
nav_order: 3
---

<div style="text-align: center;">
  <img src="https://hazratali.github.io/assets/img/research.svg" alt="Research Highlights" style="display: block; margin: auto; width: 700px; height: auto;">
</div>

# Generative AI in Healthcare
## LLMs in Medical Imaging
There is a temptation to use generative models to synthesize realistic-looking medical image data, while on the other hand, the ability to identify synthetic image data in a pool of data is also significantly important. In this study, we explore the potential of the Gemini (gemini-1.0-pro-visionlatest) and GPT-4V (gpt-4-vision-preview) models for medical image analysis using two modalities of medical image data. Utilizing synthetic and real imaging data, both Gemini AI and GPT-4V are first used to classify real versus synthetic images, followed by an interpretation and analysis of the input images. In this specific experiment, Gemini was able to perform slightly better than the GPT-4V on the classification task. In contrast, responses associated with GPT-4V were mostly generic in nature. Our early investigation presented in this work provides insights into the potential of MLLMs to assist with the classification and interpretation of retinal fundoscopy and lung X-ray images. We also identify key limitations associated with the early investigation study on MLLMs for specialized tasks in medical image analysis.

# Generative Adversarial Networks for Medical Imaging 
## Medical Image Super-Resolution using GANs
For medical image analysis, there is always an immense need for rich details in an image. In medical imaging, acquiring high-resolution images is challenging and costly as it requires sophisticated and expensive instruments, trained human resources, and often causes operation delays. Deep learning based super resolution techniques can help us to extract rich details from a low-resolution image acquired using the existing devices. We propose a new Generative Adversarial Network (GAN) based architecture for medical images, which maps low-resolution medical images to high-resolution images. The proposed architecture is divided into three steps. In the first step, we use a multi-path architecture to extract shallow features on multiple scales instead of single scale. In the second step, we use a ResNet34 architecture to extract deep features and upscale the features map by a factor of two. In the third step, we extract features of the upscaled version of the image using a residual connection-based mini-CNN and again upscale the feature map by a factor of two. The progressive upscaling overcomes the limitation for previous methods in generating true colors. Finally, we use a reconstruction convolutional layer to map back the upscaled features to a high-resolution image. Our addition of an extra loss term helps in overcoming large errors, thus, generating more realistic and smooth images. We evaluate the proposed architecture on four different medical image modalities: (1) the DRIVE and STARE datasets of retinal fundoscopy images, (2) the BraTS dataset of brain MRI, (3) the ISIC skin cancer dataset of dermoscopy images, and (4) the CAMUS dataset of cardiac ultrasound images. The proposed architecture achieves superior accuracy compared to other state-of-the-art super-resolution architectures.
Read about this work in Nature Scientific Reports

## 3D CycleGAN model for ultrasound image sequences of intra-muscular skeletal muscle contractions
Advances in sports medicine, rehabilitation applications and diagnostics of neuromuscular disorders are based on the analysis of skeletal muscle contractions. Medical imaging techniques have transformed the study of muscle contractions by allowing to learn the complex patterns of muscle activation. We use deep learning (3D cycleGAN) to model the authentic intra-muscular skeletal muscle contraction pattern using domain-to-domain translation between in silico (simulated) and in vivo (experimental) image sequences of skeletal muscle contraction dynamics. Our results show that there are large differences between the spatial features of in silico and in vivo data, and that a model could be trained to generate authentic spatio-temporal features similar to those obtained from in vivo experimental data.
Read about this work in Biomedical Engineering Online