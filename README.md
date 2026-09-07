# Digital Payment Fraud Detection

## Team 4 — Edversity AI Solutions Engineering Program
**Track:** FinTech & Digital Banking
**Members:** Qaiser, Alliya, Naiba, Salman, Tahir Abbas

## Problem Statement
Fraud in digital payment and mobile wallet transactions (e.g., EasyPaisa/JazzCash) is a major financial risk for FinTech companies. This project builds a machine learning model to classify transactions as fraudulent or legitimate.

## Dataset
- Source: Kaggle — Credit Card Fraud Detection
- Rows: 284,807 transactions
- Features: Time, Amount, V1–V28 (anonymized), Class (target)

## Approach
1. Data loading from Kaggle CSV
2. EDA & cleaning (removed 1,081 duplicates, analyzed class imbalance)
3. Feature engineering (5 new features: scaled amount/time, transaction hour, interaction features, amount category)
4. Model training: RandomForestClassifier with balanced sampling
5. Evaluation: 96.8% accuracy, confusion matrix, classification report

## Results
- Accuracy: 96.8%
- Precision (fraud class): 0.95
- 80/95 fraud cases correctly detected

## Setup Instructions
1. Clone this repository
2. Open `Team_4.ipynb` in Google Colab or Jupyter
3. Upload `creditcard.csv` (or mount Google Drive)
4. Run all cells in order

## Contributions
- [Har member yahan apna role likhein — e.g. "Alliya: EDA & visualization"]# digital-payment-fraud-detection
Fraud detection ML model for digital payments - Edversity Hackathon
