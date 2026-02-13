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

Welcome! I am an assistant professor in the <a href="https://www.mccormick.northwestern.edu/industrial/">Department of Industrial Engineering and Management Sciences (IEMS) </a> and the <a href="https://www.mccormick.northwestern.edu/mechanical/">Department of Mechanical Engineering (ME) </a> at Northwestern University. I obtained my Ph.D. from the Department of Industrial and Operations Engineering at the University of Michigan. The research in our lab is driven by the need for novel statistical and optimization methodologies addressing scientific and engineering challenges across diverse domains, including distributed data ecosystems, Digital Twins, and smart manufacturing. We are also interested in investigating the theoretical underpinnings of these methods. In particular, our current research in **personalized, collaborative, and decentralized** data analytics explores computational techniques to integrate knowledge from multiple sources.  






Featured papers
======
A few topics of my research are introduced below.

---

<ins>**Scalable Mean-Field Variational Inference via Preconditioned Primal-Dual Optimization**</ins> 
Jinhua Lyu, Tianmin Yu, Ying Ma, Naichen Shi, 2026. [Link](https://arxiv.org/abs/2602.07632).

<div class="myresearchdetails"> The scale and complexity of modern Bayesian statistics are growing. While Mean Field Variational Inference (MFVI) offers an efficient approach to probabilistic inference, it struggles to handle hierachical models where the number of latent variables grows with the number of data points. We developed a mini-batch version of MFVI and introduced a primal-dual algorithm, PD-VI, along with its block-preconditioned extension, P²D-VI. These methods utilize an augmented Lagrangian formulation to jointly update global and local parameters while adapting to heterogeneous loss geometries.
</div>

<p align="center">
  <img src="images/mouse.png" alt="Mouse" width="400" style="display: inline-block; margin: 0 10px;"/>
</p>

<div class="myresearchdetails"> 
On a spatial transcriptomics domain detection task, P²D-VI is capable of segmenting transcriptomic profiles across over 150,000 locations in under 6 seconds.
</div>


<ins>**Calibrated Principal Component Regression**</ins> 
Yixuan Florence Wu, Yilun Zhu, Lei Cao, Naichen Shi, 2025. [Link](https://arxiv.org/abs/2510.19020).

<div class="myresearchdetails">When we reduce the dimension of the input data using PCA, we reduce data complexity by retaining only most relevant information. However, using only top PCA embeddings for downstream analytics, such as regression, always brings risks as meaningful information in the remaining PCs could be discarded.</div>
<p align="center">
  <img src="images/pcr_cpcr_intro.png" alt="CPCR" width="200" style="display: inline-block; margin: 0 10px;"/>
</p>

<div class="myresearchdetails">We introduce a Calibrated Principal Component Regression model that leverages cross-fitting to restore some information lost in PCA. A risk analysis grounded the random matrix theory reveals the optimal tradeoff between bias and variance. </div>

---

[Here](https://naichenshi.github.io/research/) is a more comprehensive list of publications. You can also check my [Google scholar profile](https://scholar.google.com/citations?user=9DVanY4AAAAJ&hl=en).

Recent news
======
- October 2025: Our paper, "Calibrated Principal Component Regression," is [online](https://arxiv.org/abs/2510.19020)!

<details>

<summary>Previous news</summary>

<ul>
<li> September 2024: Our paper, "Triple Component Matrix Factorization: Untangling Global, Local, and Noisy Components," is selected as the winner for the Data Mining best paper competition in INFORMS, 2024! </li>


<li> June 2024: Our paper, "Triple Component Matrix Factorization: Untangling Global, Local, and Noisy Components", won the <a href="https://ioe.engin.umich.edu/2024/05/10/ioe-graduate-class-of-2024/#:~:text=The%20Wilson%20Prize%20was%20won,any%20application%20of%20Industrial%20Engineering.">Wilson prize</a>! </li>

<li> October 2023: Our paper, "Personalized Tucker Decomposition: Modeling Commonality and Peculiarity on Tensor Data",  is selected as the finalist of the INFORMS 2023 QSR best refereed paper competition! </li>

<li> October 2023: Our paper, "Heterogeneous Matrix Factorization: When features differ by datasets", is selected as the finalist of the INFORMS 2023 best student paper competition! </li>

<li> July 2023: I am selected as the instructor of the small course of IOE 202 Operations Engineering and Analytics! </li>



</ul>

</details>
