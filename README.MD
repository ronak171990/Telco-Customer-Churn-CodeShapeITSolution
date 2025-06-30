# 📊 Telco Customer Churn Analysis

Customer churn is a major issue in the telecom industry. This project uses machine learning and data analysis techniques to understand which factors lead to customer churn and builds a predictive model to identify high-risk customers.

We used Python for data preprocessing, EDA, and modeling, and evaluated the models using accuracy, F1 score, and ROC-AUC metrics.

---

## 📁 Dataset Information

* 📌 **Source**: IBM Sample Dataset
* 📍 **Records**: 7,043 customer entries
* 🌟 **Target**: `Churn` (Yes/No)

### Key Features:

* `gender`, `SeniorCitizen`, `Partner`, `Dependents`
* `tenure`, `PhoneService`, `InternetService`, etc.
* `Contract`, `MonthlyCharges`, `PaymentMethod`, `TotalCharges`

We performed:

* ✅ Data cleaning
* ✅ Missing value handling
* ✅ One-hot encoding for categorical variables

---

## ✅ Short Summary

* 📊 Built a data-driven solution to predict customer churn for a telecom company.
* 🔍 Applied data cleaning, exploratory analysis, and feature engineering.
* 🧠 Trained and evaluated 3 models: Logistic Regression, Random Forest, and XGBoost.
* 🌟 Achieved 80% accuracy and 0.84 ROC-AUC with Logistic Regression.
* 📁 Delivered insights through visuals and saved all artifacts in a reusable format.

---

## 📈 Auto-Generated Insights from Plots

### 📌 1. Churn Distribution

\~26.6% of customers have churned — confirming a high-risk business segment.

### 📌 2. Contract Type

Month-to-month contracts lead to the highest churn. Long-term contracts provide retention stability.

### 📌 3. Tenure

Customers with <12 months tenure are far more likely to churn. Loyalty programs can help here.

### 📌 4. Monthly Charges

Customers with monthly charges > ₹90–₹100 show higher churn, suggesting price sensitivity.

### 📌 5. Internet Service

Fiber optic users churn the most. May indicate service quality or pricing concerns.

### 📌 6. Payment Method

Electronic check users churn more than those using cards or bank transfers.

---

## 🔍 Additional Hidden Insights

### 📌 7. Tech Support

Lack of tech support is linked to higher churn. Offering it as a bundled service can help.

### 📌 8. Security & Protection

Customers without online security/device protection churn more.

### 📌 9. Streaming

Streaming services do not strongly influence churn — likely add-ons, not drivers.

### 📌 10. Paperless Billing

Slightly higher churn among paperless users — possibly more digitally agile.

### 📌 11. Senior Citizens

No significant increase in churn — challenges assumptions about age and loyalty.

### 📌 12. Total Charges

Low total charges correlate with churn, suggesting newer or less engaged customers.

### 📌 13. Multiple Services

More services = lower churn. Bundling improves stickiness.

---

## 🧠 Bonus: Model Insight

* ✅ **Logistic Regression** delivered the best results:

  * Accuracy: `80.2%`
  * F1 Score: `0.605`
  * ROC-AUC: `0.836`
* Simple, interpretable, and ready for production deployment or dashboard integration.

---

## 🌟 Key Takeaways

* ⚠️ Month-to-month contracts have the highest churn rate.
* 💰 High monthly charges drive churn risk.
* ⏳ Longer-tenure users are more loyal.
* 🌐 Fiber-optic users churn more often.
* 🌟 Early identification = better retention strategy.

---
