# 💸 Loan Status Prediction - Machine Learning Project

This project focuses on predicting whether a loan application will be approved or not based on the applicant's personal and financial attributes. It uses data analysis, visualization, and machine learning models to perform binary classification.

---

## 📌 Table of Contents

- [About the Project](#about-the-project)
- [Tech Stack](#tech-stack)
- [Dataset Overview](#dataset-overview)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Preprocessing](#data-preprocessing)
- [Modeling](#modeling)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [How to Run](#how-to-run)
- [Future Work](#future-work)
- [Author](#author)

---

## 🧠 About the Project

The goal is to classify loan applications as either approved (`Yes`) or rejected (`No`). This is a supervised classification problem solved using traditional machine learning techniques such as Logistic Regression, Decision Trees, etc.

---

## 🧰 Tech Stack

- Python 🐍
- Pandas
- NumPy
- Seaborn & Matplotlib (for data visualization)
- Scikit-learn (for modeling)
- Jupyter Notebook

---

## 📊 Dataset Overview

The dataset includes the following features:

- Gender, Marital Status, Education
- Income, Loan Amount, Credit History
- Property Area
- Target: **Loan Status**

---

## 📈 Exploratory Data Analysis

Performed univariate and bivariate analysis using:
- Count plots for categorical features like `loan_status`
- Histograms for numerical features like `income_annum`
- Cross-tabulations (e.g., Education vs Loan Status)

---

## 🧹 Data Preprocessing

- Checked and handled missing values
  - Mode for categorical features
  - Median for numerical features
- Encoding of categorical variables (Label Encoding / OneHotEncoding)
- Feature selection

---

## 🤖 Modeling

Models used:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Accuracy comparison between models

---

## 🧪 Evaluation Metrics

- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)

---

## ✅ Results

- The best model achieved around **[add your best accuracy here]** accuracy.
- The confusion matrix and classification report showed balanced performance on both classes.

---

## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/loan-status-prediction.git
   cd loan-status-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook:
   ```bash
   jupyter notebook
   ```

---

## 🔮 Future Work

- Hyperparameter tuning using GridSearchCV
- Model deployment using Flask/Streamlit
- Real-time predictions on new data
- Better handling of class imbalance if needed



