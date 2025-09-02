
# Student Performance Dashboard Pipeline

##  Overview
This project generates realistic VTU-style student performance data, trains a machine learning model to predict academic risk, and outputs **Power BI-ready CSVs** for building an interactive academic dashboard.

##  Features
- Dataset for 5 engineering departments (CSE, ISE, ECE, EEE, MECH)
- 25+ engineered features from attendance, assessments, and LMS activity
- ML model (XGBoost / RandomForest) for risk prediction
- Early warning alerts and personalized recommendations
- Aggregated CSVs for direct use in Power BI:
  - `summary_metrics.csv` – KPI cards
  - `risk_trend.csv` – Risk trend line chart
  - `risk_by_dept_course.csv` – Risk explorer matrix
  - `student_360.csv` – Student profile table

## Usage
Run the pipeline:
final.ipynb
This will generate raw data, model outputs, and Power BI-ready CSVs in the project folder.
## Power BI Integration
- Open Power BI Desktop.
- Load the four aggregate CSVs (summary_metrics.csv, risk_trend.csv, risk_by_dept_course.csv, student_360.csv).
- Build visuals
