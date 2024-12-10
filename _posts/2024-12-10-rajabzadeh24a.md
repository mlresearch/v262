---
title: 'EchoAtt: Attend, Copy, then Adjust for More Efficient Large Language Models'
section: Model Efficiency \& Compression
abstract: Large Language Models (LLMs), with their increasing depth and number of
  parameters, have demonstrated outstanding performance across a variety of natural
  language processing tasks. However, this growth in scale leads to increased computational
  demands, particularly during inference and fine-tuning. To address these challenges,
  we introduce \textbf{EchoAtt}, a novel framework aimed at optimizing transformer-based
  models by analyzing and leveraging the similarity of attention patterns across layers.
  Our analysis reveals that many inner layers in LLMs, especially larger ones, exhibit
  highly similar attention matrices. By exploiting this similarity, \textbf{EchoAtt}
  enables the sharing of attention matrices in less critical layers, significantly
  reducing computational requirements without compromising performance. We incorporate
  this approach within a knowledge distillation setup, where a pre-trained teacher
  model guides the training of a smaller student model. The student model selectively
  shares attention matrices in layers with high similarity while inheriting key parameters
  from the teacher. Our best results with TinyLLaMA-1.1B demonstrate that \textbf{EchoAtt}
  improves inference speed by 15%, training speed by 25%, and reduces the number of
  parameters by approximately 4%, all while improving zero-shot performance. These
  findings highlight the potential of attention matrix sharing to enhance the efficiency
  of LLMs, making them more practical for real-time and resource-limited applications.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: rajabzadeh24a
month: 0
tex_title: "{EchoAtt}: Attend, Copy, then Adjust for More Efficient Large Language
  Models"
firstpage: 259
lastpage: 269
page: 259-269
order: 259
cycles: false
bibtex_author: Rajabzadeh, Hossein and Jafari, Aref and Sharma, Aman and Jami, Benyamin
  and Ju Hj Kwon, Hyock and Ghodsi, Ali and Chen, Boxing and Rezagholizadeh, Mehdi
author:
- given: Hossein
  family: Rajabzadeh
- given: Aref
  family: Jafari
- given: Aman
  family: Sharma
- given: Benyamin
  family: Jami
- given: Hyock
  family: Ju Hj Kwon
- given: Ali
  family: Ghodsi
- given: Boxing
  family: Chen
- given: Mehdi
  family: Rezagholizadeh
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
pdf: https://raw.githubusercontent.com/mlresearch/v262/main/assets/rajabzadeh24a/rajabzadeh24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
