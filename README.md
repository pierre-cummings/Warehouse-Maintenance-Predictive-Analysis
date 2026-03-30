# Warehouse Maintenance Predictive Analysis

## Project Overview
This project uses Python and Machine Learning to predict whether a warehouse maintenance event is likely to result in high downtime.

The goal was to move beyond descriptive maintenance reporting and build a predictive model that can help identify which maintenance events may require faster escalation or preventive action.

A high downtime event in this project is defined as a maintenance event with more than 24 hours of downtime.

---

## Tools Used
- Python
- pandas
- scikit-learn
- Jupyter Notebook
- GitHub

---

## Project Goal
Build a predictive maintenance model to classify whether a maintenance event will become a high downtime event based on:

- equipment type
- issue type
- warehouse location
- in-house location
- department
- repair ownership
- repair provider
- safety and operations flags
- timing features

---

## Model Workflow
The notebook follows these steps:

1. Load and inspect the data  
2. Convert date columns  
3. Create the target variable  
4. Explore downtime risk patterns  
5. Select features  
6. Encode categorical variables  
7. Train a Random Forest model  
8. Evaluate model performance  
9. Review feature importance  
10. Score maintenance events by downtime risk  

---

## Target Variable
The model predicts:

- `1` = High downtime event (more than 24 hours)
- `0` = Not high downtime event (24 hours or less)

---

## Key Outputs
This project includes:
- class balance analysis
- exploratory downtime risk charts
- confusion matrix
- ROC curve
- feature importance chart
- highest-risk maintenance event review

---

## Dashboard / Visual Preview

### Class Balance
![Class Balance](images/class_balance.png)

### Top Equipment by High Downtime Rate
![Top Equipment by High Downtime Rate](images/top_equipment_high_downtime_rate.png)

### Confusion Matrix
![Confusion Matrix](images/confusion_matrix.png)

### ROC Curve
![ROC Curve](images/roc_curve.png)

### Feature Importance
![Feature Importance](images/feature_importance.png)

### Highest-Risk Events
![Highest-Risk Events](images/high_risk_events_table.png)

---

## Repository Structure
```text
warehouse-maintenance-predictive-analysis/
│
├── data/
│   └── warehouse_operations_dataset_v2.csv
│
├── notebooks/
│   └── warehouse_maintenance_predictive_analysis_v2.ipynb
│
├── images/
│   ├── class_balance.png
│   ├── top_equipment_high_downtime_rate.png
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   ├── feature_importance.png
│   └── high_risk_events_table.png
│
├── insights/
│   └── model_findings.md
│
└── README.md
