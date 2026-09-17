# Eintracht Frankfurt — Fan Analytics & Churn Prediction

Portfolio project analysing fan engagement and predicting churn for Eintracht Frankfurt.

## Objective
Demonstrate end-to-end data analytics: data generation, SQL/Python cleaning, KPI development, segmentation, predictive modelling, and Power BI dashboards.

## Tools
Python, pandas, scikit-learn, SQL, Power BI (DAX), Git

## Data
Synthetic dataset of 10,000 fan records generated with `src/generate_data.py`.
Simulates realistic fan behaviour: attendance, engagement, spend, and churn.
**Note:** synthetic data is used because real fan data is not publicly available. The methodology mirrors a real club analytics workflow.

## Project Steps
1. Generate synthetic fan data
2. Build KPIs (engagement score, CLV, total spend)
3. Segment fans with K-means (Casual, Loyal, Premium, At Risk)
4. Predict churn with logistic regression
5. Visualise results in Power BI

## Key Results
- 4 fan segments identified
- Churn model accuracy: ~75% (see `src/churn_model.py` output)
- At-risk segment identified with lowest engagement and CLV

## Dashboard
! I will refer you to test it on PowerBI the DAX(on the DAX section)

## How to Run
```bash
pip install -r requirements.txt
python src/generate_data.py
python src/build_features.py
python src/segmentation.py
python src/churn_model.py
```
