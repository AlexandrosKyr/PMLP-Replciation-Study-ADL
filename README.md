# PMLP Replication Study - Advanced Topics in Deep Learning (ATDL)

![GitHub license](https://img.shields.io/github/license/AlexandrosKyr/PMLP-Replication-Study-ADL)
![GitHub stars](https://img.shields.io/github/stars/AlexandrosKyr/PMLP-Replication-Study-ADL?style=social)
![GitHub forks](https://img.shields.io/github/forks/AlexandrosKyr/PMLP-Replication-Study-ADL?style=social)

## Based on Previous Work

This project is a **replication study** of the paper:

- **Graph Neural Networks are Inherently Good Generalizers: Insights by Bridging GNNs and MLPs**  
  *Yang et al., 2023 (ICLR 2023)*  
  📄 [Paper Link](https://arxiv.org/abs/2212.09034)  
  🔗 [Original Code Repository](https://github.com/chr26195/PMLP)

The goal of this study is to **replicate the key experiments** from Yang et al., 2023, verifying whether:
1. **PMLPs generalize better** compared to standard MLPs.
2. **PMLPs perform comparably to GNNs** while being computationally efficient.
3. The model’s **efficiency gains hold across different datasets**.

🔗 **Project Repository:** [https://github.com/AlexandrosKyr/PMLP-Replication-Study-ADL](https://github.com/AlexandrosKyr/PMLP-Replication-Study-ADL)  

---

## Table of Contents
- [Based on Previous Work](#-based-on-previous-work)
- [Datasets](#-datasets)
- [Code & Implementation](#️-code--implementation)
- [Installation](#-installation)
- [Usage](#-usage)
- [Results](#-results)
- [Limitations & Future Work](#️-limitations--future-work)

---

## Datasets
We evaluate our replication study using **homophilic and heterophilic graph datasets**:

| **Dataset**       | **Type**               | **Nodes**  | **Edges**   | **Classes** |
|------------------|----------------------|-----------:|------------:|------------:|
| **Cora**         | Citation Network     | 2,708      | 5,429       | 7           |
| **Wisconsin**    | Webpage Network      | 251        | 515         | 5           |
| **OGBN-Arxiv**   | Citation Network     | 169,343    | 1,166,243   | 40          |
| **Coauthor-CS**  | Co-authorship Network | 18,333     | 81,894      | 15          |

📌 **Heterophilic Graphs:** Wisconsin  
📌 **Homophilic Graphs:** Cora, OGBN-Arxiv, Coauthor-CS  
