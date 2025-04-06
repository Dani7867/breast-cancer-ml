# breast-cancer-ml
# Breast Cancer Detection Using Machine Learning

## Overview

This repository contains a machine learning project for classifying breast tumors as benign or malignant using the **Breast Cancer Wisconsin Dataset**. The project implements four classification algorithms—**Logistic Regression**, **Decision Tree**, **Random Forest**, and **Support Vector Machine (SVM)**—and evaluates their performance for a  university course.

### Objectives
- Implement and compare four classification algorithms.
- Evaluate model performance using accuracy, precision, recall, F1-score, and ROC-AUC.
- Identify the best model for breast cancer detection, prioritizing recall for medical diagnostics.

### Dataset
- **Source**: Breast Cancer Wisconsin Dataset (available via `scikit-learn`).
- **Size**: 569 instances, 30 features (e.g., radius, texture, perimeter).
- **Target**: Binary classification (0 = benign, 1 = malignant).

## Project Structure
- **`ML_BreastCancerDetection_C2_36.ipynb`**: Jupyter notebook with the full implementation, including data exploration, preprocessing, model training, and evaluation.
- **`README.md`**: This file.

## Requirements
To run the notebook, install the following Python libraries:
```bash
pip install numpy pandas scikit-learn matplotlib seaborn jupyter
