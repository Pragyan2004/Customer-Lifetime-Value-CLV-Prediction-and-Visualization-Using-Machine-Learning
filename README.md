# Customer-Lifetime-Value-CLV-Prediction-and-Visualization-Using-Machine-Learning

# Overview

This project focuses on predicting the Customer Lifetime Value (CLV) using historical transaction data from an online retail store. It uses machine learning regression models to predict the future value of customers and provides insightful business visualizations for analysis.

# Dataset

Source: https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset?resource=download

File Used: online_retail_II.xlsx


# Key Business Metrics

Recency: Days since the customer's last purchase.

Frequency: Number of unique invoices (purchases).

Monetary: Total spending (CLV).

Country: Customer location.

# Technologies Used

Python

pandas, numpy, matplotlib, seaborn

scikit-learn, xgboost

Jupyter Notebook or .py script

Visualization with matplotlib

# Project Workflow

Step 1: Data Cleaning
Step 2: Feature Engineering
Step 3: Model Training & Evaluation

# Visualizations Included

Comparison (R² and RMSE)

![Screenshot 2025-06-05 084658](https://github.com/user-attachments/assets/830ad032-b716-4e36-bea7-79d4a8943a52)

Actual vs Predicted (Gradient Boosting)

![Screenshot 2025-06-05 084507](https://github.com/user-attachments/assets/4b05c8ea-b996-4201-a113-9bfc8cf17eb4)

Feature Importance

![Screenshot 2025-06-05 084516](https://github.com/user-attachments/assets/c42a478a-0287-4845-93f0-b7992de8c20c)

CLV Distribution

![Screenshot 2025-06-05 084735](https://github.com/user-attachments/assets/efc8dc22-cee4-4988-bc82-7883ede4f73e)

Recency vs CLV

![Screenshot 2025-06-05 083736](https://github.com/user-attachments/assets/5cb32335-8605-441b-8185-81fa3f1c902c)

Frequency vs CLV

![Screenshot 2025-06-05 083751](https://github.com/user-attachments/assets/a6fc87df-0e4e-4ca6-bdf0-506bdf030c2c)

Top 10 Countries by Customers

![Screenshot 2025-06-05 083757](https://github.com/user-attachments/assets/d1f478a1-0235-4eb7-a179-737cc38357f1)

Monthly Revenue Trend

![Screenshot 2025-06-05 083806](https://github.com/user-attachments/assets/a334c757-9081-4142-9a2c-57f4303f2087)

Top 10 Customers by CLV

![Screenshot 2025-06-05 083813](https://github.com/user-attachments/assets/0ba36987-914c-40fc-9a5e-47c17334f85f)

# Key Learnings
How to clean and transform raw transaction data for ML modeling.

Understand RFM (Recency, Frequency, Monetary) metrics.

Build interpretable models to predict CLV.

Visualize actionable customer insights for business strategy.

# Future Work
Deploy as a web app (Flask / Streamlit)

Integrate with customer segmentation (KMeans / RFM Score)

AutoML / Hyperparameter tuning

Real-time dashboard with Dash or Power BI
