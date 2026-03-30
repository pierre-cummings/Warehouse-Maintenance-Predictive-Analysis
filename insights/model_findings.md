# Model Findings

## Overview
This document summarizes the main findings from the Warehouse Maintenance Predictive Analysis project.

The purpose of this project was to predict whether a warehouse maintenance event would result in high downtime, defined as more than 24 hours.

---

## Key Findings

### 1. Certain equipment types showed higher downtime risk
Equipment categories such as conveyors, robots, case erectors, and tape machines showed stronger patterns of high downtime events.

### 2. Issue type was an important predictor
Specific maintenance issue categories were more likely to result in longer downtime than others, making them useful predictors in the model.

### 3. Repair ownership influenced downtime outcomes
Vendor-supported repairs often aligned with longer downtime patterns compared to in-house repairs, which may reflect response time differences or repair complexity.

### 4. Location and operational context mattered
Warehouse location, internal work area, and timing-related features also contributed to downtime risk.

### 5. The model supports proactive maintenance decisions
This project demonstrates how historical maintenance data can be used to identify high-risk events earlier and support better repair prioritization.

---

## Business Value
This model can help operations and maintenance teams:
- identify high-risk work orders faster
- prioritize response to events likely to create major downtime
- improve preventive maintenance focus
- support reliability planning with data

---

## Next Steps
Future improvements could include:
- predicting exact downtime hours
- predicting operations-affected failures
- adding asset-level maintenance history
- building a Power BI dashboard from scored results
