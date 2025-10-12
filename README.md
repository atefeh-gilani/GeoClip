# GeoClip: Geometry-Aware Clipping for Differentially Private SGD
This repository contains a Python implementation of **GeoClip**, a geometry-aware clipping mechanism for Differentially Private Stochastic Gradient Descent (DP-SGD). GeoClip adaptively scales and transforms gradients using a learned geometry matrix to improve privacy-utility trade-offs.

---

### Repository Structure

| File | Description |
|------|--------------|
| **`geoclip_demo.ipynb`** | Jupyter notebook demonstrating how to train a simple model (classification or regression) using GeoClip. Includes data generation, model setup, and training plots. |
| **`geoclip.py`** | Core implementation of the GeoClip algorithm with full-rank covariance updates. Suitable for experiments on moderate-dimensional models. |
| **`geoclip_rank_k.py`** | Efficient low-rank (rank-k) variant of GeoClip using online PCA updates for scalable training in high-dimensional settings. |

---

### Citation

If you use this repository, please cite the following work:

> A. Gilani, N. Tasnim, O. Kosut, and L. Sankar,  
> “**GeoClip: Geometry-Aware Clipping for Differentially Private SGD**,”  
> *NeurIPS 2025.*

---

### License

This project is released under the **MIT License**.  
See the `LICENSE` file for details.

---
