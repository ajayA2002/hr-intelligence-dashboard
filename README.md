# 📊 HR Intelligence Dashboard

> *“The data didn’t hide the problem. The dashboard made it visible.”*

This project was built on a simple but critical observation —  
clean-looking HR data often hides unstable organizational behavior.

Developed using **Tableau and Python**, this dashboard analyzes **8,950 employee records** across **7 departments, 8 states, and a 10-year hiring window (2015–2024)**.

The objective is not reporting.

It is **decision support for workforce stability and retention strategy**.

---

## 🎯 Business Problem

Most HR systems fail not due to lack of data, but due to lack of actionable clarity.

This project addresses:

- Why employees leave (attrition drivers)
- Where workforce risk is concentrated
- How compensation, geography, and demographics influence retention

---

## 📊 Live Dashboard

https://public.tableau.com/views/HR_Dashboard_17763352100130/HRSummary

---

## 📈 Tableau Profile

https://public.tableau.com/app/profile/ajay.bingishetty/vizzes

---

## 🧠 Key Business Insights

- 🔴 Attrition is heavily concentrated in specific departments, not evenly distributed  
- 💰 Lower salary bands show significantly higher employee turnover  
- 📉 Early-tenure employees represent the highest churn segment  
- 🏢 ~70% workforce concentration in a single geography creates structural dependency risk  
- ⚖️ Job satisfaction is strongly correlated with retention stability  
- 📊 Experience level is a primary predictor of employee retention behavior  

---

## 📊 Dashboard Scope

This dashboard is structured to move from **visibility → diagnosis → decision support**:

### 1. Workforce Overview
- Total employees, attrition rate, hiring trends

### 2. Demographic Analysis
- Age, gender, education distribution

### 3. Compensation & Attrition
- Salary bands vs retention probability
- Role-wise compensation imbalance

### 4. Employee-Level Drilldown
- Full exploration of all 8,950 employee records

---

## 🧠 Data Engineering Approach

Synthetic dataset generated using Python with controlled realism:

- **Pandas / NumPy** → structured generation logic  
- **Faker** → realistic employee identity simulation  
- Salary modeling based on:
  - education level  
  - role hierarchy  
  - age distribution  
- Attrition simulation using:
  - tenure-based probability  
  - department risk weighting  
- Hiring distribution spread across 2015–2024

---

## 🛠 Tech Stack

- Tableau → Dashboard development & visualization  
- Python → Data generation  
- Pandas / NumPy → Data modeling  
- Faker → Synthetic identity creation  

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

---

## 📌 Files Overview

- **HR_Dashboard.twbx** → Tableau packaged dashboard  
- **README.md** → Project documentation  
- **dashboard-summary-active.png** → Executive-level overview  
- **dashboard-records-active1.png** → Detailed employee-level view  
- **dataset.csv** → Synthetic HR dataset (8,950 records)  
- **generate_data.py** → Python script for dataset generation  

---

## 🙏 Acknowledgement

Inspired by **Data With Baraa (Baraa Khatib Salkini)** —  
for shaping analytical thinking and dashboard storytelling principles.

---

## 👤 Author

**Ajay Bingishetty**  
📊 Tableau Portfolio → https://public.tableau.com/app/profile/ajay.bingishetty  

---

## ⚡ Closing Insight

> A dashboard is not a report. It is a decision environment.

---
