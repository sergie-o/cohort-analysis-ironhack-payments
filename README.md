# 📊 Cohort Analysis — Customer Retention & Insights  

![Cohort Analysis Banner](visuals/cohort_analysis_banner.png)  

![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)  
![Pandas](https://img.shields.io/badge/Library-Pandas-orange.svg)  
![Matplotlib](https://img.shields.io/badge/Library-Matplotlib-yellow.svg)  
![Seaborn](https://img.shields.io/badge/Library-Seaborn-lightblue.svg)  
![SQL](https://img.shields.io/badge/Queries-SQL-green.svg)  
![Dataset](https://img.shields.io/badge/Data-Ironhack%20Payments-blueviolet.svg)  
![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)  

> 🔍 **How do users engage with services over time, and what drives retention?**  
> This project uses **Cohort Analysis** to uncover customer retention, incidents, and revenue patterns in a financial services dataset.  

---

## 📌 Overview  
Cohort analysis is a powerful tool to track how groups of users (cohorts) behave over time.  
In this project, I analyzed **Ironhack Payments’ cash advance service dataset** to answer questions about:  
- How often users return after their first transaction  
- Retention and churn trends by cohort  
- Incident rates across cohorts  
- Revenue performance over time  

---

## 📂 Dataset Description  
- **Source**: Provided by Ironhack Payments (internal bootcamp dataset)  
- **Files Used**:  
  - `extract - cash request - data analyst.xlsx` → Cash advance requests  
  - `extract - fees - data analyst.xlsx` → Fees & revenue  
  - `Lexique - Data Analyst.xlsx` → Data dictionary  
- **Notes**:  
  - Missing values handled in key columns  
  - Duplicate transactions removed  
  - Dates standardized for analysis  

---

## 🎯 Research Goals  
1. **Service Usage Frequency** → How often do users request cash advances?  
2. **Retention** → Do users from each cohort keep using the service?  
3. **Incident Rates** → Which cohorts face more issues?  
4. **Revenue** → How does financial performance evolve across cohorts?  

---

## 🛠 Steps Taken  
1. **Data Cleaning**  
   - Handled missing values  
   - Standardized dates and removed duplicates  
2. **Exploratory Data Analysis (EDA)**  
   - Cohort creation based on first usage  
   - Tracked user activity across months  
3. **Visualizations**  
   - Cohort heatmaps for retention  
   - Line charts for incidents and revenue trends  
   - Bar plots for cohort size and usage frequency  
4. **SQL Integration**  
   - Queried user counts, cohort distributions, and retention patterns  

---

## 📊 Key Findings  
- **Retention dropped after the first month** across most cohorts — a common fintech challenge.  
- **Incidents clustered in certain cohorts**, highlighting periods of operational stress.  
- **Revenue trends** showed that while newer cohorts generated high initial revenue, sustainability depended on retention.  
- Cohort analysis helped identify **thresholds where user engagement declines**, providing actionable insight for product improvement.  

---

## 💻 Reproduction Guide  
**Requirements**:  
`pandas`, `matplotlib`, `seaborn`, `numpy`, `sqlite3`  

**Run Instructions:**  
1. **Clone this repository**  
   ```bash
   git clone https://github.com/<your-username>/cohort-analysis-project.git
   cd cohort-analysis-project
