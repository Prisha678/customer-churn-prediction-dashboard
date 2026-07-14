# End-to-End Bank Customer Churn Analysis | Python, Machine Learning & Power BI

## Project Overview

Customer churn is a major challenge for banks as retaining existing customers is more cost-effective than acquiring new ones. This project develops an end-to-end customer churn analytics solution using Python, Machine Learning, and Power BI to identify customers at risk of leaving and recommend business actions to improve customer retention.
The project covers the complete analytics lifecycle, including data preprocessing, exploratory data analysis (EDA), feature engineering, predictive modeling, and interactive business dashboards.

## Business Objective

- Analyze customer churn behavior.
- Identify key factors driving churn.
- Build predictive machine learning models.
- Compare model performance.
- Visualize insights using Power BI.
- Recommend actionable customer retention strategies.

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Power BI
- Jupyter Notebook

**Final Model Selected:** Random Forest

Random Forest was selected because customer churn prediction prioritizes identifying churning customers (higher Recall) over maximizing overall Accuracy. It achieved the highest ROC-AUC while maintaining the best balance between precision and recall.

## Power BI Dashboard

### Executive Dashboard
<img width="602" height="337" alt="1  Executive dashboard" src="https://github.com/user-attachments/assets/6cbe360e-fec9-4d2b-8b48-18d3395ac6fd" />

### Customer Insights & Root Cause Analysis
<img width="597" height="337" alt="2  Root cause dashboard" src="https://github.com/user-attachments/assets/f7d89cba-71bf-4f4e-b3f2-d797f943b964" />

### Customer Retention Strategy & Action Plan
<img width="599" height="336" alt="3  Retention playbook" src="https://github.com/user-attachments/assets/9fc1e027-af9d-4e8d-97fd-c7a7595f9801" />

## Key Insights

- Customer age is the strongest predictor of churn.
- Inactive customers exhibit significantly higher churn.
- Germany records the highest churn among regions.
- Customers with 3–4 products show elevated churn risk.
- Balance and activity status strongly influence customer retention.

## Business Recommendations

- Target inactive customers with personalized retention campaigns.
- Prioritize high-risk customers identified by the Random Forest model.
- Offer loyalty benefits to senior customers.
- Develop region-specific retention strategies for Germany.
- Promote relevant banking products to engaged customers.
