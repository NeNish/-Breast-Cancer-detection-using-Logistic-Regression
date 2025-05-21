# Breast Cancer Detection using Logistic Regression

This project uses Logistic Regression to predict whether a tumor is benign or malignant based on features extracted from breast cancer cell images. The dataset used is the popular **Breast Cancer Wisconsin (Diagnostic) Dataset** from the UCI Machine Learning Repository.

## 📊 Dataset Description

- **Features:** 30 real-valued features computed from digitized images of a breast mass (e.g., radius, texture, perimeter, area, smoothness, etc.)
- **Target:** Binary classification — 
  - `0` for malignant tumors
  - `1` for benign tumors

You can find the dataset [here].  (https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)

## 📌 Objectives

- Load and preprocess the breast cancer dataset
- Split the dataset into training and testing sets
- Train a Logistic Regression model
- Evaluate the model using accuracy, precision, recall, F1-score, and confusion matrix
- Visualize key evaluation metrics

## 🚀 Getting Started

### Prerequisites

Install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
