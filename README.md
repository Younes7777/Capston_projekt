<div align="center">

# 🚗 Loan Default Prediction

### Data Science Capstone Project · neuefische Bootcamp (2020)

![Python](https://img.shields.io/badge/Python-Data%20Science-3776AB?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Classification-1F6FEB)
![Status](https://img.shields.io/badge/Project-Capstone-2EA44F)

**Exploratory analysis, data preparation and predictive modeling of vehicle loan defaults.**

[📓 Open the Jupyter Notebook](Loan%20Default%20Prediction.ipynb)

</div>

---

## 🎯 Project Overview

This project explores whether a borrower is likely to default on a vehicle loan. It was developed as a capstone project during the **540-hour Data Science bootcamp at neuefische** in 2020.

The notebook covers the workflow from inspecting and cleaning raw data to exploratory analysis, classification models, hyperparameter tuning and model evaluation.

## 📊 Dataset

The analysis uses the **L&T Vehicle Loan Default Prediction** dataset. The notebook describes a dataset with **345,546 rows and 42 columns**, including the target variable indicating loan default.

The project refers to the following source files:

- `train.csv`
- `test.csv`
- `data_dictionary.csv`

> **Reproducibility note:** These input files are referenced by the notebook and are not included in this README. To rerun the notebook, you need the dataset and compatible Python dependencies.

## 🧹 Data Preparation & Feature Engineering

- Inspected missing values and handled missing employment-type information
- Transformed date and categorical fields
- Derived features from account age and credit history
- Combined information from primary and secondary credit accounts
- Removed identifiers and other fields not intended for modeling
- Prepared numerical and categorical variables for machine learning

## 🔎 Exploratory Data Analysis

- Examined distributions of categorical and continuous variables
- Explored relationships between borrower characteristics and loan defaults
- Used univariate and multivariate visualizations to understand the data

## 🤖 Machine Learning

The notebook explores and compares multiple classification approaches:

| Model | Focus |
| --- | --- |
| Logistic Regression | Interpretable classification baseline |
| Decision Tree | Tree-based classification and tuning |
| Random Forest | Ensemble classification and tuning |
| Gradient Boosting / XGBoost | Boosted trees and parameter optimization |
| Support Vector Machine (SVM) | Margin-based classification |
| CatBoost | Gradient boosting with additional model analysis |

## 📈 Model Evaluation

The notebook includes model evaluation and comparison, hyperparameter optimization, cross-validation, and model explainability. The precise metrics and results are documented in the notebook rather than summarized here without context.

## 🛠️ Tech Stack

**Language:** Python  
**Environment:** Jupyter Notebook  
**Data analysis:** pandas, NumPy  
**Visualization:** Matplotlib, seaborn  
**Machine learning:** scikit-learn, XGBoost, CatBoost

## 📂 Project Files

- [📓 **Loan Default Prediction.ipynb**](Loan%20Default%20Prediction.ipynb) — complete analysis and modeling notebook

## 🎓 Background

Created as the capstone project for the **Data Science Bootcamp at neuefische GmbH (May–August 2020)**.

---

<div align="center">

*Data cleaning · Statistical exploration · Predictive modeling*

</div>
