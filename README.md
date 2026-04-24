# 📊 HR Intelligence Dashboard  
### Decision Intelligence System for Workforce Risk & Attrition Analysis  

> “The data didn’t hide the problem. The dashboard made it visible.”

---

## 🧭 Overview

A **Tableau + Python-powered HR analytics system** designed to uncover workforce risks, attrition drivers, and compensation imbalances across an organization.

It transforms raw HR data into **decision intelligence for retention strategy and workforce planning**.

### Dataset Scope:
- 8,950 employee records  
- 7 departments  
- 8 states  
- 2015–2024 hiring window  

**Objective:** Shift from reporting → decision intelligence

---

## 🎯 Business Problem

Most HR systems fail not due to lack of data, but due to lack of interpretability.

This project addresses:

- Why employees leave the organization  
- Where attrition risk is concentrated  
- How compensation and geography influence retention  
- Which workforce patterns indicate structural instability  

---

## 📊 Live Dashboard

👉 https://public.tableau.com/views/HR_Dashboard_17763352100130/HRSummary  

---

## 📈 Tableau Profile

👉 https://public.tableau.com/app/profile/ajay.bingishetty  

---

## 🧠 Key Insights

- 🔴 Attrition is concentrated in specific departments, not evenly distributed  
- 💰 Lower salary bands show significantly higher turnover probability  
- 📉 Early-tenure employees represent the highest attrition segment  
- 🏢 ~70% workforce concentration in a single geography creates dependency risk  
- ⚖️ Job satisfaction strongly correlates with employee retention  
- 📊 Experience level is a strong predictor of attrition behavior  

---

## 📊 Analytical Framework

### 1. Workforce Overview
- Headcount trends  
- Attrition rate analysis  
- Hiring patterns (2015–2024)

### 2. Demographic Analysis
- Age distribution  
- Gender distribution  
- Education segmentation  

### 3. Compensation Intelligence
- Salary vs attrition correlation  
- Role-based pay gaps  
- Retention risk segmentation  

### 4. Employee-Level Drilldown
- Full exploration of 8,950 records  
- Individual-level workforce visibility  

---

## 🧠 Data Engineering Approach

Synthetic but realistic dataset built using Python:

- **Pandas / NumPy** → structured data modeling  
- **Faker** → realistic employee generation  

### Modeling Logic:
- Salary derived from education, role, and age  
- Attrition modeled using tenure-based probability curves  
- Department-level risk weighting applied  
- Hiring simulated across 2015–2024  

---

## 🛠 Tech Stack

- Tableau → Data visualization & dashboard design  
- Python → Synthetic dataset generation  
- Pandas / NumPy → Data modeling  
- Faker → Identity simulation  

---

## 📁 Project Structure
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

## ⚡ Final Insight

> A dashboard is not a report. It is a decision environment.
