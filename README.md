# AI-Driven-Diagnosis-of-Multiclass-Parkinson-Disease


This project presents a comprehensive pipeline for classifying Parkinson’s disease using patient questionnaire data. The study explores advanced preprocessing, feature selection, class imbalance handling, and evaluation of 15 machine learning models with explainability tools such as SHAP and LIME.

---

## 📊 Overview

The proposed architecture includes:
- **Data Collection & Cleaning**
- **Feature Selection & Dimensionality Reduction**
- **Handling Class Imbalance with SMOTE**
- **Model Training and Cross-Validation**
- **Explainability using SHAP & LIME**

---

## 🧾 Dataset

The dataset was originally collected in JSON format and later converted to CSV. It includes:
- Demographic features: age, gender, height, weight, family history
- 30 binary responses on Parkinson’s Disease Non-Motor Symptoms (PDNMS), based on the official questionnaire by the International Parkinson and Movement Disorder Society ([Reference](https://www.movementdisorders.org/))

🧮 **Instances:** 469  
📌 **Features:** 51

---

## 🧹 Data Preprocessing

- Handled missing/NaN values
- Created a data quality report for statistical understanding
- Converted JSON to structured CSV for modeling

---

## ⚖️ Data Balancing (SMOTE)

Used **SMOTE** to address class imbalances:
- PD vs HC: 276 vs 79  
- PD vs Other Disorders: 276 vs 114  
- PD vs HC vs Other: 276 vs 79 vs 114

SMOTE interpolates between minority samples to generate synthetic data and balance the dataset.

---

## 🔍 Feature Selection

Techniques used:
- **ANOVA**, **Recursive Feature Elimination (RFE)**, and **Sequential Feature Selection**
- Dimensionality reduction using **PCA**, **ICA**, and **T-SNE**
- Applied 10-fold cross-validation for performance robustness

---

## 🤖 Machine Learning Models

A total of **15 models** were evaluated:
- KNN, Naive Bayes, Logistic Regression, Decision Tree, Random Forest
- Gradient Boosting, XGBoost, AdaBoost, Extra Trees, LightGBM
- SVM, Multi-Layer Perceptron (MLP), CatBoost, Stacking, Bagging

Model training included:
- SMOTE oversampling
- Cross-validation
- Hyperparameter tuning

---

## 📈 Evaluation Metrics

Evaluated with:
- **Accuracy**
- **Precision, Recall, F1-Score (Macro & Weighted)**
- **Confusion Matrix**
- **ROC AUC Score**

---

## 🧠 Explainable AI

To interpret model predictions:
- **LIME**: Local interpretable model-agnostic explanations
- **SHAP**: SHapley Additive exPlanations for global and local interpretability

---

## 🏆 Key Results

### PD vs HC:
- **Best Model:** CatBoost (F1-score: 0.95 after SMOTE)
- PCA and ICA (top 5 components) improved performance

### PD vs Other:
- **Top Models:** Gradient Boosting, SVM, CatBoost (F1-score: 0.82 with ANOVA + SMOTE)

### PD vs HC vs Other:
- **Best Performance:** Logistic Regression with Backward Elimination and SMOTE (Accuracy: 69%)

📊 See [results/](./results/) for all metrics and confusion matrices.

---



