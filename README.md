# startup_profit_analysis

## Overview
This project studies how R&D, administration, and marketing spending relate to profit
in a dataset of 50 startups, and builds a model to estimate profit.

## Dataset
- 50 records, 5 columns: RD_Spend, Administration, Marketing_Spend, State, Profit
- States: California, Florida, New York
- Quality check: 0 missing values and 0 duplicate rows

## Approach
1. Data quality checks and summary statistics
2. Exploratory analysis and state-wise profit comparison
3. Correlation analysis
4. Multiple Linear Regression (80/20 train-test split, random_state=42)
5. Power BI dashboard

## Key Findings
- R&D spend has a strong correlation with profit (r = 0.973)
- Marketing spend has a positive correlation (r = 0.748)
- Administration spend has a weak correlation (r = 0.201)
- The model achieved R² ≈ 0.90 on the test set (MAE 6,979; RMSE 8,996)
- New York has the largest total profit in this sample

## Limitations
Small dataset (50 records) and a single train-test split. Correlation does not
prove causation.

## Tools
Python, Pandas, NumPy, Matplotlib, Scikit-learn, Jupyter Notebook, Power BI

## Files
- `Profit_Analysis.ipynb`: analysis and model
- `startup dashboard.pbix`: Power BI dashboard
- Report and presentation (PDF/PPTX)

- <img width="1920" height="1080" alt="startup_profit_dashboard" src="https://github.com/user-attachments/assets/b819c25d-ab44-4de1-ab41-3cf20dad8e88" />


<img width="1323" height="745" alt="startup_profit_dashboard_cropped" src="https://github.com/user-attachments/assets/6cb0419e-0cfe-408d-ae6c-fa2f564012a7" />

