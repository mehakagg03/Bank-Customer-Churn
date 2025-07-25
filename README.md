# Bank-Customer-Churn-Analysis
It focuses on understanding the patterns and behaviors of customers who decide to leave a bank. It identifies the key factors contributing to customer churn by analyzing various features such as customer activity, credit card ownership and account status.

## 📁 Dataset

The dataset used is `Churn_Modelling.csv`, which contains the following features for 10,000 customers:

- **CustomerID**: Unique ID of the customer
- **CreditScore**: Numerical credit score
- **Geography**: Country of the customer
- **Gender**: Male or Female
- **Age**, **Tenure**, **Balance**, **EstimatedSalary**
- **HasCrCard**: Whether the customer has a credit card
- **IsActiveMember**: Whether the customer is active
- **Exited**: **Target variable** — 1 if the customer churned, 0 if they stayed

## 🔍 Objectives

- Analyze customer demographics and behavior
- Visualize churn patterns using Seaborn and Matplotlib
- Identify factors that may influence customer churn

## 🛠️ Tools Used

- Python (Pandas, NumPy)
- Matplotlib, Seaborn
- Jupyter Notebook

## ✔ Conclusion

The analysis of the Bank Customer Churn dataset provided several valuable insights into customer behavior and the factors associated with churn:

📍 1. Geography Matters
Customers from Germany have a notably higher churn rate than those from Spain or France.
Prediction: Customers in Germany are more likely to churn, suggesting region-specific factors at play.

🧑‍💼 2. Age Affects Churn
Churn rate increases significantly with age, especially after age 40.
Prediction: Older customers (40+) are more likely to leave the bank, possibly due to retirement, life events, or unmet financial needs.

📦 3. Number of Products Strongly Influences Loyalty
Customers with 1 product churn at the highest rate.
Those with 2 or more products show increased loyalty.
Prediction: Customers with only 1 product are most likely to churn. Cross-selling is key to reducing churn.

📉 4. Customer Activity is Critical
Inactive members are much more likely to churn than active ones.
Prediction: Disengaged or passive users are strong churn risks. Engagement campaigns can help retain them.

👩‍💼 5. Gender Has Minor Influence
Slightly more female customers churn, but the difference is small.
Prediction: Gender is not a major churn driver.

💰 6. Balance vs. Churn
Customers with high balances show higher churn rates.
Prediction: High-balance customers may churn due to competition or dissatisfaction—ironically, this valuable group is at risk.

💳 7. Credit Card Ownership Has Little Effect
Minimal difference in churn rate between those with and without credit cards.
Prediction: Credit card status is not a strong indicator of customer loyalty.
