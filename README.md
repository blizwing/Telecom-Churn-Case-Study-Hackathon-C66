# Telecom Churn Prediction - Hackathon C66

## 📌 Project Overview

This project aims to solve a real-world business problem in the **telecom industry**, where customer churn significantly affects profitability. The solution involves building a machine learning model that can predict customer churn based on historical usage and behavior data.

### 💼 Problem Statement

- The telecom sector faces a **15–25% annual churn rate**.
- Acquiring a new customer costs **5–10 times more** than retaining an existing one.
- Retaining high-value customers is crucial to business success.

**Objective:**  
- Predict which customers are at risk of churning using available features.
- Identify the **key indicators of churn** so that telecom companies can take proactive retention measures.

---

## 🔍 Dataset Description

The dataset contains customer activity over a four-month window:

- **Months 1-2**: "Good phase" – normal behavior
- **Month 3**: "Action phase" – changes in behavior, dissatisfaction begins
- **Month 4**: "Churn phase" – the customer either churns or stays

Files used:

- `train.csv` – Training data with churn labels
- `test.csv` – Test data without labels
- `sample.csv` – Sample submission file
- `data_dictionary.csv` – Column-wise data description

---

## ⚙️ Technologies Used

- **Languages**: Python  
- **Libraries**:
  - `pandas`, `numpy` – Data manipulation
  - `scikit-learn` – Modeling and evaluation
  - `xgboost` – Advanced gradient boosting
  - `matplotlib`, `seaborn` – Visualization

---

## 🔨 Methodology

1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical features
   - Feature scaling and selection
   - Exploratory Data Analysis (EDA)

2. **Model Building**
   - Tried multiple models including:
     - Random Forest
     - XGBoost (final choice)
   - Hyperparameter tuning with `RandomizedSearchCV`

3. **Model Evaluation**
   - Evaluated using metrics such as:
     - Accuracy
     - Precision, Recall, F1 Score
     - ROC-AUC

---

## 📈 Results

The best-performing model was **XGBoost**, tuned to optimize precision and recall balance for churn detection. The pipeline was also made scalable and modular using `Pipeline` and `ColumnTransformer`.

---

## 🚀 How to Run

1. Clone this repository
2. Place the following files in the root directory:
   - `train.csv`
   - `test.csv`
   - `sample.csv`
   - `data_dictionary.csv`
3. Run the Jupyter Notebook:  
   `Praseetha Singh_Pratham Mhatre.ipynb`

---

## 🧠 Authors

- Praseetha Singh  
- Pratham Mhatre

---

## 📌 Notes

This was part of a **Machine Learning Hackathon Challenge (C66)** to simulate a real business scenario in the telecom domain.

