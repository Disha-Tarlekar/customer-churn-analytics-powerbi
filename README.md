# 📊 Customer Churn Analytics Dashboard (Excel + MySQL + Power BI)

This project is an end-to-end **Customer Churn Analytics System** built to identify  
💠 *how many customers are churning,*  
💠 *why churn is happening,* and  
💠 *which actions can reduce churn and protect revenue.*

It simulates a real subscription/telecom business scenario and converts raw customer data into **insights + retention strategy** using interactive dashboards.

---

## 🧱 Tech Stack

| Tool | Purpose |
|------|---------|
| **Excel** | Initial analysis, data cleaning & missing value checks |
| **MySQL** | Data storage, SQL queries, churn metrics & summary views |
| **Power BI** | Data modeling, DAX measures, dashboards & storytelling |

---

## 📂 Project Contents

├── customer_churn_dataset_cleaned.csv # Clean dataset (if shared)

├── sql_scripts_customer_churn.sql # SQL table + queries

├── project_report.pdf # Dashboard PDF export


---

## 📊 Dashboard Pages

### 1️⃣ **Customer Churn Overview**
- Total customers, active vs churned
- Churn rate & revenue lost due to churn
- Churn by plan type & region
- Tenure & age segmentation
- **Slicers:** Region • Plan Type

### 2️⃣ **Customer Behavior & Risk Drivers**
- Complaints vs churn trend
- Usage vs tenure analysis
- Churn by age group & gender
- High-value churned customers table

### 3️⃣ **Executive Summary & Key Insights**
- Project objective & business overview
- Root causes behind churn
- Actionable recommendations
- Business impact summary

---

## 🧮 Key DAX Measures (Examples)

- Total Customers
- Churned Customers
- Churn Rate = DIVIDE([Churned Customers], [Total Customers])
- Revenue Lost to Churn
- Avg Monthly Usage
- Age Band (calculated column)
- Tenure Band (calculated column)


---

## 💡 Business Insights (Highlights)

- Churn is highest in **Basic and Pro plans**
- Users aged **26–45 churn the most**
- **More complaints → higher churn probability**
- **Declining usage = early churn warning**
- Significant **revenue loss due to high-value customer churn**

---

## 🚀 Recommendations

| Area | Action |
|------|--------|
| Support | Improve complaint resolution & service quality |
| Engagement | Early onboarding triggers in first 6–12 months |
| Pricing | Personalized offers for risky segments (Basic/Pro plans) |
| Prediction | Use usage-drop as churn-risk indicator |
| Loyalty | Rewards for long-term & high-value customers |

---

## 🔗 Analytics Pipeline

Raw Data (CSV/Excel)

↓

Excel Cleaning & Validation

↓

MySQL Database (SQL Queries & Views)

↓

Power BI Data Model + DAX

↓

Interactive Dashboards

↓

Insights → Retention Strategy


---

## 👩‍💻 Author

**🟢 Disha Tarlekar**  
*Aspiring Data Analyst — Excel | SQL | Power BI*

📌 Open to roles: **Data Analyst | BI Analyst | SQL Analyst | Power BI Developer**  
📌 Portfolio / GitHub projects coming soon 🚀

---

⭐ *If you like this project, please star ⭐ the repository — it motivates me to build more!*  
