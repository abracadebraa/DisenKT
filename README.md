# DisenKT: A Variational Attention-Based Approach for Disentangled Cross-Domain Knowledge Tracing

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)

## 📄 Paper

**DisenKT: A Variational Attention-Based Approach for Disentangled Cross-Domain Knowledge Tracing**  
*Information Processing & Management (Elsevier), 2026*

- 🔗 DOI: https://doi.org/10.1016/j.ipm.2025.104582  
- 🔗 ScienceDirect: https://www.sciencedirect.com/science/article/abs/pii/S0306457325005230  

---

Official project page for the paper.

---

## Overview

DisenKT is a variational attention-based framework for cross-domain knowledge tracing that explicitly disentangles student knowledge states into **domain-shared** and **domain-exclusive** representations.

By leveraging a Variational Attention Autoencoder (VAAE) architecture and mutual information minimization, DisenKT enables selective knowledge transfer across domains while effectively reducing negative transfer.

Experimental results demonstrate that DisenKT consistently outperforms existing knowledge tracing and cross-domain KT approaches in both **course-level** and **student-level** CDKT scenarios.

---

## Key Features

- **Disentangled Knowledge Tracing**  
  Explicit modeling of domain-shared and domain-exclusive knowledge states improves both prediction accuracy and interpretability.

- **Variational Attention Autoencoder (VAAE)**  
  A novel sequence modeling architecture that integrates hierarchical self-attention with variational inference.

- **Negative Transfer Mitigation**  
  Mutual information minimization is employed to promote independence between disentangled latent representations and reduce harmful transfer.

- **Consistent Performance Gains**  
  Achieves stable improvements across multiple cross-domain knowledge tracing benchmarks.

- **Multi-Domain Applicability**  
  Designed to support complex educational settings involving multiple source and target domains.

---

## Code Availability

The source code of this project is currently **not publicly released**.

Due to ongoing extensions and further investigation of the proposed method,
as well as potential intellectual property considerations,
the code is available **upon reasonable request** for **academic research purposes only**.

If you are interested, please contact the authors via email and include:
- Your name and affiliation
- A brief description of your research purpose

📧 Contact: liuyuqi@m.scnu.edu.cn

---

## Citation

If you find this work useful in your research, please consider citing:

```bibtex
@article{disenkt2026,
  title={DisenKT: A Variational Attention-Based Approach for Disentangled Cross-Domain Knowledge Tracing},
  author={Yuqi Liu et al.},
  journal={Information Processing \& Management},
  volume={63},
  number={3},
  pages={104582},
  year={2026},
  publisher={Elsevier}
}
```
