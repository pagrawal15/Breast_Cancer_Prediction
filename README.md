# 🩺 Breast Cancer Diagnosis Prediction

This project predicts whether a tumor is **benign** or **malignant** using the [Wisconsin Breast Cancer Dataset](https://www.kaggle.com/datasets/wasiqaliyasir/breast-cancer-dataset).  
It showcases the end-to-end data science workflow: data exploration, feature selection, machine learning, and model interpretation.

---

## 🚀 Project Highlights

- **Full EDA:** Statistical summaries, correlation analysis, and rich visualizations (histograms, pairplots).
- **Feature Selection:** Used VIF (Variance Inflation Factor) and correlation with the target to avoid multicollinearity and select the most predictive features.
- **Modeling:** Compared Logistic Regression, Random Forest, and XGBoost classifiers.
- **Performance:** Achieved **ROC-AUC > 0.98** on the test set.
- **Interpretability:** Visualized confusion matrices, ROC curves, and feature importances to explain model decisions.

---

## 📊 Data Overview

- **Source:** [Kaggle - Breast Cancer Dataset](https://www.kaggle.com/datasets/wasiqaliyasir/breast-cancer-dataset)
- **Features:** 30 numeric predictors (cell characteristics), diagnosis label (`B` = benign, `M` = malignant).
- **Objective:** Binary classification (malignant vs. benign tumor).

---

## 🛠️ Workflow Summary

1. **Data Cleaning:** Checked for missing values, encoded diagnosis labels.
2. **EDA:** Explored distributions and relationships between features and target.
3. **Feature Engineering:** Removed highly collinear features, selected top predictors using VIF and correlation.
4. **Model Building:** Trained and compared multiple classifiers.
5. **Evaluation:** Used accuracy, precision, recall, F1-score, ROC-AUC, confusion matrix, and ROC curve.
6. **Interpretation:** Plotted feature importance for tree-based models.

---

## 📈 Results

- **Best Model:** XGBoost, with ROC-AUC of 0.98.
- **Key Features:** `perimeter_mean`, `concavity_mean`, `compactness_mean`, `texture_mean`, `smoothness_mean`.
- **Model explains** which features are most important for predicting malignancy, supporting clinical insights.

![ROC Curve Example](link-to-your-roc-curve-image)

---

## 📂 Files

- `breast_cancer_prediction.ipynb` – Full code and analysis notebook
- `README.md` – This file

---

## 🎯 Takeaways

- Combining robust EDA with thoughtful feature selection leads to highly accurate and interpretable medical prediction models.
- Model comparison and visual interpretation are critical for trustworthy, real-world solutions.
