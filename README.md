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
<img width="1920" height="867" alt="class balance chart" src="https://github.com/user-attachments/assets/c29e3eaf-f3e6-4a25-baf2-0deea98e3d06" />


### Top Equipment by High Downtime Rate
<img width="1920" height="876" alt="top equipment by high downtime rate" src="https://github.com/user-attachments/assets/fbe8e1c7-1dd7-4588-b300-97b689c069e0" />


### Confusion Matrix
<img width="1920" height="813" alt="confusion matrix" src="https://github.com/user-attachments/assets/5bbbce3e-db5a-4fe5-adeb-d99a32e91dd0" />


### ROC Curve
<img width="1920" height="878" alt="ROC curve" src="https://github.com/user-attachments/assets/03f4f405-91a4-4795-9806-47abd9e3b038" />


### Feature Importance
<img width="1920" height="872" alt="top 15 feature importance" src="https://github.com/user-attachments/assets/8846912f-dd3e-405f-9abd-26bfbb519cc1" />


### Highest-Risk Events
<img width="1920" height="925" alt="highest-risk events table" src="https://github.com/user-attachments/assets/60ff197a-d6d6-46c6-a3be-73e8b27ea46c" />


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
