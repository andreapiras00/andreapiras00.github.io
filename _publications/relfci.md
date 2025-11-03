---
title: "Relational Causal Discovery with Latent Confounders"
collection: publications
category: conferences
permalink: /publication/relational-causal-discovery-with-latent-confounders
excerpt: 'Introduced RelFCI, an algorithm extending FCI to relational data with latent confounders and non-i.i.d. assumptions.'
date: 2025-07-20
venue: 'Conference on Uncertainty in Artificial Intelligence (UAI)'
paperurl: 'https://dl.acm.org/doi/10.5555/3762387.3762521'
bibtexurl: '/files/relfci.bib'
paperpdf: '/files/RelFCI.pdf'
citation: 'Negro, Matteo, Andrea Piras et al. "Relational Causal Discovery with Latent Confounders." The 41st Conference on Uncertainty in Artificial Intelligence.'
---

Estimating causal effects from real-world relational data can be challenging when the underlying causal model and potential confounders are unknown. While several causal discovery algorithms exist for learning causal models with latent confounders from data, they assume that the data is independent and identically distributed (i.i.d.) and are not well-suited for learning from relational data. Similarly, existing relational causal discovery algorithms assume causal sufficiency, which is unrealistic for many real-world datasets. To address this gap, we propose RelFCI, a sound and complete causal discovery algorithm for relational data with latent confounders. Our work builds upon the Fast Causal Inference (FCI) and Relational Causal Discovery (RCD) algorithms and it defines new
graphical models, necessary to support causal discovery in relational domains. We also establish soundness and completeness guarantees for relational d-separation with latent confounders. We present experimental results demonstrating the effectiveness of RelFCI in identifying the correct causal structure in relational causal models with latent confounders.
