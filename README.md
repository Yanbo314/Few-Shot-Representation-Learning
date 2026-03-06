# 🌸 Few-Shot Representation Learning on Flowers102

Self-supervised representation learning on the **Oxford 102 Flower Dataset** using PyTorch.

This project explores learning image representations when **only a few labeled samples are available**.  
Two unsupervised approaches are implemented and evaluated using downstream classifiers.

---

## 🚀 Project Overview

The Oxford Flowers102 dataset contains **102 flower categories**, but only **10 labeled training samples per class**.  
To address this few-shot learning challenge, we apply **self-supervised representation learning**.

Two methods are explored:

- **Contrastive Learning (SimCLR-style)**
- **Clustering-based Representation Learning**

The learned representations are evaluated using:

- **Linear Probe**
- **MLP Classifier**

---

## 📂 Repository Structure
Few-Shot-Representation-Learning
│
├── notebooks/
│ └── main.ipynb # Main experiment notebook

├── data/ # Dataset storage

├── checkpoints/ # Saved models

├── results/ # Experiment results

├── figures/ # Plots

├── requirements.txt

└── README.md

---

## ⚙️ Installation

Install dependencies:

```bash
pip install -r requirements.txt