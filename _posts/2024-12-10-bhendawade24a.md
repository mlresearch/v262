---
title: 'Speculative Streaming: Fast LLM Inference without Auxiliary Models'
section: Inference
abstract: Speculative decoding is a prominent technique to accelerate large language
  model inference by leveraging predictions from an auxiliary draft model. While effective,
  in application-specific settings, it often involves fine-tuning both draft and target
  models to achieve high acceptance rates. As the number of downstream tasks grows,
  draft models add significant complexity to inference systems. Recently several single
  model architectures viz. Medusa have been proposed to speculate tokens in non-autoregressive
  manner, however, their effectiveness is limited due to lack of dependency between
  speculated tokens. We introduce a novel speculative decoding method that integrates
  drafting within the target model by using Multi-stream attention and incorporates
  future token planning into supervised fine-tuning objective. To the best of our
  knowledge, it is the first parameter-efficient approach that scales well with number
  of downstream tasks while improving downstream metrics. Speculative Streaming speeds
  up decoding by 1.9 - 3X in a diverse set of tasks, such as Summarization, Structured
  Queries, and Meaning Representation, while improving generation quality and using
  10000X fewer extra parameters than alternative architectures, making it ideal for
  resource-constrained devices. Our approach can also be effectively deployed in lossless
  settings for generic chatbot applications that do not necessitate fine-tuning. In
  such setups, we achieve 2.9 - 3.2X speedup while maintaining the integrity of the
  base model’s output.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bhendawade24a
month: 0
tex_title: 'Speculative Streaming: Fast {LLM} Inference without Auxiliary Models'
firstpage: 395
lastpage: 413
page: 395-413
order: 395
cycles: false
bibtex_author: Bhendawade, Nikhil and Belousova, Irina and Fu, Qichen and Mason, Henry
  and Rastegari, Mohammad and Najibi, Mahyar
author:
- given: Nikhil
  family: Bhendawade
- given: Irina
  family: Belousova
- given: Qichen
  family: Fu
- given: Henry
  family: Mason
- given: Mohammad
  family: Rastegari
- given: Mahyar
  family: Najibi
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
pdf: https://raw.githubusercontent.com/mlresearch/v262/main/assets/bhendawade24a/bhendawade24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
