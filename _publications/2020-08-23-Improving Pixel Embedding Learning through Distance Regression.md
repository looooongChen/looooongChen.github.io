---
layout: post
title:  "Improving Pixel Embedding Learning through Intermediate Distance Regression Supervision"
date:   2020-08-23
excerpt: ""
authors: Yuli Wu, <u><b>Long Chen</b></u> and Dorit Merhof
published: ECCV 2020 Workshop on Computer Vision Problems in Plant Phenotyping (CVPPP)
categories: "publication"
thumbnail: /assets/publications/thumbnail_eccv2020.png
tag:
- Instance Segmentation
- Pixel Embedding
- Distance Regression
---

<br>
<img src="/assets/publications/overview_eccv2020.png" style="width:80%">
<br>

**Abstract:** As a proposal-free approach, instance segmentation through pixel embedding learning and clustering is gaining more emphasis. Compared with bounding box renement approaches, such as Mask R-CNN,
it has potential advantages in handling complex shapes and dense objects. In this work, we propose a simple, yet highly effective, architecture for object-aware embedding learning. A distance regression module is
incorporated into our architecture to generate seeds for fast clustering. At the same time, we show that the features learned by the distance regression module are able to promote the accuracy of learned object-
aware embeddings signicantly. By simply concatenating features of the distance regression module to the images as inputs of the embedding module, the mSBD scores on the CVPPP Leaf Segmentation Challenge can be further improved by more than 8% compared to the identical setup without concatenation, yielding the best overall result amongst the leaderboard at CodaLab.

[Paper](https://www.researchgate.net/publication/342944438_Improving_Pixel_Embedding_Learning_through_Intermediate_Distance_Regression_Supervision_for_Instance_Segmentation){: .btn}
[Code](https://github.com/looooongChen/instSeg){: .btn}
[Data](https://competitions.codalab.org/competitions/18405){: .btn}



