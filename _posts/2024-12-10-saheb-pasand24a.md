---
title: 'RGP: Achieving Memory-Efficient Model Fine-tuning Via Randomized Gradient
  Projection'
section: Training
abstract: Training and fine-tuning Large Language Models (LLMs) require significant
  memory due to the substantial growth in the size of weight parameters and optimizer
  states. While methods like low-rank adaptation (LoRA), which introduce low-rank
  trainable modules in parallel to frozen pre-trained weights, effectively reduce
  memory usage, they often fail to preserve the optimization trajectory and are generally
  less effective for pre-training models. On the other hand, approaches, such as GaLore,
  that project gradients onto lower-dimensional spaces maintain the training trajectory
  and perform well in pre-training but suffer from high computational complexity,
  as they require repeated singular value decomposition on large matrices. In this
  work, we propose Randomized Gradient Projection (RGP), which outperforms GaLore,
  the current state-of-the-art in efficient fine-tuning, on the GLUE task suite, while
  being 74% faster on average and requiring similar memory.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: saheb-pasand24a
month: 0
tex_title: "{RGP}: Achieving Memory-Efficient Model Fine-tuning Via Randomized Gradient
  Projection"
firstpage: 47
lastpage: 54
page: 47-54
order: 47
cycles: false
bibtex_author: Saheb Pasand, Ali and Bashivan, Pouya
author:
- given: Ali
  family: Saheb Pasand
- given: Pouya
  family: Bashivan
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
pdf: https://raw.githubusercontent.com/mlresearch/v262/main/assets/saheb-pasand24a/saheb-pasand24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
