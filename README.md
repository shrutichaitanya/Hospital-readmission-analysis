# Hospital Readmission Analysis

Predicting 30-day hospital readmission using patient demographics and clinical encounter data.

## Overview
This project analyzes inpatient hospital encounter data to identify and predict **30-day hospital readmissions** using Python and Jupyter Notebook.

The workflow includes:
- data loading and cleaning
- inpatient encounter filtering
- 30-day readmission target creation
- feature engineering
- exploratory data analysis
- logistic regression modeling
- export of processed data for reporting or dashboards

## Project Objectives
- Understand patient, encounter, and condition datasets
- Create a 30-day readmission label
- Engineer features such as age, length of stay, and number of conditions
- Explore readmission patterns across demographic and clinical variables
- Train and evaluate a predictive model

## Tools and Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Files in This Repository
- `HospitalReadmissionAnalytics.ipynb` — main project notebook
- `requirements.txt` — project dependencies
- `README.md` — project documentation

## Key Features
- Inpatient admission filtering
- 30-day readmission labeling
- Feature engineering:
  - age
  - length of stay
  - number of conditions
- Exploratory analysis by readmission status
- Logistic regression model for prediction

## Project Deliverables
- Jupyter Notebook analysis
- Logistic regression readmission model
- Tableau dashboard for interactive visualization

## ## Tableau Dashboard
An interactive dashboard was developed in Tableau to present key insights from the hospital readmission analysis.

[View the interactive dashboard on Tableau Public] (https://public.tableau.com/app/profile/shruti.chaitanya2024/viz/Book1_HospitalReadmissionAnalysis/Hospitalreadmissiondashboard)

## ## Key Findings

The analysis identified meaningful patterns associated with 30-day hospital readmissions:

- Patients with a higher burden of recorded conditions appeared more likely to be readmitted within 30 days.
- Longer hospital stays were associated with increased readmission risk, suggesting that admission complexity may influence outcomes.
- Demographic variation was observed across readmission groups, indicating that patient characteristics may contribute to different readmission patterns.
- The engineered features — age, length of stay, and number of conditions — provided a useful foundation for predicting readmission risk.
- A logistic regression model was able to distinguish between readmitted and non-readmitted encounters, demonstrating the value of structured clinical and demographic data for early risk identification.

## Project Impact

This project shows how healthcare data can be transformed into actionable insights that support:
- readmission risk stratification
- care management planning
- hospital quality improvement
- dashboard-based decision support


