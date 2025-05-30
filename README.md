# 🛡️ Online Payments Fraud Detection

This project aims to detect fraudulent transactions using machine learning techniques. It leverages a real-world dataset of online payment transactions to build a binary classification model that distinguishes between legitimate and fraudulent transactions.

## 📊 Dataset

**Source**: [Kaggle - Online Payments Fraud Detection](https://www.kaggle.com/code/ananthu19/online-payments-fraud-detection/input)

**Description**:  
The dataset contains a total of **6362620** records and **10** features including transaction amount, type, and origin/destination accounts.

- `step` - Time step unit (hour)
- `type` - Type of transaction (e.g., CASH_OUT, TRANSFER)
- `amount` - Amount of the transaction
- `nameOrig` - Customer who initiated the transaction
- `oldbalanceOrg` - Initial balance before transaction
- `newbalanceOrig` - New balance after transaction
- `nameDest` - Recipient of the transaction
- `oldbalanceDest` - Initial recipient balance
- `newbalanceDest` - New recipient balance
- `isFraud` - Target variable (1 = fraud, 0 = legitimate)

✅ Project Steps
Data Preprocessing
Handling null values
Feature engineering
Encoding categorical features
Exploratory Data Analysis (EDA)
Class imbalance inspection
Visualizations of transaction types and fraud patterns
Model Training
Logistic Regression
XGBoost
LightGBM
Random Forest
Evaluation
Accuracy, Precision, Recall, F1-score
Confusion matrix
ROC-AUC curve
Fraud Prevention Insights
Suggested business actions based on model predictions


