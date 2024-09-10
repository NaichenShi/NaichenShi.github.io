---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
.myresearchdetails {
    font-size:0.8em;
    padding-left: 20px;
    margin: 10px;
}
</style>

Welcome! I am a Ph.D. candidate in the Department of Industrial and Operations Engineering at the University of Michigan, advised by [Dr. Raed Al Kontar](https://alkontar.engin.umich.edu/). My research is driven by the need for novel statistical and optimization methodologies addressing scientific and engineering challenges across diverse domains, including the Internet of Things, smart manufacturing, and spatial transcriptomics. I am also interested in investigating the theoretical underpinnings of these methods. In particular, my current research in **personalized, collaborative, and decentralized** data analytics explores computational techniques to integrate knowledge from multiple sources and builds tailored machine-learning models.  

<div style="padding: 15px; border: 0px solid transparent; border-color: transparent; margin-bottom: 20px; border-radius: 8px;  background-color: #dff0d8; border-color: #d6e9c6;text-align: center;
vertical-align: middle;">
<b>I am looking for academic positions!</b>
</div>

<div style="padding: 15px; border: 0px solid transparent; border-color: transparent; margin-bottom: 20px; border-radius: 8px;  background-color: #dff0d8; border-color: #d6e9c6;">
I am selected as a finalist in the <a href="https://connect.informs.org/communities/community-home/digestviewer/viewthread?GroupId=469&MessageKey=e1098b1d-0146-422f-a919-3f9d7c687678&CommunityKey=1d5653fa-85c8-46b3-8176-869b140e5e3c&hlmlt=VT">Data Mining Best Paper Competition</a> at INFORMS 2024. I will be presenting my work on October 23, 2024, at 8:00 AM in Regency - 704.
</div>


Featured papers
======
A few topics of my research are introduced below.

---

<ins>**Personalized PCA: Decoupling Shared and Unique Features**</ins> 
Naichen Shi, Raed Al Kontar. *Journal of Machine Learning Research (JMLR)*, 2024. [Link](https://www.jmlr.org/papers/v25/22-0810.html), [Video](https://www.youtube.com/watch?v=9XWY745ZFPM), [Code](https://github.com/UMDataScienceLab/Personalized_PCA).

<div class="myresearchdetails"> When data are collected from multiple related but heterogeneous sources, how can we efficiently integrate the common information among these sources? How to describe and make use of the unique feature in each source? We take advantage of the feature extraction power of principal component analysis (PCA). More specifically, we use global principal components (PCs) to model the common information and local principal components to capture the unique information.  </div>

<p align="center">
  <img src="./images/perpca.png" alt="Personalized PCA" width="450" style="display: inline-block; margin: 0 10px;"/>
</p>


<div class="myresearchdetails"> <b>Identifiability</b> is a key hurdle as the global PCs can be confounded with local PCs in data. We propose a <i>misalignment condition</i> that measures the "smallest difference" among the subspaces spanned by global PCs. The condition helps us establish an upper bound on the statistical error of the global and local PCs, which almost matches their lower bound. Intriguingly, the results suggest that a higher level of heterogeneity can decrease the statistical error in our method, a benefit of personalization.  </div>

<div class="myresearchdetails"> Despite the simplicity, Personalized PCA and its derivatives have proven valuable in a variety of fields, including  <a href="https://www.sciencedirect.com/science/article/abs/pii/S0278612524000694"><b>additive manufacturing</b></a>, <a href="https://arxiv.org/pdf/2309.03439"><b>solar flare detection</b></a>, and <b>spatial transcriptomics analysis</b>.</div>

<p align="center">
  <img src="images/3dprinting.png" alt="3D printing" width="250" style="display: inline-block; margin: 0 10px;"/>
  <img src="images/srt.png" alt="Spatial transcriptomics" width="100" style="display: inline-block; margin: 0 10px;"/>
  <img src="images/solarflare.png" alt="Solar flare" width="220" style="display: inline-block; margin: 0 10px;"/>
</p>

<div class="myresearchdetails"> An article from <a href="https://phys.org/news/2024-03-statistical-tool-distinguish-unique-features.html">Phys.org</a> reports this method. </div>

---

<ins>**Personalized Federated Learning via Domain Adaptation with an Application to Distributed 3D Printing**</ins> 
Naichen Shi, Raed Al Kontar. *Technometrics*, 2023. [Link](https://www.tandfonline.com/doi/abs/10.1080/00401706.2022.2157882?journalCode=utch20), [Code](https://github.com/UMDataScienceLab/Personalized_FL_with_DA).

<div class="myresearchdetails"> Federated learning (FL) uses data from multiple clients to collectively train predictive models. Challenges arise when marginal distributions on the input are heterogeneous among clients. In such scenarios, training predictive models with existing methods is uneasy as the input distributions can differ and even be non-overlapping.  To address these challenges, we propose a method based on domain adaptation that firstly maps the input into a common feature space, then predict the outputs from the features. We also use a bi-lavel optimization to optimize the feature encoder and decoder. In an application of material extrusion 3D printing, our method demonstrates improved accuracy and robustness predictive performances.</div>

<p align="center">
  <img src="./images/pflda.png" alt="3D printing examples" width="450" style="display: inline-block; margin: 0 10px;"/>
</p>

---

[Here](https://naichenshi.github.io/research/) is a more comprehensive list of publications. You can also check my [Google scholar profile](https://scholar.google.com/citations?user=9DVanY4AAAAJ&hl=en).

News
======
- September 2024: Our paper, "Triple Component Matrix Factorization: Untangling Global, Local, and Noisy Components," is selected as the finalist for the Data Mining best paper competition in INFORMS, 2024!

- July 2024: I presented our paper,  "Multi-physics Simulation Guided Generative Diffusion Models with Applications in Fluid and Heat Dynamics", at [ICQSR 2024](https://www.icqsr24.polimi.it/), in Como, Italy.

- June 2024: Our paper, "Triple Component Matrix Factorization: Untangling Global, Local, and Noisy Components", won the [Wilson prize](https://ioe.engin.umich.edu/2024/05/10/ioe-graduate-class-of-2024/#:~:text=The%20Wilson%20Prize%20was%20won,any%20application%20of%20Industrial%20Engineering.)!

- October 2023: Our paper, "Personalized Tucker Decomposition: Modeling Commonality and Peculiarity on Tensor Data",  is selected as the finalist of the INFORMS 2023 QSR best refereed paper competition!

- October 2023: Our paper, "Heterogeneous Matrix Factorization: When features differ by datasets", is selected as the finalist of the INFORMS 2023 best student paper competition!

- July 2023: I am selected as the instructor of the small course of IOE 202 Operations Engineering and Analytics!

- June 2023: I presented at ICQSR 2023 on the topic of heterogeneous matrix factorization!

