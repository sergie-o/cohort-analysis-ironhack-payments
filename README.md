# 📊 Cohort Analysis — Customer Retention & Insights  

<p align="center">
  <img src="https://github.com/sergie-o/cohort-analysis-ironhack-payments/blob/main/39334A14-0356-4F1E-8522-43B06C9BEF30.png" width="800">
</p>

![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)  
![Pandas](https://img.shields.io/badge/Library-Pandas-orange.svg)  
![Matplotlib](https://img.shields.io/badge/Library-Matplotlib-yellow.svg)  
![Seaborn](https://img.shields.io/badge/Library-Seaborn-lightblue.svg)  
![Dataset](https://img.shields.io/badge/Data-Ironhack%20Payments-blueviolet.svg)  
![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)  

> 🔍 **How do users engage with services over time, and what drives retention?**  
> This project applies **Cohort Analysis** to explore customer retention, incidents, and revenue patterns in a financial services dataset.  

---

## 📌 Overview  
Cohort analysis is a method of tracking how groups of users behave over time.  
In this project, I analyzed **Ironhack Payments’ cash advance service data** to uncover:  
- How often users return after their first request  
- Retention and churn across cohorts  
- Incident rates per cohort  
- Revenue performance by cohort over time  

---

## 📂 Dataset Description  
- **Source**: Provided by Ironhack Payments (bootcamp dataset)  
- **Files Used**:  
  - `extract - cash request - data analyst.xlsx` → Cash advance requests  
  - `extract - fees - data analyst.xlsx` → Fees & revenue  
  - `Lexique - Data Analyst.xlsx` → Data dictionary  
- **Notes**:  
  - Missing values were handled in critical fields  
  - Duplicate transactions removed  
  - Date fields standardized  

---

## 🎯 Research Goals  
1. **Service Usage Frequency** → How often do users request cash advances?  
2. **Retention** → Do users from each cohort keep using the service over time?  
3. **Incident Rates** → Which cohorts face higher risks of issues?  
4. **Revenue** → How does financial performance evolve across cohorts?  

---

## 🛠 Steps Taken  
1. **Data Cleaning**  
   - Handled missing values and standardized dates  
   - Removed duplicate transactions  
2. **EDA (Exploratory Data Analysis)**  
   - Defined cohorts by first transaction month  
   - Tracked user behavior over time  
3. **Visualizations**  
   - **Cohort heatmaps** → Retention over time  
   - **Line charts** → Incidents & revenue trends  
   - **Bar plots** → Cohort sizes and usage frequency  

---

## 📊 Key Findings  
- **Retention declined sharply after the first month**, highlighting onboarding and engagement challenges.  
- **Incidents clustered in certain cohorts**, suggesting operational improvements are needed during specific timeframes.  
- **Revenue trends** showed strong initial activity but sustained growth required improving retention.  
- Cohort analysis provided clear thresholds where **customer engagement weakened**, offering actionable insights for product teams.  

---

## 💻 Reproduction Guide  
**Requirements**:  
`pandas`, `matplotlib`, `seaborn`, `numpy`  

**Run Instructions:**  
1. **Clone this repository**  
   ```bash
   git clone https://github.com/<your-username>/cohort-analysis-project.git
   cd cohort-analysis-project
