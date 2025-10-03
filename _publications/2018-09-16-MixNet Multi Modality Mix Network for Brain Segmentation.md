---
layout: post
title:  "MixNet Multi-modality Mix Network for Brain Segmentation"
date:   2018-09-16
excerpt: ""
authors: <u><b>Long Chen</b></u> and Dorit Merhof
published: MICCAI 2018 Brainlesion Workshop (BrainLes)
categories: "publication"
thumbnail: /assets/publications/thumbnail_miccai2018.png
feature: /assets/publications/miccai2018_overview.png
tag:
- Brain Segmentation
- Multi-Modality
---

<br>
<img src="/assets/publications/miccai2018_overview.png" style="width:80%">
<br>

**Abstract:** Automated brain structure segmentation is important to many clinical quantitative analysis and diagnoses. In this work, we introduce MixNet, a 2D semantic-wise deep convolutional neural network
to segment brain structure in multi-modality MRI images. The network is composed of our modied deep residual learning units. In the unit, we replace the traditional convolution layer with the dilated convolutional
layer, which avoids the use of pooling layers and deconvolutional layers, reducing the number of network parameters. Final predictions are made by aggregating information from multiple scales and modalities.
A pyramid pooling module is used to capture spatial information of the anatomical structures at the output end. In addition, we test three architectures (MixNetv1, MixNetv2 and MixNetv3) which fuse the modalities differently to see the eect on the results. Our network achieves the state-of-the-art performance. MixNetv2 was submitted to the MRBrainS challenge at MICCAI 2018 and won the 3rd place in the 3-label task. On
the MRBrainS2018 dataset, which includes subjects with a variety of pathologies, the overall DSC (Dice Coeffcient) of 84.7% (gray matter), 87.3% (white matter) and 83.4% (cerebrospinal fluid) were obtained with only 7 subjects as training data.

[Paper](https://www.researchgate.net/publication/340826683_MixNet_Multi-modality_Mix_Network_for_Brain_Segmentation){: .btn}
[Code](https://github.com/looooongChen/MRBrainS-Brain-Segmentation){: .btn}
[Data](https://mrbrains18.isi.uu.nl/){: .btn}



