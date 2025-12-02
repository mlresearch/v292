---
title: 'Shaping Fine-Tuning of Geospatial Foundation Models: Effects of Label Availability
  and Temporal Resolution'
abstract: 'Fine-tuning foundation models is a key step in adapting them to a particular
  task. In the case of Geospatial Foundation Models (GFMs), fine-tuning can be particularly
  challenging given data scarcity both in terms of the amount of labeled data and,
  in the case of Satellite Image Time Series (SITS), temporal context. Under these
  circumstances, the optimal GFM fine-tuning strategy across different labeled data
  regimes remains poorly understood. In this paper, we thoroughly assess and study
  the performances of two different GFMs given several combinations of two data scarcity
  factors: the number of labeled samples and the sequence length. Specifically, we
  analyze the performances on a crop classification task, particularly, semantic segmentation
  of the Sentinel-2 images contained in the PASTIS-HD dataset. We compare GFMs to
  U-TAE, as a fully supervised baseline, across varying amounts of labeled data (1%,
  10%, 50%, 100%) and temporal input lengths (1, 6, 15, 25 and 35). Among these explorations,
  we find that using a smaller learning rate for the pre-trained encoders improves
  performance in moderate and high data regimes (50%-100%). In contrast, full fine-tuning
  outperforms partial fine-tuning in very low-label settings (1%-10%). This behavior
  suggests a nuanced trade-off between feature reuse and adaptation that defies the
  intuition of standard transfer learning. The code is available \href{https://github.com/GioCastiglioni/ShapingFT}{here}.'
openreview: CLTEaA2mtC
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: castiglioni25a
month: 0
tex_title: 'Shaping Fine-Tuning of Geospatial Foundation Models: Effects of Label
  Availability and Temporal Resolution'
firstpage: 81
lastpage: 96
page: 81-96
order: 81
cycles: false
bibtex_author: Castiglioni, Giovanni and Isla Fern{\'a}ndez, Nicol{\'a}s Gonzalo and
  {Buc Calderon}, Cristian and {Castillo Navarro}, Javiera and Lef{\`e}vre, S{\'e}bastien
  and Barriere, Valentin
author:
- given: Giovanni
  family: Castiglioni
- given: Nicolás Gonzalo
  family: Isla Fernández
- given: Cristian
  family: Buc Calderon
- given: Javiera
  family: Castillo Navarro
- given: Sébastien
  family: Lefèvre
- given: Valentin
  family: Barriere
date: 2025-12-02
address:
container-title: 'Proceedings of The TerraBytes {ICML} Workshop: Towards global datasets
  and models for Earth Observation'
volume: '292'
genre: inproceedings
issued:
  date-parts:
  - 2025
  - 12
  - 2
pdf: https://raw.githubusercontent.com/mlresearch/v292/main/assets/castiglioni25a/castiglioni25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
