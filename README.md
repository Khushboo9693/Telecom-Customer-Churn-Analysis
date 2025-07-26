# Telecom-Customer-Churn-Analysis

This project analyzes customer churn data to understand the patterns and factors leading to customer attrition. The notebook performs data cleaning, exploration, and visualization to gain insights.

---
**Filename:** `Customer Churn.csv`  
The dataset contains customer information including demographics, services subscribed, contract type, and whether they have churned.

---

## 🔍 Key Steps in the Notebook

### 1. Data Cleaning
- Replaces blank strings in `TotalCharges` with `0`
- Converts `TotalCharges` to float
- Checks for and handles missing or duplicate values
- Converts `SeniorCitizen` from 0/1 to "No"/"Yes"

### 2. Exploratory Data Analysis (EDA)
- Basic statistical summary using `describe()`
- Distribution of churn vs. non-churn using bar plots
- Checks for duplicates in `customerID`

### 3. Visualization
- Bar plots to analyze churn distribution
- (Optional) You can extend the notebook to include:
  - Churn by tenure or contract type
  - Correlation heatmaps
  - Pie charts or histograms for services usage

---

## ⚙️ Requirements

- pandas
- matplotlib
- seaborn
- numpy
