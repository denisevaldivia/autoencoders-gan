# References and Learning Resources

## Introduction

This document lists the **external references** used to support the theoretical understanding and practical implementation of the autoencoders developed in this project. The references are organized by **type of autoencoder** and include **articles, research papers (PDFs), videos, tutorials, and code repositories**.

This file serves two main purposes:
- To guide readers who want to **learn more about autoencoders**
- To document the materials that influenced the **design decisions and implementations** in this project

---
## 1. General Autoencoders (Vanilla Autoencoders)

These references were used to understand the basic principles of autoencoders, encoder–decoder architectures, and representation learning.

### Articles / Tutorials
- **Medium (Piyush Kashyap)** – *A Comprehensive Guide to Autoencoders*: https://medium.com/@piyushkashyap045/a-comprehensive-guide-to-autoencoders-8b18b58c2ea6

### Videos
- **YouTube** – *Autoencoders Explained*: https://www.youtube.com/watch?v=hZ4a4NgM3u0

### Academic Papers (PDF)
- **ABCs 2018 Conference** – *Autoencoders: An Overview* (Gedeon et al., 2018): https://users.cecs.anu.edu.au/~Tom.Gedeon/conf/ABCs2018/paper/ABCs2018_paper_58.pdf

---

## 2. Denoising Autoencoders

These sources focus on robustness, noise injection, and reconstruction of clean data from corrupted inputs.

### Documentation / Tutorials
- **Keras Blog** – *Building Autoencoders in Keras*: https://blog.keras.io/building-autoencoders-in-keras.html
- **Medium (Laveesh Chanchlani)** – *Image Denoising and Deblurring Using Autoencoders*: https://medium.com/@laveeshchanchlani05/image-denoising-and-deblurring-using-autoencoders-db51fae5596a

### Academic Papers (PDF)
- **ICML 2008** – *Extracting and Composing Robust Features with Denoising Autoencoders* (Vincent et al.): https://www.cs.toronto.edu/~larocheh/publications/icml-2008-denoising-autoencoders.pdf

---

## 3. Variational Autoencoders (VAE)

These references were used to understand probabilistic latent variable models, KL divergence, the reparameterization trick, and image generation with VAEs.

### Academic Papers (PDF)
- **Machine learning for data science handbook: data mining and knowledge discovery handbook, 353-374.** - *(Bank, D., Koenigstein, N., & Giryes, R., 2023).*: https://arxiv.org/pdf/2003.05991 

### Documentation / Tutorials
- **Keras Official Examples** – *Variational Autoencoder*: https://keras.io/examples/generative/vae/
- **Drops of AI** – *Variational Autoencoders and Image Generation with Keras*: https://dropsofai.com/variational-autoencoders-and-image-generation-with-keras/
- **Paperspace Blog** – *How to Build a Variational Autoencoder with Keras*: https://blog.paperspace.com/how-to-build-variational-autoencoder-keras/

### Community Q&A
- **Stack Overflow** – *Generating New Data Using VAE in Keras*: https://stackoverflow.com/questions/75185209/generating-new-data-using-vae-in-keras

### Code Repositories
- **GitHub (Jay Won Chung)** – *Variational Autoencoder Implementation*: https://github.com/jaywonchung/Learning-ML/tree/master/Implementations/Variational-Autoencoder

### Videos
- **YouTube** – *Variational Autoencoders Explained*: https://www.youtube.com/watch?v=FQBXon6CITk

---

## 4. Dataset Reference

### Dataset Source
- **Kaggle** – *Fashion Images Dataset*: https://www.kaggle.com/datasets/vikashrajluhaniwal/fashion-images

---

## Notes

- All implementations in this project are **original**, but inspired by the references listed above.
- Code snippets and architectural ideas were adapted and extended to fit the specific dataset and experimental goals.
- This document is intended for **academic transparency and reproducibility**.