Credit Card Fraud Detection System
Python
scikit-learn
pandas
numpy

A machine learning system for detecting fraudulent credit card transactions using various classification algorithms.

Table of Contents
Project Overview

Key Features

Installation

Usage

Data Processing

Algorithms Implemented

Performance Metrics

Visualizations

Interactive Demo

Contributing

License

Project Overview
This system analyzes transaction patterns to identify potentially fraudulent credit card activity. It implements multiple machine learning models to detect anomalies with high precision while minimizing false positives.

Key Features
Comprehensive data preprocessing pipeline

Multiple detection algorithms:

Logistic Regression (with polynomial features)

Support Vector Machines (Linear, Polynomial, RBF kernels)

Linear Discriminant Analysis

K-Nearest Neighbors

Detailed performance evaluation

Interactive prediction interface

Installation
Clone the repository:

bash
git clone https://github.com/yourusername/credit-card-fraud-detection.git
cd credit-card-fraud-detection
Install dependencies:

bash
pip install -r requirements.txt
Usage
Run the main analysis notebook:

bash
jupyter notebook Credit_Card_Fraud_Detection.ipynb
Data Processing
The system performs:

Missing value handling

Feature encoding (LabelEncoder for ordinal, OneHotEncoder for nominal)

Numerical feature scaling (StandardScaler)

Dimensionality reduction (PCA)

Algorithms Implemented
Logistic Regression

Basic and polynomial (degree=2) versions

Support Vector Machines

Linear, Polynomial (degrees 2-4), and RBF kernels

Linear Discriminant Analysis

K-Nearest Neighbors (optimized k=20)

Performance Metrics
Model comparison:

Model	Accuracy	Precision	Recall	AUC
Logistic Regression	0.81	0.66	0.54	0.84
SVM (RBF)	0.80	0.65	0.52	0.83
LDA	0.81	0.66	0.53	0.84
KNN (k=20)	0.78	0.62	0.48	0.81
Visualizations
Correlation heatmaps

ROC curves

Decision boundaries

Training progress plots
