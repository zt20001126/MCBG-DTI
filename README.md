# MCBG-DTI: Multi-Channel Graph-Based Deep Learning Framework for Drug–Target Interaction Prediction

## Overview
Welcome to the MCBG-DTI project! MCBG-DTI is a novel deep learning framework for accurate prediction of Drug–Target Interactions (DTIs). The model integrates a **Multi-Channel Graph Isomorphism Network (MCGIN)** to extract both local and global structural features of drug molecules, a **hybrid protein encoding module** that combines **1D convolution**, **Squeeze-and-Excitation (SE) blocks**, and **convolutional self-attention** to capture both local biochemical patterns and long-range dependencies in protein sequences, and a **Bidirectional Gated Fusion Attention (BGFA)** module to deeply model interactions between drug and protein representations. 

This architecture is designed to address several key challenges in DTI prediction, including the difficulty of distinguishing structurally similar drug subgraphs, capturing long-range sequence dependencies in proteins, and enhancing the quality of drug–target feature integration. Experimental results on multiple benchmark datasets demonstrate that MCBG-DTI outperforms existing state-of-the-art models in terms of prediction accuracy. Furthermore, case studies and molecular docking experiments further confirm the reliability and biological relevance of the predicted interactions.

## Current Status
The MCBG-DTI codebase is currently being finalized. We are working to ensure the implementation is clean, well-documented, and easy to use. Thank you for your patience as we prepare for a stable public release.

## Upcoming Release
We are committed to open-source principles and plan to release the complete MCBG-DTI framework soon. The release will include model code, detailed documentation, usage guidelines, and example datasets to help researchers and developers reproduce and build upon our work. Stay tuned for updates—we will notify the community when the code becomes available.

## Acknowledgments
We sincerely thank the research community for their interest and support. Your encouragement drives us to continue advancing DTI prediction methodologies. We appreciate your understanding as we work to deliver a robust and accessible implementation of MCBG-DTI.
