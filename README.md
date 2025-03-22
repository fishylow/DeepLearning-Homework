# Deep Learning Homework - Group Zerocool
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fishylow/DeepLearning-Homework/blob/main/DeepLearning_Homework.ipynb)
## Team Members
- **Néder Brúnó (NQKZUX)**
- **Jenei Ákos (EBBUE7)**
- **Tasi Gergő (BRY27P)**

## Project Overview
This project applies a **Convolutional Neural Network (CNN)** combined with metadata-driven Dense layers to identify skin cancer from dermoscopic images. We leverage the **ISIC 2024 Challenge** dataset from Kaggle, which provides a wide range of clinical images and metadata for improved diagnosis.
<details>
  <summary>Open for example images, viewer discretion advised</summary>
  <img src="https://github.com/user-attachments/assets/aa4c67a3-5a5d-431a-8871-3657dd1e3828" alt="DL results" size="50%">

</details>

**Key Features:**
- **Hybrid Architecture:** CNN for image feature extraction + Dense layers for metadata.
- **Data Preprocessing:** One-hot encoding of lesion location, age imputation, class balancing, and image augmentation.
- **Hyperparameter Tuning:** Automated tuning of CNN and Dense layer configurations using Keras Tuner.

**Dataset:** [ISIC 2024 Challenge](https://www.kaggle.com/competitions/isic-2024-challenge)

## Repository Structure
- **DeepLearning-Homework.ipynb**: All the code (data loading, preprocessing, model building, training, and evaluation) in one Jupyter Notebook.

## Running the Project
1. Configure parameters in the first cells of the notebook.
2. Run all cells to train and evaluate the model.

## Results
We've achieved an accuracy of over 80% with the current iteration of the project.
<img src="https://github.com/user-attachments/assets/1e9cc232-d8fd-465c-be87-2e94f837d030" alt="DL results" width="50%" height="50%">
