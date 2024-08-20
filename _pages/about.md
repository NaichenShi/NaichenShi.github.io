---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---



Welcome! I am a Ph.D. candidate in the Department of Industrial and Operations Engineering at the University of Michigan advised by [Dr. Raed Al Kontar](https://alkontar.engin.umich.edu/). My research is driven by the need for novel statistical and optimization methodologies addressing scientific and engineering challenges across diverse domains, including the Internet of Things, smart manufacturing, and spatial transcriptomics. I am also interested in investigating the theoretical underpinnings of these methods. In particular, my current research in <span style="color:#bf8f78">personalized, collaborative, and decentralized</span> data analytics explores computational techniques to integrate knowledge from multiple sources and builds tailored machine-learning models.  



Featured papers
======
A few topics of my research are introduced below.

---

<ins>**Personalized PCA: Decoupling Shared and Unique Features**</ins> 
Naichen Shi, Raed Al Kontar. *Journal of Machine Learning Research (JMLR)*, 2024. [Link](https://www.jmlr.org/papers/v25/22-0810.html), [Video](https://www.youtube.com/watch?v=9XWY745ZFPM), [Code](https://github.com/UMDataScienceLab/Personalized_PCA)

When data are collected from multiple related but heterogeneous sources, how can we efficiently integrate the common information among these sources? How to describe and make use of the unique feature in each source? We take advantage of the feature extraction power of principal component analysis (PCA). More specifically, we use global principal components (PCs) to model the common information and local principal components to capture the unique information.  

![Personalized PCA](./images/perpca.png)

**Identifiability** is a challenge as the global PCs can be difficult to separate from local PCs in data. We propose a *misalignment condition* that measures the "smallest difference" among the subspaces spanned by global PCs. Based on the misalignment condition, we provide an upper bound on the statistical error of the global and local PCs, which almost matches their lower bound. 

Despite the simplicity, Personalized PCA and its variants have found several useful applications in [**additive manufacturing**](https://www.sciencedirect.com/science/article/abs/pii/S0278612524000694), [**solar flare detection**](https://arxiv.org/pdf/2309.03439), and **spatial transcriptomics analysis**.

<p align="center">
  <img src="images/3dprinting.png" alt="3D printing" width="200" style="display: inline-block; margin: 0 10px;"/>
  <img src="images/srt.png" alt="Spatial transcriptomics" width="80" style="display: inline-block; margin: 0 10px;"/>
  <img src="images/solarflare.png" alt="Solar flare" width="180" style="display: inline-block; margin: 0 10px;"/>
</p>

An article from [Phys.org](https://phys.org/news/2024-03-statistical-tool-distinguish-unique-features.html) reports this method.

---

<ins>**Personalized Federated Learning via Domain Adaptation with an Application to Distributed 3D Printing**</ins> 
Naichen Shi, Raed Al Kontar. *Technometrics*, 2023. [Link](https://www.tandfonline.com/doi/abs/10.1080/00401706.2022.2157882?journalCode=utch20), [Video](https://www.youtube.com/watch?v=wOV8ZwdHgJ0), [Code](https://github.com/UMDataScienceLab/Personalized_FL_with_DA)

