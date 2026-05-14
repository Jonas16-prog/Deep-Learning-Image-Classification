# Deep Learning Image Classification using PyTorch

## Overview

This project explores the implementation and evaluation of several neural network architectures for image classification using PyTorch.

The objective is to study how different neural network configurations behave in terms of:

- learning capacity,
- generalization,
- overfitting,
- and classification performance.

The project includes:

- linear models,
- shallow neural networks,
- deep neural networks,
- regularization techniques,
- and performance visualization.

A strong emphasis is placed on experimentation, interpretability, and understanding the training dynamics of neural networks.

---

# Project Objectives

The main goals of this project are:

- Build neural network classifiers using PyTorch
- Compare linear and non-linear models
- Analyze the impact of hidden layer size
- Study overfitting behavior
- Evaluate regularization techniques
- Visualize learned weights and model performance
- Understand neural network training dynamics

---

# Technologies Used

- Python
- PyTorch
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

# Project Structure

```bash
deep-learning-image-classification/
│
├── notebooks/
│   └── pytorch_classification_project.ipynb
│
├── images/
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

# Neural Network Architectures

The project explores several architectures:

## 1. Linear Classifier

A simple linear model used as a baseline for comparison.

Topics explored:

- linear separability,
- classification boundaries,
- baseline accuracy.

---

## 2. Shallow Neural Network

A neural network with:

- one hidden layer,
- non-linear activation functions.

This architecture improves the model’s capacity to learn non-linear patterns.

---

## 3. Deep Neural Network

A deeper architecture with multiple hidden layers allowing:

- hierarchical feature extraction,
- more complex representations,
- improved classification performance.

---

# Experiments Conducted

The notebook includes several experiments:

- Hidden layer size optimization
- Comparison between architectures
- Training vs testing accuracy analysis
- Overfitting experiments
- L2 regularization
- Per-class accuracy analysis
- Weight visualization
- Confusion matrix analysis

---

# Overfitting Analysis

One of the main focuses of the project is understanding overfitting.

The experiments demonstrate how:

- increasing model complexity,
- excessive training,
- or insufficient regularization

can lead to poor generalization performance.

The project also explores how L2 regularization helps reduce overfitting.

---

# Model Evaluation

Several evaluation metrics and visualization techniques are used:

- Accuracy
- Confusion Matrix
- Per-class Accuracy
- Training Curves
- Weight Visualization

These analyses help better understand:

- model strengths,
- weaknesses,
- and learning behavior.

---

# Weight Visualization

The learned weights of the neural network are visualized as 28×28 images.

This provides insight into:

- what the model learns,
- important pixel regions,
- and feature extraction behavior.

---

# Confusion Matrix Analysis

Confusion matrices are used to identify:

- frequently confused classes,
- classification weaknesses,
- and difficult patterns in the dataset.

---

# Key Learning Outcomes

This project demonstrates:

- the importance of non-linearity in neural networks,
- how deeper architectures improve representation learning,
- the impact of regularization on generalization,
- and how neural networks progressively learn useful features.

It also provides practical experience with:

- PyTorch training workflows,
- optimization,
- neural network experimentation,
- and model evaluation.

---

# Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/deep-learning-image-classification.git
cd deep-learning-image-classification
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

# Requirements

Example requirements:

```text
torch
torchvision
numpy
matplotlib
scikit-learn
jupyter
```

---

# Possible Future Improvements

Potential extensions include:

- Convolutional Neural Networks (CNNs)
- Dropout regularization
- Batch normalization
- Data augmentation
- Hyperparameter optimization
- GPU acceleration
- Transfer learning

---

# Author

Komi Jonas Amehunke

Student in Mathematics, Computer Science and Numerical Science
University of Geneva

---

# License

This project is intended for academic and educational purposes.
