# Breast Cancer Recurrence Prediction with Machine Learning

This project uses classification models to predict the recurrence of breast cancer based on patient and tumor characteristics. The pipeline includes preprocessing, visualization, SMOTE handling for imbalance, multiple classifiers, evaluation metrics, and explainability.

---

## Objective

Predict whether a breast cancer patient will experience a recurrence or not, using interpretable and ensemble machine learning models.

---

## Dataset

- **Acknowlegment** Kaggle for Dataset
- **Source**: [UCI Breast Cancer Dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer)
- **Samples**: 286
- **Features**: Age, tumor size, menopause status, node caps, etc.
- **Target**: `Class` – `no-recurrence-events` or `recurrence-events`

---

## Workflow

### Data Understanding & Visualization
- Class distribution
- Feature-target relationship plots

### Preprocessing
- Label encoding
- One-hot encoding for categorical features

### Modeling & Evaluation
- Random Forest (with and without SMOTE)
- ROC Curve and AUC Score
- Feature importance plot
- Classification metrics (accuracy, F1, confusion matrix)

### Stacking Ensemble (Optional)
- Combines Random Forest + SVC + Logistic Regression

---
