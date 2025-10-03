---
layout: post
title:  "Instance Segmentation of Nematode Cysts in Microscopic Images of Soil Samples"
date:   2019-07-23
excerpt: ""
authors: <u><b>Long Chen</b></u>, Martin Strauch, Matthias Daub, Marcus Jansen, Hans-Georg Luigs and Dorit Merhof
published: International Conference of the IEEE Engineering in Medicine and Biology Society (EMBC) 2019
categories: "publication"
thumbnail: /assets/publications/thumbnail_embc2019.jpg
feature: /assets/publications/embc2019_p0.jpg
tag:
- Instance Segmentation
- Nematode
---

<br>
<img src="/assets/publications/embc2019_overview.png" style="width:70%">
<br>

**Abstract:** Nematodes are plant parasites that cause damage to crops. In order to quantify nematode infestation based on soil samples, we propose an instance segmentation method that will serve as the basis of automatic quantitative analysis. We consider light microscopic images of cluttered object collections as they occur in realistic soil samples. We introduce an algorithm, LMBI (Local Maximum of Boundary Intensity) to propose instance segmentation candidates. In a second step, a SVM classifier separates the nematode cysts among the candidates from soil particles. On a data set of soil sample images, the LMBI detector achieves near-optimal recall with a limited number of candidate segmentations, and the combined detector/classifier achieves recall and precision of ~0:7. The pipeline only requires simple dot annotations and moderately
sized training data, which enables quick annotating and training in laboratory applications.

[Paper](https://ieeexplore.ieee.org/document/8856567){: .btn}
[Code](https://github.com/looooongChen/LMBI){: .btn}
[Data](){: .btn}



