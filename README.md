

## Overview

This project predicts customer churn using data analysis, machine learning, and an interactive Power BI dashboard.
It helps businesses identify at-risk customers and take proactive steps to retain them.

## Dataset

The dataset contains telecom customer details such as:

* Contract type
* Tenure
* Monthly charges
* Payment method
* Churn status


## Steps Performed

**1. Data Cleaning** – handled missing values, performed data type conversions.
**2. Exploratory Data Analysis (EDA)** – visualized churn patterns and correlations.
**3. Feature Engineering** – created new features like `tenure_group`.
**4. Modeling** – tested Logistic Regression, Random Forest, and XGBoost.
**5. Evaluation** – measured accuracy, precision, recall, and F1-score.
**6. Dashboard Creation (Power BI)** – designed an interactive churn analysis dashboard.


## Power BI Dashboard

The **Telecom Customer Churn Dashboard** in Power BI provides a visual and interactive way to explore churn data, including:

* **KPIs** – Total Customers, Churned Customers, Churn %, Average Tenure.
* **Churn Breakdown** – by Contract type, Tenure segment, Gender, Payment method, and Multiple lines.
* **Customer Segment Filters** – filter by Internet service, gender, and senior citizen status.
* **Visual Insights** – highlight high churn groups using color-coded charts (red = high churn risk, green/blue = lower churn).

This dashboard allows stakeholders to **quickly identify high-risk customer segments** and explore churn patterns without coding.


## Tech Stack

**Python** – Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

**Power BI** – For dashboard and visualization

**Machine Learning** – Logistic Regression, Random Forest, XGBoost


## Results

* Achieved **79.49% accuracy** on churn prediction.
* Key churn factors: Contract type, Tenure, Monthly Charges.
* Power BI dashboard provides **real-time visual insights** for decision-making.


## How to Run

**Clone this repo:**

```bash
git clone https://github.com/kptanuja/Customer-Churn-Analysis.git
```

**Run the Python scripts for modeling:**

```bash
python churn_analysis.py
```

**View the Power BI Dashboard:**

1. Open the `.pbix` file in Power BI Desktop.
2. Use the filters and visuals to explore churn data interactively.

