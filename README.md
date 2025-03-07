# TelecomChurnAnalysis-PYTHON-EDA

#### **Objective**  
The notebook analyzes telecom customer churn to identify factors influencing customer retention.

#### **Technologies Used**
- **Python Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`
- **Data Processing**:
  - Reads customer churn dataset (`Customer Churn.csv`)
  - Handles missing values (`TotalCharges` column)
  - Converts categorical data (e.g., `SeniorCitizen` from 0/1 to Yes/No)
  - Removes duplicates
- **Exploratory Data Analysis (EDA)**:
  - **Churn Distribution**: Count plots and pie charts show that **26.54% of customers churned**.
  - **Key Findings**:
    - **Senior Citizens** have a higher churn rate.
    - **Short-tenure customers (1-2 months)** are more likely to churn.
    - **Month-to-month contracts** have higher churn compared to 1- or 2-year contracts.
    - Customers without **Online Security, Tech Support, and Streaming Services** tend to leave.

This analysis provides insights into customer behavior and factors affecting churn.
