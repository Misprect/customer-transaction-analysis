---
## Customer Transaction Prediction using Machine Learning

### Project Overview

This project focuses on predicting whether a customer will make a transaction based on anonymized numerical features. The goal is to build robust classification models and evaluate their performance using industry-standard metrics.

The project implements **feature engineering, imbalance handling, model training, hyperparameter tuning, and model explainability** techniques.
---

### Models Used

- Logistic Regression (baseline)
- Random Forest Classifier
- LightGBM (Gradient Boosting)

---

### Techniques & Concepts

- Exploratory Data Analysis (EDA)
- Feature correlation analysis
- Handling class imbalance using **SMOTE**
- Model evaluation using **ROC-AUC**
- Hyperparameter tuning
- Early stopping in LightGBM
- Feature importance analysis
- Partial Dependence Plots (PDP)

---

### Project Structure

```
├── customer_transaction_predict.ipynb
├── train.csv
├── test.csv
├── README.md
├── .gitignore
```

---

### Evaluation Metrics

- ROC-AUC Score
- Confusion Matrix
- Classification Report
- ROC Curve Visualization

---

### Results

- LightGBM achieved the **best performance**
- Validation ROC-AUC ≈ **0.89**
- Model generalized well with early stopping

---

### Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- LightGBM
- Matplotlib, Seaborn
- PDPbox
- Imbalanced-learn (SMOTE)

---

### How to Run

```bash
pip install -r requirements.txt
jupyter notebook customer_transaction_predict.ipynb
```

---

### Key Learnings

- Importance of handling imbalanced datasets
- Effectiveness of gradient boosting models
- Practical usage of early stopping
- Model interpretability using feature importance & PDP

---

### Author

**Aryaman Jain**
_Data Science Intern_

---
