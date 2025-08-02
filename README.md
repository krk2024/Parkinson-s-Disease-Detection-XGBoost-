# Parkinson's Disease Detection using XGBoost

This project implements a machine learning-based detection system for Parkinson’s Disease using voice measurements. It leverages the XGBoost classifier along with data preprocessing and feature importance analysis to build an accurate and interpretable model.

## Features

- Voice-based biomedical feature analysis
- XGBoost model with hyperparameter tuning via GridSearchCV
- Accuracy and classification report evaluation
- Feature importance extraction
- Model export for future deployment

## Dataset

- Source: UCI Machine Learning Repository - Parkinson’s Dataset
- Features: 22 voice-related measurements (e.g., MDVP:Fo(Hz), Jitter, Shimmer)
- Target column: `status` (1 indicates Parkinson’s, 0 indicates healthy)

## Technologies Used

- XGBoost
- scikit-learn
- pandas
- numpy
- matplotlib, seaborn

## Installation

Install the required packages using pip:

```bash
pip install xgboost scikit-learn pandas numpy matplotlib seaborn
