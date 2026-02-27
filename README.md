# 📊 Telecom Customer Churn Prediction

## 📌 Project Overview

Customer churn is a major challenge in the telecom industry. Losing customers directly impacts revenue and business growth. This project uses Machine Learning techniques to predict whether a customer will leave the company (churn) or stay.

The goal is to help telecom companies identify customers at risk and take preventive actions to improve retention.

---

## 🎯 Problem Statement

Build a classification model to predict customer churn:

- **1 → Customer Left (Churned)**
- **0 → Customer Stayed**

---

## 📂 Dataset Description

The dataset contains telecom customer details, subscription information, usage behavior, and service history.

### 🔎 Feature Explanation
    
| Column Name                    | Description |
|--------------------------------|----------------------------------------------------|
| `id`                           | Unique customer ID number                          |
| `is_tv_subscriber`             | 1 = Has TV subscription, 0 = No                    |
| `is_movie_package_subscriber`  | 1 = Has movie package subscription, 0 = No         |
| `subscription_age`             | Duration customer has stayed (in years)            |
| `bill_avg`                     | Average monthly bill amount                        |
| `reamining_contract`           | Remaining contract time                            |
| `service_failure_count`        | Number of service failures experienced             |
| `download_avg`                 | Average download usage                             |
| `upload_avg`                   | Average upload usage                               |
| `download_over_limit`          | Number of times customer exceeded download limit   |
| `churn`                        | Target  → 1 = Customer left, 0 = Customer stayed   |

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib    
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🔄 Project Workflow

### 1️⃣ Data Preprocessing
- Removed unnecessary columns (`id`)
- Handled missing values in `reamining_contract`
- Feature scaling using **StandardScaler**
- Train-test split

### 2️⃣ Model Building
- Applied Machine Learning classification algorithm
- Trained model using scaled training data

### 3️⃣ Model Evaluation
- Accuracy Score
- Confusion Matrix
- Model predictions on test data

---

## 📈 Model Performance

- Model trained on scaled features
- Evaluated using test dataset
- Performance depends on data distribution and class balance

---
