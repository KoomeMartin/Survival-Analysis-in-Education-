# 🎓 Survival Analysis in Education

## CASE STUDY
### Investigating Student Drop Out Rates Using A Time Dependent Cox Proportional Hazards Model At The Faculty Of Science And Technology In Multimedia University Of Kenya

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
![Gender](https://github.com/user-attachments/assets/371b388f-5f3b-4b3e-bbb5-42c4ea64507c)
![Settlement type](https://github.com/user-attachments/assets/1952562b-d1e2-4489-8ef2-432118362697)
![Departent](https://github.com/user-attachments/assets/f724559c-d901-452b-8dd6-d303e5ef30ab)

* **Log-rank tests** for comparing survival distributions.
* **Time dependent Cox Proportional Hazards model** for multivariate regression analysis.

![Time dependent cox ph model](https://github.com/user-attachments/assets/ce9babfd-5005-4349-b007-b30aeec7a0e8)

* **Time dependent Cox Proportional Hazards model with an interaction Point** for multivariate regression analysis.
  
![Cox Interaction point ](https://github.com/user-attachments/assets/112a6594-307c-43b2-9048-5ac5ee2a2745)

* **Time independent Cox Proportional Hazards model** for multivariate regression analysis.

 ![Baseline Cox](https://github.com/user-attachments/assets/b7280449-f576-441e-91bf-2f33782e757d)


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

### 📢 Disclaimer on Data Confidentiality
***Confidentiality Notice:***
The datasets used in this project contain sensitive academic records and institutional information from the Faculty of Science and Technology at Multimedia University of Kenya. In compliance with ethical and data protection guidelines, the raw data are not publicly shared in this repository.

Access to the data requires explicit authorization from the university. If you are a researcher or institution interested in collaborative work, please contact the university’s academic office or project contributors for data access protocols.

## 🎓 Contributors 
This project is a joint academic research undertaken as part of the requirements for the award of the Bachelor of Science in Mathematics and Computer Science degree at Multimedia University of Kenya.

We gratefully acknowledge the following contributors whose dedication and input were vital to the success of this study:

* Martin Koome 

* Emmanuel Ratemo  <a href='https://github.com/nyagucha'>GitHub<a/>

* Hill Arimba    <a href='https://github.com/Hill-Arimba99'>GitHub<a/>

* Denis Mutuku 

* Bravin Otieno

Their contributions were instrumental in data analysis, modeling, and interpretation throughout the project.
