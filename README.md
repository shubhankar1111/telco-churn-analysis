# Telco Customer Churn Analysis
### End-to-end Data Analytics & ML Project

## 📌 Project Overview
Analyzed 7,043 telecom customers to understand and predict churn 
using SQL, Python, Machine Learning, and Power BI.

**Business Problem:** 26.58% of customers are churning — costing 
the business significant revenue. The goal was to identify WHY 
customers churn and predict WHO will churn next.

---

## 🛠️ Tools & Technologies
| Tool | Purpose |
|---|---|
| Python (Pandas, NumPy) | Data cleaning & EDA |
| Matplotlib & Seaborn | Data visualization |
| SQLite + SQL | Data storage & querying |
| Scikit-learn | ML model building |
| Power BI | Interactive dashboard |

---

## 📁 Project Structure

---

## 📊 Key Findings

- **26.58%** overall churn rate — 1 in 4 customers leaving
- **Month-to-month** customers churn at **43%** vs **3%** for two-year contracts
- **Fiber optic** users churn at nearly **2x** the rate of DSL users
- Most churn happens in the **first 12 months** — critical retention window
- **14%** of customers are currently high risk (churn probability > 60%)

---

## 🤖 ML Results

| Model | ROC-AUC |
|---|---|
| Logistic Regression | 0.8438 |
| Random Forest | **0.9686** ✅ |

- Handled **73/27 class imbalance** via upsampling
- Top churn drivers: **tenure, monthly charges, contract type**

---

## 💡 Business Recommendations

1. **Retention outreach** at months 3, 6, and 12 for new customers
2. **Incentivise annual contracts** with 10-15% discount
3. **Review fiber optic pricing** — high churn suggests poor value perception
4. **Bundle add-on services** (security, backup) to increase stickiness
5. **Score customers monthly** using ML model — flag anyone above 60% risk

---

## 📈 Dashboard Preview
![Dashboard](Churn_Dashboard.pdf)

---

## 👤 Author
Shubhankar Kulkarni  
M.Tech Data Science  
www.linkedin.com/in/shubhankar-kulkarni-9a8727301 | shubhs0008@gmail.com
