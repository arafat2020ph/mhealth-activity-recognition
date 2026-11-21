# Human Activity Recognition using Machine Learning

## Project Overview
This project uses sensor data (Accelerometer, Gyroscope, Magnetometer) to predict human activities. The dataset used is `mhealth.csv`.

## Problem Statement
The goal is to classify different human activities (0-12) based on time-series sensor data. One of the classes (Activity 0) was underperforming, so extensive error analysis, feature engineering, and model comparison were performed to improve its performance.

## Models Compared
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Random Forest (Best Model)

## Key Results
- **Best Model**: Random Forest
- **Accuracy**: 96%
- **Macro F1-Score**: 0.96
- **Improvement**: Activity 0's F1-score improved from 0.77 to 0.80 after adding new magnitude and variance features.

## Techniques Used
- Data Cleaning & Preprocessing
- Feature Engineering (Magnitude, Standard Deviation)
- Model Evaluation (Precision, Recall, F1-Score, Confusion Matrix)
- Hyperparameter Tuning & Cross-Validation