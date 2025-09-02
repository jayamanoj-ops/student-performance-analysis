
# Student Performance Dashboard Pipeline

##  Overview
This project generates realistic VTU-style synthetic student performance data, trains a machine learning model to predict academic risk, and outputs **Power BI-ready CSVs** for building an interactive academic dashboard.

##  Features
- Synthetic dataset for 5 engineering departments (CSE, ISE, ECE, EEE, MECH)
- 25+ engineered features from attendance, assessments, and LMS activity
- ML model (XGBoost / RandomForest) for risk prediction
- Early warning alerts and personalized recommendations
- Aggregated CSVs for direct use in Power BI:
  - `summary_metrics.csv` – KPI cards
  - `risk_trend.csv` – Risk trend line chart
  - `risk_by_dept_course.csv` – Risk explorer matrix
  - `student_360.csv` – Student profile table

## Project Structure
student-performance-dashboard/ 
│
├── vtu_pipeline_final_fixed.py # Main Python pipeline
├── requirements.txt # Python dependencies 
├── README.md # Project documentation 
└── data/ # (Optional) Sample CSV outputs
