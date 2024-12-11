# Deep Learning Homework - Group Zerocool

## Team Members
- **Néder Brúnó (NQKZUX)**
- **Jenei Ákos (EBBUE7)**
- **Tasi Gergő (BRY27P)**

## Project Overview
This project applies a **Convolutional Neural Network (CNN)** combined with metadata-driven Dense layers to identify skin cancer from dermoscopic images. We leverage the **ISIC 2024 Challenge** dataset from Kaggle, which provides a wide range of clinical images and metadata for improved diagnosis.

**Key Features:**
- **Hybrid Architecture:** CNN for image feature extraction + Dense layers for metadata.
- **Data Preprocessing:** One-hot encoding of lesion location, age imputation, class balancing, and image augmentation.
- **Hyperparameter Tuning:** Automated tuning of CNN and Dense layer configurations using Keras Tuner.

**Dataset:** [ISIC 2024 Challenge](https://www.kaggle.com/competitions/isic-2024-challenge)

## Repository Structure
- **DeepLearning-Homework.ipynb**: All code (data loading, preprocessing, model building, training, and evaluation) in one Jupyter Notebook.

## Running the Project
1. Configure parameters in the first cells of the notebook.
2. Run all cells to train and evaluate the model.

**Try it in Colab:**  
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fishylow/DeepLearning-Homework/blob/main/DeepLearning_Homework.ipynb)
