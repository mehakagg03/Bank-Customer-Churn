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

- Customer Activity Matters: Active members were significantly less likely to churn compared to inactive members. This suggests that engagement and usage of banking services may contribute to customer retention.
- Credit Card Ownership Is Not a Strong Indicator: Customer held a credit card had a slight effect on their likelihood of churn, indicating that this feature may not be a reliable predictor of customer behavior.
- Gender Distribution Shows Minor Variation: Female customers were observed to churn at slightly higher rates, but the gender does not play a major role in churn behavior.
- Other Indicators: Analysis of numerical variables such as balance, tenure, and estimated salary, along with geographic trends, provide a stronger foundation for predictive modeling.

- Business Implication: Retention efforts may be more effective when targeted at inactive customers and potentially high-value clients who show early signs of disengagement.
