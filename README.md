# HR Employee Attrition Analysis

## Business Problem
A company is experiencing 16.1% annual employee attrition.
This project identifies which departments, roles, and factors
drive attrition — enabling HR to take targeted retention action.

## Key Findings
- Overall attrition rate: **16.1%** (237 out of 1,470 employees)
- **Sales department** has the highest attrition at ~21%
- **Sales Representatives** have ~40% attrition — highest of any role
- Employees working **overtime are 3x more likely** to leave
- Employees who left earned **~$2,000/month less** on average
- **New employees (0–2 years)** have the highest attrition risk

## Dashboard Preview
![Dashboard](HR_Attrition_Dashboard.pdf)

## Tools Used
- **Python** — pandas, seaborn, matplotlib, scikit-learn
- **Power BI** — interactive dashboard with DAX measures
- **Google Colab** — development environment

## Project Structure
| File | Description |
|------|-------------|
| `HR_Attrition_Analysis.ipynb` | Full analysis notebook |
| `hr_attrition_cleaned.csv` | Cleaned dataset |
| `HR_Attrition_Dashboard.pdf` | Power BI dashboard export |
| `*.png` | EDA charts |

## Model Performance
- Algorithm: Logistic Regression
- Accuracy: ~87%
- Key attrition drivers: OverTime, MonthlyIncome, JobSatisfaction, YearsAtCompany

## Dataset
IBM HR Analytics Employee Attrition Dataset
1,470 employees, 35 features
Source: [Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
