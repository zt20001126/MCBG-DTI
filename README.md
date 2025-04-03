# MCBG-DTI: Multi-Channel Graph-Based Deep Learning Framework for Drug–Target Interaction Prediction

![License](https://img.shields.io/badge/license-MIT-green.svg)
![Python](https://img.shields.io/badge/python-3.8%2B-blue.svg)
![Status](https://img.shields.io/badge/status-Coming%20Soon-orange.svg)
![Paper](https://img.shields.io/badge/paper-MCBG--DTI-lightgrey)
![Model Type](https://img.shields.io/badge/model-GNN%2BAttention-blueviolet)

## 🧬 Overview
**MCBG-DTI** is a novel deep learning framework for accurate prediction of Drug–Target Interactions (DTIs). It integrates:

- 🧪 A **Multi-Channel Graph Isomorphism Network (MCGIN)** for modeling both local and global topological structures of drug molecules.
- 🧬 A protein feature extractor combining **1D convolution**, **Squeeze-and-Excitation (SE) blocks**, and **convolutional self-attention**, enabling the modeling of local biochemical patterns and long-range dependencies.
- 🔁 A **Bidirectional Gated Fusion Attention (BGFA)** module for deep interaction modeling between drug and protein features.

MCBG-DTI effectively addresses the limitations of traditional DTI models in distinguishing structurally similar subgraphs, capturing long-range dependencies in protein sequences, and integrating multimodal biological features. Experiments on benchmark datasets show superior predictive performance, and case studies with molecular docking further validate the model's biological relevance.

---

## 🚧 Current Status
The codebase is currently being finalized. We're working on cleaning the implementation, writing documentation, and preparing it for release. Thanks for your patience!

---

## 🚀 Upcoming Release
We are committed to open-source principles and will release:

- ✅ Full source code
- ✅ Example datasets
- ✅ Step-by-step usage instructions
- ✅ Pre-trained model checkpoints (optional)

📌 Stay tuned! We’ll notify the community when the code is ready.

---

## 🙏 Acknowledgments
We appreciate the interest and support from the research community. Your encouragement motivates us to keep pushing the boundaries of DTI prediction research. Thank you for your understanding as we work to bring you a stable, user-friendly release of **MCBG-DTI**.

---

## 📎 Citation (Coming Soon)
If you find this work useful, please consider citing our paper once it's officially published.
