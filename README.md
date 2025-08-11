# 📊 Telecom Customer Churn Analysis

## 📌 Project Overview

This project focuses on analyzing customer churn for a telecom company using **Power BI** for visualization and an accompanying **Jupyter Notebook** for data preprocessing, exploration, and insights generation.

Customer churn is a critical business metric for telecom companies, representing the percentage of customers who discontinue their services. The goal of this analysis is to identify key patterns, customer behaviors, and service features that contribute to churn, enabling data-driven retention strategies.

---

## 🛠️ Tools & Technologies Used

* **Python** (Pandas, NumPy, Matplotlib, Seaborn) – for data preprocessing & EDA
* **Jupyter Notebook** – for interactive analysis
* **Power BI** – for dashboard design & interactive visualization
* **Dataset** – Telecom customer churn dataset (contains demographics, service details, and churn status)

---

## 📂 Project Structure

```
Telecom-Customer-Churn/
│
├── customerchurn_analysis.ipynb        # Jupyter notebook with data preprocessing & EDA
├── CustomerChurn.pbix                  # Power BI dashboard screenshot
├── README.md                           # Project documentation
└── Customerchurn.csv                   # Dataset folder 
```

---

## 📊 Dashboard Insights

### 1️⃣ **Key Metrics**

* **Total Customers**: `7043`
* **Churned Customers**: `1869`
* **Churn Rate**: `27%`

### 2️⃣ **Churn by Contract Type**

* **Month-to-Month** customers have the highest churn (`1655` customers).
* **One-Year** and **Two-Year** contracts have significantly lower churn.

### 3️⃣ **Churn by Tenure Segment**

* Customers in their **first year** have the highest churn rate (`43.24%`).
* Churn decreases with longer tenure.

### 4️⃣ **Churn by Payment Method**

* **Electronic Check** users have the highest churn.
* Customers using **automatic bank transfers** or **credit cards** churn less.

### 5️⃣ **Churn by Multiple Lines**

* Churn rates are fairly similar across multiple line usage categories.

---

## 🔍 Key Insights

* **Short-term contracts** and **first-year customers** are most likely to churn.
* **Electronic check payment method** correlates strongly with higher churn.
* **Loyalty programs** or **discounted long-term contracts** could help improve retention.

---

## 🚀 How to Use

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/telecom-customer-churn.git
   cd telecom-customer-churn
   ```
2. Open the Jupyter Notebook:

   ```bash
   jupyter notebook customerchurn_analysis.ipynb
   ```
3. Explore the Power BI dashboard (or view the screenshot provided).

---

## 📌 Future Improvements

* Implement a **Machine Learning model** to predict churn probability.
* Add **customer segmentation analysis** for targeted retention campaigns.
* Build an **interactive web app** for real-time churn monitoring.
