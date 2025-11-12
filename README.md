# Credit-Card-Analysis
This notebook performs an end-to-end Credit Card Fraud Detection project using synthetic data.
# 💳 Credit Card Fraud Detection (Machine Learning Project)

This notebook performs an **end-to-end fraud detection analysis** using **synthetic credit card transaction data**.

It demonstrates how to handle **imbalanced data**, train multiple models, and evaluate them using key classification metrics.

---

## 📊 Project Workflow

### 1️⃣ Data Generation
- 10,000 synthetic transactions  
- Features include:
  - Transaction amount  
  - Time of day  
  - Merchant category  
  - Card type  
  - Country  
  - Age of cardholder  
- Injected **fraud patterns** (e.g., high amount + online merchants)

### 2️⃣ EDA
- Checked data balance  
- Visualized fraud distribution  
- Summarized key numerical statistics

### 3️⃣ Data Preparation
- One-hot encoded categorical features  
- Applied **SMOTE** to balance fraud and non-fraud samples  
- Standardized numerical features  

### 4️⃣ Model Training
Trained and evaluated:
- Logistic Regression  
- Random Forest  
- Gradient Boosting  

### 5️⃣ Evaluation
| Metric | Description |
|---------|--------------|
| Precision | How many predicted frauds were actual frauds |
| Recall | How many actual frauds were detected |
| F1 | Harmonic mean of Precision and Recall |
| ROC-AUC | Discriminatory power of model |

### 6️⃣ Visualizations
- ROC curves for all models  
- Confusion matrix for the best model  

### 7️⃣ Future Prediction
Predicted fraud probabilities for 10 unseen transactions.

---

## 🏆 Best Model
The best model (by ROC-AUC) was typically **Random Forest** or **Gradient Boosting**, depending on the run.

---

## 📁 Output Files
| File | Description |
|------|--------------|
| `credit_card_fraud_data.csv` | Synthetic transaction dataset |
| `credit_card_fraud_model_results.csv` | Model metrics summary |
| `credit_card_future_predictions.csv` | Future fraud probability predictions |

---
