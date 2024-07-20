# Neural-Network-for-Breast-Cancer-Prediction-using-RNA-Seq-Data
This project demonstrates the use of a neural network for predicting cancer types from RNA-Seq data. The model is built using TensorFlow and Keras and trained on a publicly available RNA-Seq dataset. The notebook provides a step-by-step guide on data preprocessing, model building, training, and evaluation.
![image alt](https://github.com/bushrafatimakhan30/Neural-Network-for-Breast-Cancer-Prediction-using-RNA-Seq-Data/blob/b279ec21ecfa3132afbbe9989e2b9ad9e41fa3e1/breastcancerneuralnetwork.png)
# Table of Contents
1. Introduction
2. Dataset
3. Model Architecture
4. Training
5. Evaluation
6. Results
# Introduction
RNA-Seq (RNA sequencing) is a powerful tool for studying the transcriptome of any organism. This project utilizes RNA-Seq data to build a neural network model for cancer type prediction. By training on a labeled dataset, the model learns to distinguish between different types of cancer based on gene expression profiles.

# Dataset
The dataset used in this project is a publicly available RNA-Seq dataset. It contains gene expression data from various cancer types, labeled accordingly. The dataset can be downloaded from [https://archive.ics.uci.edu/dataset/401/gene+expression+cancer+rna+seq].
# Model Architecture
The neural network model is built using TensorFlow and Keras. The architecture consists of multiple dense layers with ReLU activation functions, and an output layer with a softmax activation function for multi-class classification.
# Training
The model is trained using the Adam optimizer and categorical cross-entropy loss function. The training process is monitored using accuracy and loss metrics on both training and validation datasets.
# Evaluation
After training, the model's performance is evaluated on a test dataset. The evaluation metrics include accuracy, precision, recall, and F1-score. The notebook also provides visualizations for the training process and the model's performance.
# Results
The model achieves a high accuracy in predicting cancer types from RNA-Seq data. The training and validation loss and accuracy are plotted to show the model's learning curve.
# Real World Application
Neuural Network technologies demonstrate a high level of efficacy in the diagnosis of cancer. A significant proportion of neural networks exhibit exceptional precision when it comes to categorizing tumours cells. Additionally, it is used in gene structure prediction, protein structure prediction, gene expression data analysis, and almost anywhere where we need classification!
