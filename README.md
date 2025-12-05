# EMI_predict
The EMIPredict AI - Intelligent Financial Risk Assessment Platform is a FinTech project designed to solve the critical issue of poor financial planning and inadequate risk assessment for loan applicants.


The project aims to build a comprehensive financial risk assessment platform to address the critical issue of people struggling to pay EMI due to poor financial planning and inadequate risk assessment. The objective is to provide data-driven insights for better loan decisions.

# Key Deliverables & Features

The platform is designed to deliver:

Dual ML Problem Solving: It tackles both a Classification problem (predicting EMI eligibility: Eligible, High_Risk, Not_Eligible) and a Regression problem (predicting the maximum safe monthly EMI amount).

Real-time Risk Assessment: It utilizes a large dataset of 400,000 financial records for real-time predictions.

MLflow Integration: It incorporates MLflow for organized experiment tracking, model comparison, and version control (Model Registry).

Production Deployment: The final application is a multi-page, interactive web application developed with Streamlit and deployed on Streamlit Cloud.

Comprehensive Data: It uses 22 financial and demographic variables for advanced feature engineering.

# High-Level Approach

# The development process follows a structured 7-step approach:
Data Loading and Preprocessing: Loading 400,000 records, cleaning data, and creating train-test-validation splits.

Exploratory Data Analysis: Analyzing eligibility distributions, correlations, and generating statistical summaries.

Feature Engineering: Creating derived financial ratios (e.g., debt-to-income) and risk scoring features.

Machine Learning Model Development: Training a minimum of Classification Models (e.g., Logistic Regression, Random Forest, XGBoost) and Regression Models (e.g., Linear Regression, Random Forest, XGBoost).

Model Selection and MLflow Integration: Logging all experiments with MLflow, comparing performance metrics, and selecting the best models.

Streamlit Application Development: Building the multi-page web application with real-time prediction and visualization components.

Cloud Deployment and Production: Deploying the application on Streamlit Cloud with an automated GitHub pipeline.

# Business Impact

# The platform is expected to:
Financial Institutions: Automate loan approval processes and reduce manual underwriting time by 80%.

FinTech Companies: Provide instant EMI eligibility checks and automated risk scoring.

Banks and Credit Agencies: Offer data-driven loan amount recommendations and improve portfolio risk management.
