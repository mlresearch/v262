---
title: Is 3D Convolution with 5D Tensors Really Necessary for Video Analysis?
section: Model Design \& Architecture
abstract: In this paper, we present a comprehensive study and propose several novel
  techniques for implementing 3D convolutional blocks using 2D and/or 1D convolutions
  with only 4D and/or 3D tensors. Our motivation is that 3D convolutions with 5D tensors
  are computationally very expensive and they may not be supported by some of the
  edge devices used in real-time applications such as robots. The existing approaches
  mitigate this by splitting the 3D kernels into spatial and temporal domains, but
  they still use 3D convolutions with 5D tensors in their implementations. We resolve
  this issue by introducing some appropriate 4D/3D tensor reshaping as well as new
  combination techniques for spatial and temporal splits. The proposed implementation
  methods show significant improvement both in terms of efficiency and accuracy. The
  experimental results confirm that the proposed spatio-temporal processing structure
  outperforms the original model in terms of speed and accuracy using only 4D tensors
  with fewer parameters.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: hajimolahoseini24a
month: 0
tex_title: Is {3D} Convolution with {5D} Tensors Really Necessary for Video Analysis?
firstpage: 136
lastpage: 144
page: 136-144
order: 136
cycles: false
bibtex_author: Hajimolahoseini, Habib and Ahmed, Walid and Wen, Shuangyue and Liu,
  Yang
author:
- given: Habib
  family: Hajimolahoseini
- given: Walid
  family: Ahmed
- given: Shuangyue
  family: Wen
- given: Yang
  family: Liu
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
pdf: https://raw.githubusercontent.com/mlresearch/v262/main/assets/hajimolahoseini24a/hajimolahoseini24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
