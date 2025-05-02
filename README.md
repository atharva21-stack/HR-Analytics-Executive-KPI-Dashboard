# 📊 CUSTOMER SEGMENTATION ANALYSIS

### 1. Preview of Project  
### 2. Project Overview

---

### **Preview of Project:**

**Customer Segmentation Visualization (RFM + Clustering):**  
![Customer Segmentation Clusters](https://github.com/ekaterinakham/PowerBI-Tableau-SQL-Excel-HR-Analytics-Project/assets/144201262/eaa60708-2dc7-4185-a719-7b9fdd3e0bc1)

**Customer Behavior Heatmap (RFM Score Matrix):**  
![RFM Heatmap](https://github.com/ekaterinakham/PowerBI-Tableau-SQL-Excel-HR-Analytics-Project/assets/144201262/0d853a88-0651-4eae-a282-3b03abe5ed40)

---

### **Project Overview**

This project demonstrates a modern, data-driven approach to customer segmentation using **RFM analysis**, **K-Means clustering**, and **Python-based visualization**, integrated with SQL-based preprocessing. It reflects core Business Intelligence practices and aligns with my experience in delivering insight-rich dashboards, segmentation strategies, and stakeholder-ready visuals.

---

### **Dataset**

Used a cleaned open-source retail transactional dataset including `CustomerID`, `InvoiceDate`, `InvoiceNo`, and `Amount` to build a reliable segmentation model.

---

### **Objective**

To help marketing and business teams:
- Identify high-value customers.
- Understand customer behavior patterns.
- Enable data-backed targeting strategies.
- Optimize customer engagement and retention.

---

### **Analysis Process**

#### 🔹 **RFM Segmentation:**
- **Recency:** Days since last purchase.
- **Frequency:** Number of purchases.
- **Monetary:** Total amount spent.

RFM scores were assigned using quantile-based binning and combined into customer segments (e.g., Champions, Loyal Customers, At Risk).

#### 🔹 **K-Means Clustering:**
- Used Elbow Method and Silhouette Score to find optimal `k`.
- Segmented customers into clusters with similar behavior profiles.
- Scaled features and evaluated cluster distribution using heatmaps and scatter plots.

#### 🔹 **Customer Journey & Profitability Mapping:**
- Analyzed average lifetime value and purchase patterns by cluster.
- Suggested tailored strategies for each segment (e.g., retention for At Risk, upsell for Champions).

---

### **Tech Stack & Tools**

- **Languages:** Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- **Data Querying:** SQL (Preprocessing + Aggregation)
- **Modeling:** K-Means Clustering, RFM Score Calculation
- **Visualization:** Matplotlib, Seaborn (customizable for Power BI/Tableau integration)
- **Deployment Ready:** Jupyter Notebook for reproducibility and stakeholder demos

---

### **Outcome**

- Built a production-ready segmentation pipeline using modern data science techniques.
- Identified 4 profitable customer segments based on behavior.
- Delivered actionable insights for targeted marketing and improved ROI.

---

### ✅ **Why This Matters**

This project demonstrates analytical thinking, hands-on data modeling, and the ability to translate raw customer data into business intelligence — all key requirements in 2025 BI, Data Analyst, and Data Engineering roles.
