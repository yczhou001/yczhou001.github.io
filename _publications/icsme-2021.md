---
title: "On the Evaluation of Commit Message Generation Models: An Experimental Study"
collection: publications
permalink: /publication/icsme-2021
excerpt: 'Commit messages are natural language descriptions of code changes, which are important for program understanding and maintenance. However, writing commit messages manually is time-consuming and laborious, especially when the code is updated frequently. Various approaches utilizing generation or retrieval techniques have been proposed to automatically generate commit messages. To achieve a better understanding of how the existing approaches perform in solving this problem, this paper conducts a systematic and in-depth analysis of the state-of-the-art models and datasets. We find that: (1) Different variants of the BLEU metric are used in previous works, which affects the evaluation and understanding of existing methods. (2) Most existing datasets are crawled only from Java repositories while repositories in other programming languages are not sufficiently explored. (3) Dataset splitting strategies can influence the performance of existing models by a large margin. Some models show better performance when the datasets are split by commit, while other models perform better when the datasets are split by timestamp or by project. Based on our findings, we conduct a human evaluation and find the BLEU metric that best correlates with the human scores for the task. We also collect a large-scale, information-rich, and multi-language commit message dataset MCMD and evaluate existing models on this dataset. Furthermore, we conduct extensive experiments under different dataset splitting strategies and suggest the suitable models under different scenarios. Based on the experimental results and findings, we provide feasible suggestions for comprehensively evaluating commit message generation models and discuss possible future research directions. We believe this work can help practitioners and researchers better evaluate and select models for automatic commit message generation. Our source code and data are available at https://github.com/DeepSoftwareAnalytics/CommitMsgEmpirical.'
date: 2021-09-27
venue: ''
paperurl: 'http://academicpages.github.io/files/paper2.pdf'
citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---

## Abstract

Commit messages are natural language descriptions of code changes, which are important for program understanding and maintenance. However, writing commit messages manually is time-consuming and laborious, especially when the code is updated frequently. Various approaches utilizing generation or retrieval techniques have been proposed to automatically generate commit messages. To achieve a better understanding of how the existing approaches perform in solving this problem, this paper conducts a systematic and in-depth analysis of the state-of-the-art models and datasets. We find that: (1) Different variants of the BLEU metric are used in previous works, which affects the evaluation and understanding of existing methods. (2) Most existing datasets are crawled only from Java repositories while repositories in other programming languages are not sufficiently explored. (3) Dataset splitting strategies can influence the performance of existing models by a large margin. Some models show better performance when the datasets are split by commit, while other models perform better when the datasets are split by timestamp or by project. Based on our findings, we conduct a human evaluation and find the BLEU metric that best correlates with the human scores for the task. We also collect a large-scale, information-rich, and multi-language commit message dataset MCMD and evaluate existing models on this dataset. Furthermore, we conduct extensive experiments under different dataset splitting strategies and suggest the suitable models under different scenarios. Based on the experimental results and findings, we provide feasible suggestions for comprehensively evaluating commit message generation models and discuss possible future research directions. We believe this work can help practitioners and researchers better evaluate and select models for automatic commit message generation. Our source code and data are available at [https://github.com/DeepSoftwareAnalytics/CommitMsgEmpirical](https://github.com/DeepSoftwareAnalytics/CommitMsgEmpirical).

## Links

[View at IEEE *Xplore*](https://ieeexplore.ieee.org/document/9609189)

[Download paper here](https://arxiv.org/pdf/2107.05373)

[Dataset: **M**ulti-language **C**ommit **M**essage **D**ataset, MCMD](https://doi.org/10.5281/zenodo.5025758)

[Code](https://github.com/DeepSoftwareAnalytics/CommitMsgEmpirical)

## Related Works

[A Large-Scale Empirical Study of Commit Message Generation: Models, Datasets and Evaluation](../emse-2022)

## Recommended citation

### Plain Text

```markdown
W. Tao et al., "On the Evaluation of Commit Message Generation Models: An Experimental Study," 2021 IEEE International Conference on Software Maintenance and Evolution (ICSME), 2021, pp. 126-136, doi: 10.1109/ICSME52107.2021.00018..
```

### BibTex

```bibtex
@inproceedings{DBLP:conf/icsm/TaoWSDH0ZZ21, \
  author    = {Wei Tao and \
               Yanlin Wang and \
               Ensheng Shi and \
               Lun Du and \
               Shi Han and \
               Hongyu Zhang and \
               Dongmei Zhang and \
               Wenqiang Zhang}, \
  title     = {On the Evaluation of Commit Message Generation Models: An Experimental \
               Study}, \
  booktitle = {{IEEE} International Conference on Software Maintenance and Evolution, \
               {ICSME} 2021, Luxembourg, September 27 - October 1, 2021}, \
  pages     = {126--136}, \
  publisher = {{IEEE}}, \
  year      = {2021}, \
  url       = {https://doi.org/10.1109/ICSME52107.2021.00018}, \
  doi       = {10.1109/ICSME52107.2021.00018}, \
  timestamp = {Thu, 14 Jul 2022 08:16:44 +0200}, \
  biburl    = {https://dblp.org/rec/conf/icsm/TaoWSDH0ZZ21.bib}, \
  bibsource = {dblp computer science bibliography, https://dblp.org} \
}
```
