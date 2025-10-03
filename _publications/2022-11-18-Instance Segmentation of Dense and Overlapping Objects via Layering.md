---
layout: post
title:  "Instance Segmentation of Dense and Overlapping Objects via Layering"
date:   2022-11-18
excerpt: ""
authors: <u><b>Long Chen</b></u>, Yuli Wu and Dorit Merhof
published: British Machine Vision Conference (BMVC)
categories: "publication"
thumbnail: /assets/publications/thumbnail_bmvc2022.png
feature: /assets/publications/bmvc2022_p0.png
tag:
- Instance Segmentation
- Pixel Embedding
---
<br>
<img src="/assets/publications/bmvc2022_overview.png" style="width:80%">
<br><br>
**Abstract:** Instance segmentation aims to delineate each individual object of interest in an image. State-of-the-art approaches achieve this goal by either partitioning semantic segmentations or refining coarse representations of detected objects. In this work, we propose a novel approach to solve the problem via object layering, i.e. by distributing crowded, even overlapping objects into different layers. By grouping spatially separated objects in the same layer, instances can be effortlessly isolated by extracting connected components in each layer. In comparison to previous methods, our approach is not affected by complex object shapes or object overlaps. With minimal post-processing, our method yields very competitive results on a diverse line of datasets: C. elegans (BBBC), Overlapping Cervical Cells (OCC) and cultured neuroblastoma cells (CCDB). The source code is publicly available.

[Paper](https://www.lfb.rwth-aachen.de/wp-content/plugins/bibtex/show_pdf.php?file=CHE22b.pdf){: .btn}



