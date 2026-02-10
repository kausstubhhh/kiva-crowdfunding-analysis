# Kiva Crowdfunding Data Analysis

## Overview
This project analyses global microfinance lending patterns using the **Kiva Crowdfunding dataset**.  
The aim is to understand how borrower characteristics, geographic factors, and socioeconomic conditions influence loan funding success and funding duration.

The analysis follows a complete data science pipeline:
- Data cleaning and integration
- Exploratory data analysis (EDA)
- Feature engineering
- Predictive modelling
- Interactive visualisation

---

## Dataset
The project uses publicly available Kiva datasets (2005–2017), covering over **586,000 loans** across **80+ countries**, enriched with Multidimensional Poverty Index (MPI) data.

**Key data sources:**
- Loan-level data (amounts, sectors, borrower demographics)
- Regional poverty indicators (MPI)
- Development themes associated with each loan

---

## Objectives
- Explore global and regional microfinance lending patterns  
- Analyse relationships between borrower attributes, poverty levels, and funding outcomes  
- Build machine learning models to:
  - Predict funding success (classification)
  - Estimate funding duration (regression)
- Develop interactive visualisations for insight-driven analysis  

---

## Methods & Tools
- **Languages:** Python, SQL  
- **Libraries:** pandas, numpy, matplotlib, seaborn, plotly, scikit-learn  
- **Models:** Random Forest Classifier & Regressor  
- **Evaluation:** ROC-AUC, RMSE  

---

## Key Insights
- Agriculture, Food, and Retail dominate global microfinance lending  
- Loans to female borrowers show marginally higher funding success  
- Funding duration varies significantly by region and sector  
- Predictive models achieved strong performance (ROC-AUC ≈ 0.89)

---

## Repository Structure
- `notebooks/` – Jupyter notebooks with full analysis  
- `reports/` – Final project report (PDF)  
- `data/` – Raw and cleaned datasets  
- `outputs/` – Generated figures and summary tables  

---

## Disclaimer
This project was completed as part of an academic coursework submission.  
The analysis is intended for educational and research purposes only.
