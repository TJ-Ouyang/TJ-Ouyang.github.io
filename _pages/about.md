---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a second-year master student in [FIB-Lab](https://fi.ee.tsinghua.edu.cn/) at Tsinghua Univeristy, advised by Prof. [Yong Li](https://scholar.google.com/citations?user=kmgzPeQAAAAJ&hl). My research interest includes multimodal LLM's application on health, urban science, and socioeconomics.

Research Projects
======

ChestLIP-LLM: Understanding Health Records and Chest X-ray Images via Multi-modal LLM
------
Chest X-rays are among the most common and cost-effective medical imaging exams. However, diagnosing chest X-rays can be challenging. To address this, we propose a novel approach that utilizes contrastive pre-training (CLIP) to cluster X-ray images based on similar diagnostic labels. By incorporating chain of thought (CoT) prompts and visual instruction tuning with clinical knowledge, our method aims to enhance the accuracy of large language models (LLMs) in diagnosis, and provide more thorough, structured explanations. (Ongoing project)

[Health CLIP: Depression Rate Prediction Using Satellite and Street View Images](https://dl.acm.org/doi/10.1145/3589335.3651451):
------
As the pressure of society keeps growing, depression hasbecome a severe problem in modern cities, therefore finding a way toestimate depression rate is of significance to relieve the problem. We adopt GPT4-vision to generate health related captions for satellite and street view images, then fine-tune CLIP model with the encapsulated image-text pairs, pushing CLIP's image encoder to extract health related features. In the end, we concatenate the features with neural network to predict the depression rate in New York City. (First author, WWW'24)

UrbanMLLM: Joint Learning of Cross-view Imagery for Urban Understanding
------
We propose UrbanMLLM, a novel multimodal large language model designed to enhance urban understanding by jointly learning from satellite-view and street-view imagery, addressing the challenges of needing a large-scale cross-view dataset and the difficulty of traditional MLLMs in integrating diverse urban imagery, through the introduction of a cross-view perceiver architecture and interleaved pre-training approach, resulting in significant performance improvements across 13 urban understanding tasks. (Shared first author, under review at ICLR'25)

[CityBench: Evaluating the Capabilities of Large Language Model as World Model](https://arxiv.org/abs/2406.13945):
------
We propose a simulator based global scale benchmark to evaluate the performance of large language model on various urban tasks, such as geospatial prediction, mobility prediction and street navigation task. I am in charge of vision part of this project, focusing on testing various open-source and closed-source multi-modal LLMs' ability on geo-location and socio-economy prediction via street view and satellite images. (Shared second author, under review at ICLR'25)

Explaining Infant and Maternal Mortality in Africa via Night Light and Satellite Imagery:
------
We try to use regression algorithm and machine learning method to explain what are the factors that affecting infant and maternal mortality rate in Africa, where only a small proportion of data are available with long interval. (Ongoing project)

[LCSim: A Large-Scale Controllable Traffic Simulator](https://arxiv.org/abs/2406.19781):
------
We propose LCSim, a large-scale controllable traffic simulator. LCSim provides map tools for constructing unified HD map descriptions from either open-source datasets including Waymo and Argoverse or publicly available data sources like OpenStreetMap to scale up the simulation scenarios. Diffusion-based traffic simulation is integrated into the simulator to achieve realistic and controllable microscopic traffic flow modeling. (Second author, under review at ICLR'25)

Highly Sensitive Biosensor Based on Terahertz Metasurface:
------
A new metasurface biosensor structure of metal ring surface and quartz substrate is proposed. Using the surface plasmon resonance (SPR) method, it has an extremely high quality factor (Q value), great sensitivity and quality factor. The performance of the metasurface are tested using the CST simulation suite.
