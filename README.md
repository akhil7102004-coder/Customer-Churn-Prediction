# Customer Churn Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue?logo=pandas)
![License](https://img.shields.io/badge/License-MIT-green)

## Project Overview

Customer churn is one of the major challenges faced by subscription-based businesses. This project develops a Machine Learning model to predict whether a customer is likely to leave a telecom service based on demographic information, account details, and service usage.

The project follows a complete Machine Learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, hyperparameter tuning, model evaluation, and testing on an unseen dataset.

---

## Problem Statement

The objective is to build a predictive model that accurately identifies customers who are likely to churn, enabling businesses to take proactive retention measures.

---

## Dataset

The project uses:

- Training_data.csv
- Testing_data.csv

Target Variable:

- **Churn**
  - 0 → Customer Stayed
  - 1 → Customer Left

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Exploratory Data Analysis

Performed:

- Dataset inspection
- Missing value handling
- Duplicate checking
- Summary statistics
- Target distribution analysis
- Boxplots
- Histograms
- Correlation Heatmap
- Categorical feature analysis

---

## Feature Engineering

The following preprocessing steps were performed:

- Missing value imputation
- Label Encoding
- Feature Scaling
- Customer Lifetime Value (CLV) Feature
- Interaction Features
- Feature Importance Analysis

---

## Machine Learning Models

The following models were trained and evaluated:

- Logistic Regression
- Balanced Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Tuned Random Forest (GridSearchCV)

---

## Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

## Final Results

| Model | Accuracy |
|--------|----------|
| Logistic Regression | **80.57%** |
| Random Forest | 79.41% |
| Tuned Random Forest | 76.57% |
| Balanced Logistic Regression | 75.60% |
| Decision Tree | 73.11% |

### Final Testing Accuracy

**81.48%**

The Logistic Regression model achieved the best overall performance and generalized well on the unseen testing dataset.

---

## Project Structure

```
Customer-Churn-Prediction/
│
├── Customer_Churn_Prediction.ipynb
├── Training_data.csv
├── Testing_data.csv
├── README.md
├── LICENSE
└── .gitignore
```

---

## How to Run

1. Clone the repository

```bash
git clone https://github.com/akhil7102004-coder/Customer-Churn-Prediction.git
```

2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Open

```
Customer_Churn_Prediction.ipynb
```

4. Run all cells.

---

## Future Improvements

- Deploy the model using Streamlit or Flask
- Experiment with XGBoost and LightGBM
- Perform Cross Validation
- Improve Feature Engineering
- Develop an interactive dashboard

---

## Author

**Akhil A**

B.Tech Computer Science & Engineering

Python | SQL | Machine Learning | Data Analytics

---

## License

This project is licensed under the MIT License.
