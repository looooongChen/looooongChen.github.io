---
layout: post
title:  "Instance Segmentation of Biomedical Images with an Object-aware Embedding Learned with Local Constraints"
date:   2019-10-13
excerpt: ""
authors: <u><b>Long Chen</b></u>, Martin Strauch and Dorit Merhof
published: International Conference on Medical Image Computing and Computer Assisted Intervention (MICCAI) 2019
categories: "publication"
thumbnail: /assets/publications/thumbnail_miccai2019.png
tag:
- Instance Segmentation
- Pixel Embedding
---

<br>
<img src="/assets/publications/overview_miccai2019.png" style="width:80%">
<br>

**Abstract:** Automatic instance segmentation is a problem that occurs in many biomedical applications. State-of-the-art approaches either perform semantic segmentation or rene object bounding boxes obtained
from detection methods. Both suer from crowded objects to varying degrees, merging adjacent objects or suppressing a valid object. In this work, we assign an embedding vector to each pixel through a deep neural
network. The network is trained to output embedding vectors of similar directions for pixels from the same object, while adjacent objects are orthogonal in the embedding space, which eectively avoids the fusion of
objects in a crowd. Our method yields state-of-the-art results even with a light-weighted backbone network on a cell segmentation (BBBC006 + DSB2018) and a leaf segmentation data set (CVPPP2017).

[Paper](https://www.researchgate.net/publication/340826279_Instance_Segmentation_of_Biomedical_Images_with_an_Object-aware_Embedding_Learned_with_Local_Constraints){: .btn}
[Code1](https://github.com/looooongChen/instance_segmentation_with_pixel_embeddings){: .btn}
[Code2](https://github.com/looooongChen/instSeg){: .btn}
[Data1](https://bbbc.broadinstitute.org/BBBC006){: .btn}
[Data2](https://competitions.codalab.org/competitions/18405){: .btn}



