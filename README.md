# Telecom Customer Churn Prediction (ML)

A machine learning project that predicts whether a telecom customer is likely to leave (churn), so the business can act early with targeted retention offers.

**Live Dashboard:** [https://telecom-customer-churn-prediction-ml-1.onrender.com](https://telecom-customer-churn-prediction-ml-1.onrender.com)

---

## Live Demo

Try the deployed dashboard here: [Telecom Churn Prediction Dashboard](https://telecom-customer-churn-prediction-ml-1.onrender.com)

> Note: The app is hosted on Render's free tier, so the first load may take 30-60 seconds if the service has been idle.

<!-- TODO: Add a screenshot of the dashboard, e.g. ![Dashboard Preview](images/dashboard.png) -->

## Problem Statement

Customer churn directly hurts revenue in the highly competitive telecom industry, and acquiring a new customer usually costs far more than keeping an existing one. This project builds a classification model that flags customers at high risk of churning based on their demographics, account details and the services they use.

## Dataset

<!-- TODO: Confirm this matches the dataset you used -->
- **Source:** [Telco Customer Churn - Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Size:** ~7,043 customers, 21 columns
- **Target:** `Churn` (Yes / No)
- **Feature groups:**
  - *Demographics:* gender, senior citizen, partner, dependents
  - *Services:* phone, multiple lines, internet, online security, backup, tech support,
