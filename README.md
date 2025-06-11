# 🗳️ Spanish Voter Intent Prediction


## 📌 Overview

This project analyzes voter intent in Spain using a multiclass classification approach. Using survey data that captures attitudes toward nationalism, gender, and economic conditions, the goal is to predict which of six political parties a respondent is likely to support.

---

## 🎯 Objectives

- Preprocess and encode Spanish voter survey data for machine learning  
- Compare multiple classification models including **Random Forest**, **XGBoost**, **KNN**, and **Multinomial Logistic Regression**  
- Evaluate model performance using **accuracy**, **F1-score**, and **precision-recall curves**  
- Visualize class-specific prediction quality

---

## 🛠 Methods & Tools

**Languages & Libraries:**
- Python: `pandas`, `scikit-learn`, `xgboost`, `matplotlib`, `seaborn`
- Jupyter / Google Colab

**Methods:**
- Label encoding & standardization  
- Multiclass classification (6 parties)  
- Confusion matrix + macro/micro-average F1 scores  
- Precision-Recall Curve analysis using `label_binarize()` and `predict_proba()`

---

## 📊 Key Findings

- **Random Forest and XGBoost** performed best across classes, with notable gains in precision for major parties.  
- Multinomial logistic regression yielded interpretable coefficients but had lower accuracy on minority classes.  
- Precision-Recall curves revealed significant performance variation between political groups, highlighting the challenge of class imbalance.

---

## 📌 Future Work

- Tune models using grid/randomized search for improved multiclass accuracy  
- Explore ensemble stacking methods  
- Incorporate demographic and geographic features to enhance prediction

