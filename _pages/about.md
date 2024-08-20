---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---



Welcome! I am a Ph.D. candidate in the Department of Industrial and Operations Engineering at the University of Michigan, advised by [Dr. Raed Al Kontar](https://alkontar.engin.umich.edu/). My research is driven by the need for novel statistical and optimization methodologies addressing scientific and engineering challenges across diverse domains, including the Internet of Things, smart manufacturing, and spatial transcriptomics. I am also interested in investigating the theoretical underpinnings of these methods. In particular, my current research in **personalized, collaborative, and decentralized** data analytics explores computational techniques to integrate knowledge from multiple sources and builds tailored machine-learning models.  

<span style="color:#7bb3a9">**I am looking for Academic positions!** Please kindly let me know if you have any openings.</span>

Featured papers
======
A few topics of my research are introduced below.

---

<ins>**Personalized PCA: Decoupling Shared and Unique Features**</ins> 
Naichen Shi, Raed Al Kontar. *Journal of Machine Learning Research (JMLR)*, 2024. [Link](https://www.jmlr.org/papers/v25/22-0810.html), [Video](https://www.youtube.com/watch?v=9XWY745ZFPM), [Code](https://github.com/UMDataScienceLab/Personalized_PCA).

<sub> When data are collected from multiple related but heterogeneous sources, how can we efficiently integrate the common information among these sources? How to describe and make use of the unique feature in each source? We take advantage of the feature extraction power of principal component analysis (PCA). More specifically, we use global principal components (PCs) to model the common information and local principal components to capture the unique information.  </sub>

![Personalized PCA](./images/perpca.png)

<sub> **Identifiability** is a key hurdle as the global PCs can be confounded with local PCs in data. We propose a *misalignment condition* that measures the "smallest difference" among the subspaces spanned by global PCs. The condition helps us establish an upper bound on the statistical error of the global and local PCs, which almost matches their lower bound. Intriguingly, the results suggest that a higher level of heterogeneity can decrease the statistical error in our method, a benefit of personalization.  </sub>

<sub>Despite the simplicity, Personalized PCA and its derivatives have proven valuable in a variety of fields, including [**additive manufacturing**](https://www.sciencedirect.com/science/article/abs/pii/S0278612524000694), [**solar flare detection**](https://arxiv.org/pdf/2309.03439), and **spatial transcriptomics analysis**.</sub>

<p align="center">
  <img src="images/3dprinting.png" alt="3D printing" width="200" style="display: inline-block; margin: 0 10px;"/>
  <img src="images/srt.png" alt="Spatial transcriptomics" width="80" style="display: inline-block; margin: 0 10px;"/>
  <img src="images/solarflare.png" alt="Solar flare" width="150" style="display: inline-block; margin: 0 10px;"/>
</p>

<sub> An article from [Phys.org](https://phys.org/news/2024-03-statistical-tool-distinguish-unique-features.html) reports this method. </sub>

---

<ins>**Personalized Federated Learning via Domain Adaptation with an Application to Distributed 3D Printing**</ins> 
Naichen Shi, Raed Al Kontar. *Technometrics*, 2023. [Link](https://www.tandfonline.com/doi/abs/10.1080/00401706.2022.2157882?journalCode=utch20), [Video](https://www.youtube.com/watch?v=wOV8ZwdHgJ0), [Code](https://github.com/UMDataScienceLab/Personalized_FL_with_DA).

<sub> Federated learning (FL) uses data from multiple clients to collectively train predictive models. Challenges arise when marginal distributions on the input are heterogeneous among clients. In such scenarios, training predictive models with existing methods is uneasy as the input distributions can differ and even be non-overlapping.  To address these challenges, we propose a method based on domain adaptation that firstly maps the input into a common feature space, then predict the outputs from the features. We also use a bi-lavel optimization to optimize the feature encoder and decoder. In an application of material extrusion 3D printing, our method demonstrates improved accuracy and robustness predictive performances.</sub>

![3D printing examples](./images/pflda.png)
---

<ins>**RMSprop converges with proper hyper-parameter**</ins>
Naichen Shi, Dawei Li, Mingyi Hong, Ruoyu Sun. *International Conference on Learning Representations (ICLR)*, 2021. [Link](https://openreview.net/forum?id=3UDSdyIcBDA), [Video](https://iclr.cc/virtual/2021/spotlight/3415), [Code](https://github.com/soundsinteresting/RMSprop).


<sub>Almost every ML/AL practitioner uses adaptive stepsize optimization algorithms (e.g., Adam). Surprisingly, an important theoretical problem was largely unexplored: under what conditions can they converge? We show, both theoretically and numerically, that the good performance of RMSprop and Adam is contingent on the appropriate choice of the exponential averaging parameter $\beta_2$. Only when $\beta_2$ close enough to 1 can (stochastic versions of) Adam and RMSprop generate stable update directions that gradually lead the updates to the optimality. </sub>

<p align="center">
  <img src="images/adamconverge.png" alt="Adam updates" width="250" style="display: inline-block; margin: 0 10px;"/>

</p>

---

[Here](https://naichenshi.github.io/publications/) is a more comprehensive list of publications. You can also check my [Google scholar profile](https://scholar.google.com/citations?user=9DVanY4AAAAJ&hl=en).

News
======
- July 2024: I presented our paper,  "Multi-physics Simulation Guided Generative Diffusion Models with Applications in Fluid and Heat Dynamics", at ICQSR 2024, in Como, Italy.

- June 2024: Our paper, "Triple Component Matrix Factorization: Untangling Global, Local, and Noisy Components", won the Wilson prize!

- October 2023: Our paper, "Personalized Tucker Decomposition: Modeling Commonality and Peculiarity on Tensor Data",  is selected as the finalist of the INFORMS 2023 QSR best refereed paper competition!

- October 2023: Our paper, "Heterogeneous Matrix Factorization: When features differ by datasets", is selected as the finalist of the INFORMS 2023 best student paper competition!

- July 2023: I am selected as the instructor of the small course of IOE 202 Operations Engineering and Analytics!

- June 2023: I presented at ICQSR 2023 on the topic of heterogeneous matrix factorization!

