# 🧠 HR Analytics Project

## 📌 Overview

This project presents a comprehensive **HR Analytics solution** developed using SQL for data cleaning and analysis, and Power BI for insightful visualizations. The goal was to analyze workforce demographics, identify key HR trends, and uncover insights from a dataset spanning 20 years (2000–2020) with over 22,000 employee records.

---

## 🗂️ Tools & Technologies

- **Database:** MySQL Workbench  
- **Visualization:** Power BI  
- **Language:** SQL  

---

## 📊 Dataset

- 22,000+ records from the years 2000 to 2020  
- Covers employee demographics, job roles, location, hire & termination data  
- Cleaned and processed to enable structured querying and visualization  

---

## 🛠️ Project Workflow

1. **Data Cleaning & Preprocessing (SQL)**
   - Standardized date formats (`birthdate`, `hire_date`, `termdate`)
   - Added `AGE` column using `TIMESTAMPDIFF`
   - Filtered out invalid or future term dates

2. **Exploratory Data Analysis (SQL)**
   - Gender, race, and age distribution
   - Department- and title-wise employee and termination analysis
   - Geographic and temporal employment patterns

3. **Data Visualization (Power BI)**
   - Dashboards covering:
     - Gender & Age Group breakdowns
     - Headquarters vs Remote distribution
     - Turnover rates by department
     - Geographic heatmaps by state
     - Year-over-year employee trends

---

## ❓ Key Questions Answered

- What is the gender and race/ethnicity distribution of employees?
- What is the age distribution and most common job title?
- What is the average length of employment for terminated employees?
- Which departments have the highest turnover rates?
- How are employees distributed across locations?
- How has the workforce changed from 2000 to 2020?
- How does gender vary by department and job title?

---

## 📈 Summary of Findings

- **Gender:** 9,328 males, 8,455 females, 502 non-conforming  
- **Race:** Majority White (5,214), lowest count in Native Hawaiian or Other Pacific Islander  
- **Age:** Most employees are aged 25–34; youngest is 20, oldest is 57  
- **Location:** ~75% at Headquarters, ~25% Remote  
- **Tenure:** Average tenure for terminated employees is ~8 years  
- **Turnover:** Highest in Auditing and Legal departments  
- **Geography:** Most employees from **Ohio**, fewest from **Wisconsin**  
- **Growth:** Net employee count has steadily increased from 2000 to 2020  

---

## ✅ Conclusion

This HR analytics project offers actionable insights into workforce composition and HR operations. By integrating **SQL-based data analysis** and **Power BI dashboards**, it supports strategic decision-making for HR managers and business leaders. Key areas like diversity, turnover, age distribution, and hiring trends are clearly visualized, enabling data-driven HR strategy.


