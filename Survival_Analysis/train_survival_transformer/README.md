# 🧠 Transformer-Based Deep Survival Analysis

A **PyTorch implementation** of the paper  
[**Transformer-Based Deep Survival Analysis**](http://proceedings.mlr.press/v146/hu21a/hu21a.pdf)  
by *Hu et al., Proceedings of Machine Learning Research (PMLR), 2021.*

---

## 📘 Overview
This repository implements a **Transformer-based framework for survival analysis**, leveraging self-attention to model complex temporal dependencies and handle censored data efficiently.

The model predicts **survival probabilities over time** and supports evaluation through key survival metrics such as the **Concordance Index (C-index)** and **Mean Absolute Error (MAE)**.

---

## ⚙️ Requirements
The implementation was tested under the following environment:

- **Python** ≥ 3.6  
- **PyTorch** ≥ 1.1.0  
- **CUDA-compatible GPU** (e.g., NVIDIA TITAN Xp)

Install dependencies with:
```bash
pip install -r requirements.txt
