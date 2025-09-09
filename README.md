# Autism Prediction using Machine Learning

## Overview
This project predicts autism likelihood using machine learning models on a Kaggle dataset. It covers data preprocessing, class imbalance handling, model training, hyperparameter tuning, and evaluation.

## Dataset
- Source: [Autism Diagnosis Dataset (Kaggle)](https://www.kaggle.com/competitions/autismdiagnosis/data)
- Includes demographic and behavioral features relevant for autism prediction.

## Methodology
- Handled missing values and outliers
- Balanced classes with SMOTE
- Performed feature correlation analysis
- Trained models: Random Forest, XGBoost, Decision Tree
- Hyperparameter tuning with RandomizedSearchCV + cross-validation
- Model evaluation using confusion matrix and classification metrics

## Results
- Best model: Random Forest
- Accuracy: 83%
- Recall: 69.44%
- Precision: 60.9%
## How to Run
```bash
git clone https://github.com/mishka832/Autism-Prediction.git
cd Autism-Prediction
pip install -r requirements.txt
