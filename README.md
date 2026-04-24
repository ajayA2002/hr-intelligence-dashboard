# 📊 HR Intelligence Dashboard

> *“The data didn’t hide the problem. The dashboard did.”*

This project started with a simple observation —  
the numbers looked clean.

That was the whole problem.

Built using **Tableau and Python**, this dashboard analyzes **8,950 employee records** across **7 departments, 8 states, and a 10-year hiring window (2015–2024)** — not to summarize outcomes, but to surface what quietly goes unquestioned.

Because in most organizations, risk doesn’t survive by being hidden.  
It survives by being easy to accept.

Operations carried the largest share of employees — and also the highest exits.  
Finance appeared balanced — until education exposed how compensation split across gender at higher levels.  
70% of the workforce sat in a single location — treated as geography, but functioning as a structural retention dependency.

None of this was missing from the data.  
It was missing from the way the data was presented.

So instead of building another reporting layer, this project focuses on something more direct —  
moving from observation to decision.

The dashboard brings together workforce overview, demographic composition, and income patterns into a single interactive experience. At the top level, it answers *what is happening*. One layer deeper, it explains *who makes up the workforce*. At its most critical layer, it challenges *what we assume is true* — especially around compensation and retention.

For deeper analysis, a fully filterable employee-level view allows navigation across all 8,950 records — turning aggregated insight into individual-level clarity.

Under the hood, the dataset is synthetically generated using Python (Pandas, NumPy, Faker) with controlled realism — salary adjusted by education, gender, and age; hiring trends distributed across years; and attrition modeled with time constraints.

This isn’t just a dashboard build.  
It’s a design decision.

Because a clean-looking dashboard can be more dangerous than a broken one —  
it convinces people nothing needs attention.

---

## 📊 Live Dashboard
https://public.tableau.com/views/HR_Dashboard_17763352100130/HRSummary

---

## 🏗 Project Structure
hr-intelligence-dashboard/
│
├── data/
│ └── dataset.csv
│
├── notebook/
│ └── generate_data.py
│
├── dashboard/
│ └── HR Dashboard.twbx
│
├── images/
│ ├── dashboard-summary-active.png
│ └── dashboard-records-active1.png
│
└── README.md

---

## 🛠 Tech Stack

- **Tableau** → Data visualization & dashboard design  
- **Python** → Data generation  
- **Pandas / NumPy** → Data modeling  
- **Faker** → Synthetic data creation  

---

## 🙏 Acknowledgement

Inspired by **Data With Baraa (Baraa Khatib Salkini)** —  
not just in how dashboards are built, but in what they are responsible for.

---

## 👤 Author

**Ajay Bingishetty**  
https://public.tableau.com/app/profile/ajay.bingishetty

---

> *If your dashboard feels clear, it’s probably protecting the problem — not revealing it.*
