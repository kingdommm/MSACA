# MSACA：Fake News Detection via Multi-scale Semantic Alignment and Cross-modal Attention
Pytorch code for the MSACA paper accepted in the The 47th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 2024)

## Overview
This repository contains code necessary to run the MSACA. MSACA is a multimodal fake news detection network by deep learning. See our paper for details on the code.

## Dataset
The meta-data of the Weibo and GossipCop datasets used in our experiments are available in their papers.
- Multimodal Fusion with Recurrent Neural Networks for Rumor Detection on Microblogs [论文地址](https://dl.acm.org/doi/10.1145/3123266.3123454)
- Fakenewsnet: A data repository with news content, social context, and spatiotemporal information for studying fake news on social media [项目地址](https://github.com/KaiDMML/FakeNewsNet))

## Running code 
The `train.py` is the main file for running the code.

## Reference📜
Detailed data analysis and method are in our paper. If you are insterested in this work, and want to use the dataset or codes in this repository, please star this repository and cite by:
```
@inproceedings{10.1145/3626772.3657905,
author = {Wang, Jiandong and Zhang, Hongguang and Liu, Chun and Yang, Xiongjun},
title = {Fake News Detection via Multi-scale Semantic Alignment and Cross-modal Attention},
year = {2024},
isbn = {9798400704314},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3626772.3657905},
doi = {10.1145/3626772.3657905},
pages = {2406–2410},
numpages = {5},
keywords = {fake news detection, multi-scale representation, multimodal learning},
location = {Washington DC, USA},
series = {SIGIR '24}
}
```
