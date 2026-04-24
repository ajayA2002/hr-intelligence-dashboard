# 📊 HR Intelligence Dashboard

> *“The data didn’t hide the problem. The dashboard made it visible.”*

---

## 🧭 Overview

A **Tableau + Python-powered HR analytics dashboard** built to uncover hidden workforce risks, attrition drivers, and compensation imbalance across an organization.

Analyzes:
- **8,950 employee records**
- **7 departments**
- **8 states**
- **2015–2024 hiring window**

> Objective: Move from reporting → decision intelligence

---

## 🎯 What This Project Solves

Most HR systems fail not due to missing data — but due to unclear interpretation.

This dashboard answers:

- Why employees leave
- Where attrition risk is concentrated
- How salary, role, and geography influence retention
- Which workforce patterns signal structural instability

---

## 📊 Live Dashboard

👉 https://public.tableau.com/views/HR_Dashboard_17763352100130/HRSummary  

## 📈 Tableau Profile

👉 https://public.tableau.com/app/profile/ajay.bingishetty/vizzes  

---

## 🧠 Key Insights

- 🔴 Attrition is concentrated in specific departments (not evenly distributed risk)
- 💰 Lower salary bands show significantly higher churn
- 📉 Early-tenure employees form the highest-risk group
- 🏢 ~70% workforce concentrated in a single geography (structural dependency risk)
- ⚖️ Job satisfaction strongly correlates with retention
- 📊 Experience level is a primary retention predictor

---

## 📊 Dashboard Design Layers

### 1. Workforce Overview
- Headcount
- Attrition rate
- Hiring trends

### 2. Demographics
- Age distribution
- Gender distribution
- Education levels

### 3. Compensation Analysis
- Salary vs attrition
- Role-based disparity
- Retention risk zones

### 4. Deep Drilldown
- 8,950 employee-level exploration

---

## 🧠 Data Engineering

Synthetic dataset built using Python:

- Pandas / NumPy → data structure design  
- Faker → realistic employee generation  
- Salary logic → education + role + age weighting  
- Attrition model → tenure + department risk curves  
- Timeline → 2015–2024 hiring simulation  

---

## 🛠 Tech Stack

**Tableau** → Dashboard design  
**Python** → Data generation  
**Pandas / NumPy** → Data modeling  
**Faker** → Synthetic data creation  

---

## 📁 Repository Structure
hr-intelligence-dashboard/
│
├── HR_Dashboard.twbx
├── README.md
├── dashboard-summary-active.png
├── dashboard-records-active1.png
├── dataset.csv
├── generate_data.py


---

## 👤 Author

**Ajay Bingishetty**  
📊 Tableau Portfolio → https://public.tableau.com/app/profile/ajay.bingishetty  

---

## ⚡ Closing Insight

> A dashboard is not a report. It is a decision environment.
