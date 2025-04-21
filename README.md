# 🩺 Diabetes Prediction using Machine Learning

This project applies multiple machine learning models to predict the onset of diabetes using the **Pima Indians Diabetes Dataset**. The goal is to evaluate the performance of different models and investigate how feature scaling, train-test split ratios, and regularization affect model outcomes.

## 📁 Files Included

- `diabetes_prediction.ipynb`: Jupyter Notebook containing all code, visualizations, and analysis.
- `diabetes_prediction_report.pdf`: A formatted report summarizing the experiments and findings.
- `diabetes.csv`: The dataset used in this project (from Kaggle).

## 📌 Dataset Description

- **Source**: [Pima Indians Diabetes Dataset – Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Features**: 
  - Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age
- **Target**:
  - `Outcome` (0 = Non-Diabetic, 1 = Diabetic)

## ✅ Objectives

- Apply and compare **Logistic Regression**, **Decision Tree**, and **Random Forest** classifiers.
- Experiment with:
  - Feature Scaling
  - Train-Test Split Ratios
  - Regularization (L1 and L2 for Logistic Regression)
- Evaluate model performance using:
  - Accuracy
  - Confusion Matrix
  - Precision, Recall, and F1 Score

## 🧪 Summary of Findings

- **Best Performing Model**: Random Forest showed the highest accuracy and best balance between precision and recall.
- **Feature Scaling**: Had minimal effect overall, but slightly improved Decision Tree performance.
- **Train-Test Split Change**: Helped Decision Tree accuracy but negatively impacted Random Forest.
- **Regularization**: Did not significantly affect Logistic Regression. Not applicable to tree-based models.

## 🛠️ Requirements

Install dependencies using pip:


## This Project is done by : Mazen Mohamed Hemdan
