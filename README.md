# customer-rfm-analysis
Customer Segmentation using RFM Analysis in Python
# 📊 Customer Segmentation using RFM Analysis

## 📌 Project Overview
This project focuses on analyzing customer transaction data using **RFM (Recency, Frequency, Monetary) Analysis** to identify high-value customers and improve business decision-making.

---

## 🎯 Objectives
- Analyze customer behavior based on purchase patterns  
- Segment customers into meaningful groups  
- Identify high-value and at-risk customers  
- Generate insights for targeted marketing strategies  

---

## 🧠 What is RFM Analysis?
RFM stands for:
- **Recency (R):** How recently a customer made a purchase  
- **Frequency (F):** How often a customer makes purchases  
- **Monetary (M):** How much money a customer spends  

Customers are scored on a scale of 1–5 and segmented accordingly.

---

## ⚙️ Steps Performed

1. **Data Loading & Exploration**
   - Imported customer and transaction datasets  
   - Checked structure, data types, and missing values  

2. **Data Cleaning**
   - Handled missing values and duplicates  
   - Converted date columns to proper format  
   - Validated CustomerID consistency  

3. **RFM Calculation**
   - Calculated Recency, Frequency, and Monetary values  
   - Created RFM table for each customer  

4. **RFM Scoring**
   - Assigned scores (1–5) using quantile-based approach  

5. **Customer Segmentation**
   - Segmented customers into:
     - Champions  
     - Loyal Customers  
     - Potential Loyalists  
     - At Risk  
     - Lost  
     - Big Spenders  

6. **Data Visualization**
   - Customer Segment Distribution  
   - Revenue Contribution by Segment  
   - Recency vs Monetary Scatter Plot  
   - Pareto Analysis (80/20 Rule)  

---

## 📊 Key Insights

- A small percentage of customers contributes the majority of revenue (Pareto Principle)  
- Loyal and Potential customers form the largest segment  
- Champions generate the highest revenue  
- At-risk customers indicate potential churn  
- Recent customers tend to spend more  

---

## 💼 Business Impact

- Helps identify high-value customers for targeted marketing  
- Improves customer retention strategies  
- Enables data-driven decision-making  
- Optimizes marketing efforts and costs  

---

## 🛠️ Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 🚀 Conclusion

RFM analysis provides a powerful approach to understand customer behavior and segment customers effectively. By focusing on high-value customers and re-engaging at-risk segments, businesses can significantly improve revenue and customer retention.

---

