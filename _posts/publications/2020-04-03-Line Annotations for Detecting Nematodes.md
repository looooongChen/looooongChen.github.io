---
layout: post
title:  "A CNN Framework Based on Line Annotations for Detecting Nematodes in Microscopic Images"
date:   2020-04-03
excerpt: ""
authors: <u><b>Long Chen</b></u>, Martin Strauch, Matthias Daub, Xiaochen Jiang, Marcus Jansen, Hans-Georg Luigs, Susanne Schultz-Kuhlmann, Stefan Kruessel and Dorit Merhof
published: IEEE International Symposium on Biomedical Imaging (ISBI) 2020
type: "publication"
thumbnail: /assets/publications/thumbnail_isbi2020.png
tag:
- Instacen Segmentation
- Nematode
- Weakly-Supervised
---

<br>
<img src="/assets/publications/overview_isbi2020.png" style="width:60%">
<br>

**Abstract:** Plant parasitic nematodes cause damage to crop plants on a global scale. Robust detection on image data is a prerequisite for monitoring such nematodes, as well as for many biological studies involving the nematode C. elegans, a common model organism. Here, we propose a framework for detecting worm-shaped objects in microscopic images that is based on convolutional neural networks (CNNs). We annotate nematodes
with curved lines along the body, which is more suitable for worm-shaped objects than bounding boxes. The trained model predicts worm skeletons and body endpoints. The endpoints serve to untangle the skeletons from which segmentation masks are reconstructed by estimating the body width at each location along the skeleton. With light-weight backbone networks, we achieve 75.85% precision, 73.02% recall on a potato cyst nematode data set and 84.20% precision, 85.63% recall on a public C. elegans data set.

[Paper](https://www.researchgate.net/publication/340826839_A_CNN_Framework_Based_on_Line_Annotations_for_Detecting_Nematodes_in_Microscopic_Images){: .btn}
[Code](https://github.com/looooongChen){: .btn}
[Data](https://bbbc.broadinstitute.org/BBBC010){: .btn}



