📊 HR Attrition Analysis – Data Analytics Project

🔍 Overview

This project analyzes employee attrition to identify key factors influencing employee exits. The analysis is done using **Python, SQL, and Power BI** with clear insights and recommendations for improving retention.



🛠️ Tools Used

* **Python** – Data cleaning & EDA
* **SQL (MySQL)** – Data querying
* **Power BI** – Dashboard & KPIs
* **DAX** – Measures for attrition metrics



📁 Project Structure

├── data
├── python
├── dashboard
└── reports



📈 Key Insights

* Overall attrition rate: **16%**
* **Overtime workers** show highest attrition (30%)
* **Low salary (< ₹5,000)** increases attrition
* Highest attrition in **ages 18–30**
* Sales & Lab Technician roles most affected
* Lack of promotion (3+ years) drives exits



📊 Power BI KPIs

* Attrition Rate
* Attrition Count
* Total Employees
* Avg. Monthly Income
* Job Satisfaction



🧮 DAX Measures

```DAX
Attrition Count = CALCULATE(COUNTROWS(Employee), Employee[Attrition] = "Yes")
Attrition Rate = DIVIDE([Attrition Count], COUNTROWS(Employee))
```


📝 Recommendations

* Reduce overtime & improve work-life balance
* Offer competitive salary bands
* Strengthen promotion & career growth
* Improve onboarding (first 24 months)
* Manager & leadership training


