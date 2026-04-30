---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Computer Science PhD student at the University of British Columbia (UBC) [Systopia Lab](https://systopia.cs.ubc.ca/people) supervised by [Mathias Lécuyer](https://mathias.lecuyer.me/). I received my MSc. and B.S. in Statistics at UBC, where I was advised by [Aline Talhouk](https://talhouklab.med.ubc.ca/dr-aline-talhouk/) and [Lang Wu](https://www.stat.ubc.ca/~lang/). In summer 2025, I worked with [Sepid Hosseini](https://sepidsh.github.io/), [Mengyao Zhai](https://mzhai.weebly.com/) and [Thibaut Durand](https://github.com/durandtibo) at [RBC Borealis](https://rbcborealis.com/).

My research focuses on data privacy, including designing efficient privacy-preserving algorithms with provable guarantees, auditing privacy leakage in trained machine learning models, and adapting existing tools to domain-specific problems. I have also worked on broader responsible AI topics, such as mitigating social bias and developing fairer models.


#### Selected Projects

See my [Google Scholar](https://scholar.google.ca/citations?user=qr_qHm4AAAAJ&hl=en) profile for a full list.

---

**Private and Stable Test-time Adaptation with Differential Privacy**
Zefeng Li\*, **Qiaoyue Tang\***, Mathias Lécuyer, Evan Shelhamer (*Alphabetical order)
*International Conference on Machine Learning (ICML) 2026*
[Paper]
- Improve test-time adaptation (TTA) performance using differentially private training techniques, enabling trained models to adapt to new and distributionally shifted test data with reduced error while preserving privacy guarantees.
- Evaluate on pretrained ViT and ConvNeXT models using ImageNet-C and ImageNet-R corruption benchmarks.

<div style="margin-bottom: 0.6em;"></div>

**FairNVT: Improving Fairness via Noise Injection in Vision Transformers**  
**Qiaoyue Tang**, Sepidehsadat Hosseini, Mengyao Zhai, Thibaut Durand, Greg Mori  
*Full version in submission*  
*Algorithmic Fairness Across Alignment Procedures and Agentic Systems (AFAA) Workshop @ ICLR 2026*  
[Paper](https://arxiv.org/abs/2604.16780)
- Develop a unified framework that improves both prediction- and representation-level fairness when fine-tuning biased pretrained models for downstream tasks.
- Show consistent fairness gains across vision and language benchmarks while preserving downstream accuracy.

<div style="margin-bottom: 0.6em;"></div>

**On the Performance of Differentially Private Optimization with Heavy-Tail Class Imbalance**  
**Qiaoyue Tang**, Alain Zhiyanov, and Mathias Lécuyer  
*High-dimensional Learning Dynamics Workshop @ ICML 2025*  
[Paper](https://arxiv.org/abs/2507.10536)
- Investigate the behavior of differentially private optimizers under heavy-tail class imbalance, a setting common in real-world data such as language modeling.

<div style="margin-bottom: 0.6em;"></div>

**PANORAMIA: Privacy Auditing of Machine Learning Models without Retraining**  
Mishaal Kazmi\*, Hadrien Lautraite\*, Alireza Akbari\*, **Qiaoyue Tang\***, Mauricio Soroco, Tao Wang, Sébastien Gambs, Mathias Lécuyer  
<sup>\* Equal contribution</sup>  
*Neural Information Processing Systems (NeurIPS) 2024*  
[Paper](https://arxiv.org/abs/2402.09477) / [Code](https://github.com/ubc-systopia/panoramia-privacy-measurement) / [Slides](/files/panoramia_nips_video.pdf)
- Develop a retraining-free privacy auditing framework that uses synthetic non-member data to evaluate membership inference attacks on target models.
- Perform theoretical analysis that establishes rigorous guidelines for privacy auditing under the proposed framework.

<div style="margin-bottom: 0.6em;"></div>

**DP-AdamBC: Your DP-Adam Is Actually DP-SGD (Unless You Apply Bias Correction)**  
**Qiaoyue Tang**, Frederick Shpilevskiy, Mathias Lécuyer  
*AAAI Conference on Artificial Intelligence (AAAI) 2024* <span style="color:red">**(Oral, 2.3% acceptance rate)**</span>  
<span style="font-size:0.85em; color:gray">Also presented at Workshop on Trustworthy and Reliable Large-Scale Machine Learning Models @ ICLR 2023</span>  
[Paper](https://arxiv.org/abs/2312.14334) / [Code](https://github.com/ubc-systopia/DP-AdamBC) / [Slides](/files/DP_AdamBC_AAAI_24_slides.pdf)
- Demonstrate that DP noise biases Adam's second moment estimator, collapsing DP-Adam into DP-SGD with momentum and breaking the sign-descent behavior that drives Adam's performance.
- Propose DP-AdamBC, a bias-corrected variant of DP-Adam, with accompanying theoretical analysis.

<div style="margin-bottom: 0.8em;"></div>

**DP-SGD-LF: Improving Utility under Differentially Private Learning via Layer Freezing**  
**Qiaoyue Tang**, Mathias Lécuyer  
[Paper](https://openreview.net/attachment?id=coLtCLTHFbW&name=pdf)
- Propose a layer-freezing variant of DP-SGD that improves utility at fixed privacy budget, supported by both theoretical analysis and empirical evaluation.
