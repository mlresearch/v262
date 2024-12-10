---
title: 'Less is Enough: Adapting Pre-trained Vision Transformers for Audio-Visual
  Speaker Verification'
section: Applications
abstract: Speaker Verification has achieved significant improvement in performance
  using sophisticated deep learning architectures, specialized for speech signals
  as well as robust loss functions. Recently, the fusion of faces and voices received
  a lot of attention as they offer complementary relationship with each other, which
  has the potential to outperform systems with only speech signals. Inspired by the
  massive success of Vision Transformers (ViTs) in computer vision, ViTs have also
  been explored for multimodal learning. In this work, we have investigated the potential
  of ViTs, pre-trained on visual data, for audio-visual speaker verification. To cope
  with the challenges of large-scale training, we introduce the Latent Audio-Visual
  Vision Transformer (LAVViT) adapters, where we exploit the existing pre-trained
  models on visual data by training only the parameters of LAVViT adapters, without
  fine-tuning the original parameters of the pre-trained models. The LAVViT adapters
  are injected into every layer of the ViT architecture to effectively fuse the audio
  and visual modalities using a small set of latent tokens, thereby avoiding the quadratic
  computational cost of cross-attention across the modalities. The proposed approach
  has been evaluated on the Voxceleb1 dataset and shows promising performance using
  only a few trainable parameters.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: praveen-rajasekhar24a
month: 0
tex_title: 'Less is Enough: Adapting Pre-trained Vision Transformers for Audio-Visual
  Speaker Verification'
firstpage: 554
lastpage: 563
page: 554-563
order: 554
cycles: false
bibtex_author: Praveen Rajasekhar, Gnana and Alam, Jahangir
author:
- given: Gnana
  family: Praveen Rajasekhar
- given: Jahangir
  family: Alam
date: 2024-12-10
address:
container-title: Proceedings of The 4th NeurIPS Efficient Natural Language and Speech
  Processing Workshop
volume: '262'
genre: inproceedings
issued:
  date-parts:
  - 2024
  - 12
  - 10
pdf: https://raw.githubusercontent.com/mlresearch/v262/main/assets/praveen-rajasekhar24a/praveen-rajasekhar24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
