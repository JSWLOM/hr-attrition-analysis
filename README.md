# HR Attrition Analysis & Prediction

## Overview
End-to-end data science project analyzing employee attrition patterns 
using the IBM HR Analytics dataset (1,470 employees, 35 features).
Includes exploratory data analysis, machine learning prediction, 
and an interactive Power BI dashboard.

## Key Findings
- Sales Representatives have the highest attrition rate at 39.8%
- Overtime workers leave at 3x the rate of non-overtime workers (30.5% vs 10.4%)
- StockOptionLevel is the #1 predictor of attrition
- Employees who left earned ~$2,000/month less than those who stayed
- Model achieved 79% accuracy with ROC-AUC of 0.72

## Tech Stack
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (Random Forest Classifier)
- Imbalanced-learn (SMOTE for class imbalance)
- Power BI (Interactive Dashboard)

## Project Structure
hr-attrition-analysis/
│
├── HR_Attrition_Analysis.ipynb  # Main analysis notebook
├── hr_attrition_clean.csv       # Cleaned dataset with risk scores
├── HR_Attrition_Dashboard.pbix  # Power BI dashboard file
├── dashboard_screenshot.png     # Dashboard preview
└── README.md                    # Project documentation

## Dashboard Preview
![Dashboard](Screenshot2026-03-17113005.png)

## Model Performance
| Metric | Score |
|--------|-------|
| Accuracy | 79% |
| ROC-AUC | 0.72 |
| Precision (Attrition) | 35% |
| Recall (Attrition) | 36% |

## Business Recommendations
1. Reduce mandatory overtime — highest single risk factor
2. Introduce stock options for entry-level roles
3. Focus retention efforts on Sales Representatives
4. Review compensation for employees earning below $3,000/month
