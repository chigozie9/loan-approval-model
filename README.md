# Loan Approval Prediction Model

This project uses machine learning techniques to predict whether a loan application will be approved based on applicant information such as income, credit history, and loan amount. The analysis is conducted using R and includes both logistic regression and k-nearest neighbors (k-NN) models.

---

## 📁 Files

- `loan-approval.qmd`: Main analysis notebook (written in Quarto/R Markdown)
- `loan_data.csv`: Dataset used for training and testing the models

---

## 🧰 Tools & Libraries Used

- R (tidyverse, caret, dplyr)
- Quarto (.qmd)
- Machine Learning algorithms: Logistic Regression, k-Nearest Neighbors (k-NN)

---

## 🔍 Analysis Steps

1. **Data Preprocessing**
   - Handled missing values
   - Converted categorical variables to factors
   - Created a binary outcome variable (`Loan_Status`)

2. **Exploratory Data Analysis**
   - Summary statistics
   - Structure inspection
   - Null value checks

3. **Modeling**
   - Train-test split (70/30)
   - Logistic regression model using `glm()`
   - k-NN model using `caret::train()`
   - Evaluation via confusion matrix

4. **Prediction**
   - Final prediction was generated for a new applicant with specific attributes using the selected model

---

## ✅ Results

- Both models were trained and evaluated.
- Accuracy scores and confusion matrices were used to compare performance.
- The better-performing model was selected to predict loan approval for a test applicant.

---

## 📄 Notebook Preview

You can view the full notebook here: [`loan-approval.qmd`](loan-approval.qmd)

---

## 📌 Summary

This project demonstrates how basic machine learning models can be applied to real-world structured data for binary classification. It shows how to preprocess data, train/evaluate models, and make informed predictions.

