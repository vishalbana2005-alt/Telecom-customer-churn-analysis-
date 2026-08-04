# Telecom Customer Churn Analysis

## Project Overview

This project performs an Exploratory Data Analysis (EDA) on a telecom customer churn dataset to identify the major factors influencing customer attrition. The analysis focuses on customer behavior, contract types, payment methods, tenure, and service usage to uncover patterns associated with churn and provide actionable business recommendations.

---

## Objectives

- Analyze customer churn patterns.
- Identify factors influencing customer retention.
- Explore relationships between customer tenure, contract type, payment methods, and churn.
- Generate business recommendations to improve customer retention.

---

## Dataset

- **Dataset:** Telecom Customer Churn Dataset
- **Records:** 7,000+ customer records
- **Features:** Customer demographics, account information, internet services, billing details, payment methods, contract types, and churn status.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Repository Structure

```
Telecom-customer-churn-analysis/
│
├── Dataset/
│   └── Customer Churn.csv
│
├── notebooks/
│   └── TCA.ipynb
│
├── reports/
│   └── Telecom_Customer_Churn_Analysis.pdf
│
└── README.md
```

---

## Key Findings

### Contract Type

- Customers with **month-to-month contracts** have the highest churn rate (**42%**).
- Customers with **one-year contracts** have a churn rate of **11%**.
- Customers with **two-year contracts** have the lowest churn rate (**3%**).

**Insight:** Long-term contracts significantly improve customer retention.

---

### Payment Method

- Customers using **electronic checks** show the highest churn rate (**45%**).
- Customers paying via **credit cards, bank transfers, or mailed checks** have considerably lower churn rates (approximately **15–18%**).

**Insight:** Payment method appears to influence customer retention.

---

### Customer Tenure

- Customers with **less than one year** of tenure experience the highest churn rate (**50%**).
- Customers with **1–3 years** of tenure show a churn rate of **35%**.
- Customers with **more than three years** of tenure have a churn rate of **15%**.

**Insight:** Churn decreases as customer tenure increases.

---

### Internet Service

- Customers using **Fiber Optic** internet services have a higher churn rate (**30%**) than DSL users (**20%**).

---

### Senior Citizens

- Senior citizens have a churn rate of **41%**.
- Non-senior customers have a churn rate of **26%**.

---

## Business Recommendations

- Encourage customers to switch to long-term contracts.
- Improve customer engagement during the first year of service.
- Promote more reliable payment methods instead of electronic checks.
- Develop targeted retention strategies for senior citizens.
- Improve customer satisfaction for Fiber Optic service users.

---

## Visualizations

The notebook includes visualizations such as:

- Churn distribution
- Contract type vs churn
- Payment method vs churn
- Customer tenure analysis
- Internet service analysis
- Customer demographic analysis

---

## Author

**Vishal Bana**
