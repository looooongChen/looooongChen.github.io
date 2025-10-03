---
layout: post
title:  "Semi-supervised Instance Segmentation with a Learned Shape Prior"
date:   2020-10-04
excerpt: ""
authors: <u><b>Long Chen</b></u>, Weiwen Zhang, Yuli Wu, Martin Strauch and Dorit Merhof
published: MICCAI 2020 Workshop on Medical Image Learning with Less Labels and Imperfect Data (MIL3ID)
categories: "publication"
thumbnail: /assets/publications/thumbnail_miccai2020.png
feature: /assets/publications/miccai2020_p0.png
tag:
- Semi-Supervised
- Instance Segmentation
- Shape Prior
---
<br>
<img src="/assets/publications/miccai2020_overview.png" style="width:80%">
<br><br>
**Abstract:** To date, most instance segmentation approaches are based on supervised learning that requires a considerable amount of annotated object contours as training ground truth. Here, we propose a framework that searches for the target object based on a shape prior. The shape prior model is learned with a variational autoencoder that requires only a very limited amount of training data: In our experiments, a few dozens of object shape patches from the target dataset, as well as purely synthetic shapes, were suffcient to achieve results en par with supervised methods with full access to training data on two out of three cell segmentation datasets. Our method with a synthetic shape prior was superior to pre-trained supervised models with access to limited domain-specic training data on all three datasets. Since the learning of prior models requires shape patches, whether real or synthetic data, we call this framework semi-supervised learning. 

[Paper](https://www.springerprofessional.de/en/semi-supervised-instance-segmentation-with-a-learned-shape-prior/18445584){: .btn}
[Code](https://github.com/looooongChen/shape_prior_seg){: .btn}
[Data](https://github.com/looooongChen/shape_prior_seg){: .btn}



