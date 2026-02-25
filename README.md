# **Autoencoders for Product Image Generation**

## **• Project Overview**

This project explores the use of **autoencoders** as *generative deep learning models* applied to fashion product images for e-commerce applications. We implement and compare **vanilla autoencoders**, **denoising autoencoders**, and **variational autoencoders (VAEs)** to study their reconstruction capabilities, latent representations, and generative potential.

---

## **• Objectives**

### General Objective
To understand the basic characteristics of autoencoders and their application in generative deep learning.

### Specific Objectives
- Implement a **vanilla autoencoder** for image reconstruction.
- Implement a **denoising autoencoder** for noise removal in product images.
- Implement a **convolutional variational autoencoder (VAE)** for image generation.
- Explore potential applications of autoencoders in e-commerce scenarios.

---

## **• Motivation**
Studies indicate that more than **63% of consumers** consider product images more important than textual descriptions when making purchasing decisions. Therefore, image quality plays a critical role in user engagement and conversion rates on e-commerce platforms, making this dataset suitable for autoencoder-based analysis.

---

## **• Dataset Description**
The dataset consists of **over 2,900 product images** belonging to the **Apparel** and **Footwear** categories, subdivided by gender:

- Apparel: Boys, Girls  
- Footwear: Men, Women  

Each image is associated with a unique **ProductId**, and additional metadata is provided in the `fashion.csv` file, including:
- Product title  
- Description  
- Category  
- Gender  

---

## **• Project Organization**

```
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks
│
├── pyproject.toml     <- Project configuration file with package metadata for 
│                         autoencoders_gan and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
└── autoencoders_gan   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes autoencoders_gan a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations
```

--------
