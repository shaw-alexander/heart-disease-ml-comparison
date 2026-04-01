# Heart Disease Prediction (kNN vs Decision Tree)

## Overview
This project compares two supervised machine learning algorithms, k-Nearest Neighbours and Decision Trees, for predicting heart disease.

## Problem Type
Multiclass classification

## Dataset
- UCI Heart Disease dataset
- 303 samples with 13 medical features

## Models
- k-Nearest Neighbours (implemented from scratch)
- Decision Tree (scikit-learn)

## Methodology
- Train-test split used for evaluation
- Model complexity varied:
  - k value for kNN
  - max depth for Decision Tree
- Accuracy used as evaluation metric

## Results
- kNN achieved highest accuracy (~70%) at k=2
- Decision Tree achieved ~63% at depth=3
- Both models performed best at low complexity

## Key Insight
Increasing model complexity did not improve performance and led to overfitting, demonstrating the bias–variance trade-off.

## Limitations
- Single train-test split used
- Cross-validation could improve reliability

## Files
- heart-disease-classification.ipynb → full implementation
- report.pdf → detailed report
