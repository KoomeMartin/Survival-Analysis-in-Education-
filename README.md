# 🎓 Survival Analysis in Education

## CASE STUDY
### INVESTIGATING STUDENT DROP OUT RATES USING A TIME DEPENDENT COX PROPORTIONAL HAZARDS MODEL AT THE FACULTY OF SCIENCE AND TECHNOLOGY IN MULTIMEDIA UNIVERSITY OF KENYA

This project investigates the student `dropout rates` in the faculty of science and technology using `Survival Analysis` techniques, with a specific focus on the 2020 - 2024 cohort. The aim is to understand when and why students leave before completing their studies, and to identify key demographic and academic factors that influence dropout risk.

##  Overall study population 

![Academic Status   Gender Distribution](https://github.com/user-attachments/assets/93e2c732-927b-4e63-8949-d9ac9f174210)

### 🔍 Objectives
* Estimate student survival probabilities over a 4-year period.
* Identify high-risk dropout periods and vulnerable groups.
* Evaluate the effects of variables like gender, academic performance, and department using Kaplan-Meier curves and Cox Proportional Hazards models.
* Compare dropout risks between groups (e.g., male vs female) using the Log-rank test.

### 📊 Methodology

* **Kaplan-Meier Estimation** for visualizing survival probabilities.
  
![Overall](https://github.com/user-attachments/assets/0fd2be08-6235-4ad1-8dd5-2ae6c5b6a69d)

* **Log-rank tests** for comparing survival distributions.
* **Cox Proportional Hazards model** for multivariate regression analysis.

![Time dependent cox ph model](https://github.com/user-attachments/assets/ce9babfd-5005-4349-b007-b30aeec7a0e8)


### 🧠 Key Findings

* The 3rd year is a critical dropout period across most departments.
* Male students exhibited slightly higher dropout risks than females.
* Students with supplementary exams or lower grades were at significantly higher risk.
* Institutional support and resilience mechanisms appear to mitigate some combined dropout effects.

### 💡 Recommendations

* Tailored academic support for low-performing students.
* Restructuring of the work-study program to support learning outcomes.
* Career engagement events and university-industry partnerships to improve relevance and job readiness.


### 📌 Technologies Used

* Python (Pandas, Lifelines, Matplotlib, Seaborn)
* Jupyter Notebook
* Statistical modeling (Kaplan-Meier, CoxPH, Log-rank)
