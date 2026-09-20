# 🤖 RabTech Academy – Task 02
## ML Problem Framing & Responsible Data Card

> A practical Machine Learning project focused on customer churn prediction, responsible problem framing, data quality, model evaluation, and risk analysis.

---

## 📌 Project Overview

This project is part of the **RabTech Academy Artificial Intelligence & Machine Learning internship track**.

The objective of this task is not only to build a Machine Learning model, but to first understand whether ML is appropriate for the given business problem and to identify potential data, model, and decision-making risks.

Using a small customer churn dataset, the project follows a complete ML problem-framing workflow — from understanding the data and establishing a non-ML baseline to preprocessing, model training, evaluation, and responsible AI documentation.

---

## 🎯 Objectives

- Define the ML prediction problem clearly
- Identify the prediction target and input features
- Inspect data quality and missing values
- Establish a non-ML baseline
- Build a preprocessing pipeline
- Train a Logistic Regression model
- Evaluate model performance
- Analyze false positives and false negatives
- Document potential ML risks and limitations
- Prepare a responsible data card and risk register

---

## 📊 Dataset

The project uses a customer churn dataset containing:

| Feature | Description |
|---|---|
| `customer_id` | Unique customer identifier |
| `tenure_months` | Customer subscription duration |
| `support_tickets` | Number of support tickets |
| `monthly_spend_inr` | Monthly customer spending |
| `last_login_days` | Days since last login |
| `plan_type` | Customer subscription plan |
| `churned` | Target variable indicating churn |

The dataset contains **12 customer records** and **7 columns**.

---

## 🧠 Machine Learning Workflow

```text
Raw Dataset
     ↓
Data Inspection
     ↓
Data Quality Analysis
     ↓
Problem Definition
     ↓
Non-ML Baseline
     ↓
Train/Test Split
     ↓
Data Preprocessing
     ↓
Logistic Regression
     ↓
Model Evaluation
     ↓
Confusion Matrix
     ↓
Risk Analysis
     ↓
Responsible Data Documentation
