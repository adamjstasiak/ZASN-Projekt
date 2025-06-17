#  PatchConvNet with Multi-Head Latent Attention (MLA)


This repository contains an implementation of a hybrid model based on the **PatchConvNet** architecture, extended with a **Multi-Head Latent Attention (MLA)** mechanism. The aim of the project was to investigate the impact of the attentional feature proposed by the developers of the DeepSeek model, in an image classification task.


## 📌 Key features

- 🧠 Custom implementation of **Multi-Head Latent Attention** with `latent queries`.
- ⚙️ Optional support for **Low-Rank Key/Value Compression**.
- 🧪 Ablation tests: comparison of MLA with classical `Learned Aggregation`, GAP and GMP
- 📈 Selection of hyperparameters using **Optun** (run from a notebook)