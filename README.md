# Credit Card Fraud Analysis





This repository contains a comprehensive analysis and machine learning pipeline for detecting fraudulent credit card transactions. The primary focus of this project is addressing the challenges posed by highly imbalanced datasets typical in financial fraud detection.

## 🚀 Project Overview
The goal of this project is to develop a robust classification model that can accurately identify fraudulent activities. Since legitimate transactions far outnumber fraudulent ones, the project explores various sampling techniques and ensemble methods to improve model reliability and sensitivity.

Key Highlights
Imbalance Management: Implemented Under-sampling, Over-sampling, and SMOTE (Synthetic Minority Over-sampling Technique).

Model Evaluation: Utilized Logistic Regression and Random Forest Classifiers.

Validation Strategy: Applied K-Fold Cross Validation and Hyperparameter Tuning to ensure model generalization.

Performance Metrics: Evaluated results using Confusion Matrices, focusing on Accuracy and Precision.

## 🛠️ Tech Stack
Language: Python

Libraries: * Pandas & NumPy (Data Manipulation)

Scikit-learn (Machine Learning & Cross-Validation)

Imbalanced-learn (Sampling Methods)

Matplotlib & Seaborn (Data Visualization)

Environment: Jupyter Notebook

## 📊 Methodology
1. Handling Imbalanced Data
To prevent the model from ignoring the minority (fraud) class, several strategies were tested:

Under-sampling: Balancing the dataset by reducing the majority class.

Over-sampling: Increasing the representation of the minority class.

SMOTE: Creating synthetic examples of the minority class to improve learning.

Ensemble Techniques: Combining multiple models to reduce variance and improve detection rates.

2. Model Training & Optimization
Algorithms: Logistic Regression and Random Forest.

Tuning: Conducted Hyperparameter Tuning to find the optimal settings for each classifier.

Cross-Validation: Used K-Fold to validate the model's performance across different data subsets.

## 📂 Project Structure
Fraud Analysis.ipynb: The primary notebook containing data cleaning, visualization, sampling, and modeling.

README.md: Documentation of the project.

## ⚙️ Setup and Usage
Clone the repository:

Bash
git clone https://github.com/Ayushi22jain/Credit-card-fraud-analysis.git
Install necessary dependencies:

Bash
pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn
Run the Notebook:
Launch Jupyter Notebook and open Fraud Analysis.ipynb to view the analysis and results.

👤 Author
Ayushi Jain GitHub Profile
