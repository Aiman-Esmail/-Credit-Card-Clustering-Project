# 💳 Credit Card Customer Segmentation 

### 🎯 Overview
This project segments over **9,000 credit card users** into distinct behavioral groups using **K-Means Clustering**. The goal is to provide actionable insights for targeted marketing.

---

### 🛠️ Data Engineering Steps
* **Cleaning:** Missing values in `MINIMUM_PAYMENTS` and `CREDIT_LIMIT` were handled using Median imputation.
* **Normalization:** Applied **Log Transformation** to stabilize variance and minimize the effect of outliers.
* **Scaling:** Used **StandardScaler** to normalize features for distance-based clustering.

---

### 📊 Key Results (Conclusion)
The analysis successfully identified **5 customer segments**:
1. **High-Spenders:** High credit limit and frequent purchases.
2. **Dormant Users:** Minimal transactions, low balance.
3. **Revolving Users:** High balances with frequent minimum payments.
4. **Installment Buyers:** Prefer structured, periodic payments.
5. **Moderate Users:** Balanced spending and income ratio.

---

### 💡 Business Impact
These clusters help banks and insurance companies design **targeted marketing campaigns**, improve **customer retention**, and manage **credit risk** more effectively.
