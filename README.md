# Credit Card Customer Segmentation – FinTech Solutions

📊 This project applies clustering techniques to segment credit card holders for FinTech Solutions S.p.A. The goal is to support personalized marketing strategies based on customer behavior.

---

## 🎯 Objective

Segment customers based on:
- Spending habits (balance, purchases, cash advance)
- Payment behaviors (minimum/full payments)
- Usage patterns (frequency of transactions)

This allows the company to launch data-driven marketing campaigns for specific customer groups.

---

## 📁 Dataset

📥 [Download Dataset](https://proai-datasets.s3.eu-west-3.amazonaws.com/credit_card_customers.csv)

Key columns:
- `BALANCE`, `PURCHASES`, `CASH_ADVANCE`
- `PURCHASES_FREQUENCY`, `CREDIT_LIMIT`, `MINIMUM_PAYMENTS`, `TENURE`, etc.

---

## 🧠 Project Steps

1. **Exploratory Data Analysis (EDA)**
   - Summary stats, distribution plots, null values

2. **Preprocessing**
   - Missing value imputation (e.g., `MINIMUM_PAYMENTS`)
   - Feature normalization and standardization

3. **Clustering**
   - K-Means algorithm  
   - Evaluation with Elbow Method & Silhouette Score

4. **Interpretation**
   - Description of each cluster’s characteristics
   - Marketing strategy proposal per segment

---

## 🛠️ Tools Used

- Python 3  
- pandas, numpy  
- matplotlib, seaborn  
- scikit-learn

---

## 🔗 Author

👩 Giusi Russo – Junior Data Analyst  
🎓 Project created during the Data Analytics Master – ProfessionAI  
