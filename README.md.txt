🧠 AI-Enabled Customer Segmentation & Churn Prediction System
🚀 Project Overview

This project builds a full-fledged AI-driven customer intelligence system using retail transaction data.
It combines customer segmentation, churn prediction, lifetime value estimation, and recommendation logic to generate actionable insights for business stakeholders.

Unlike basic analytics projects, this system goes beyond clustering to predict risk and recommend next-best actions.

🎯 Business Problem

Retail businesses often struggle to:
Identify high-value customers
Predict customer churn
Decide who to target and how


🧠 AI & Machine Learning Approach
1. Feature Engineering (Behavioral Modeling)

Built RFM+ features from raw transaction data:

Recency
Frequency
Monetary Value
Quantity

Age

2. Customer Segmentation (Unsupervised ML)

Applied K-Means clustering

Identified 4 meaningful customer segments

Balanced statistical validity with business interpretability

3. Churn Prediction (Supervised ML)

Created churn labels using behavioral inactivity

Trained Logistic Regression model

Generated churn probability & risk buckets

4. Customer Lifetime Value (CLV)

Built a regression-based CLV prediction model

Prioritized customers by future value

5. Recommendation Engine (Decision Intelligence)

Combined:

Segment
CLV
Churn risk
Generated Next-Best-Action recommendations for each customer

📊 Key Insights

Retail revenue is highly skewed — a small percentage of customers drive most revenue

Recently active customers are not always the highest value

High-value customers with rising churn probability require urgent retention actions

Young customers show long-term growth potential despite low current value

🛠️ Tech Stack

Python
Pandas, NumPy
Scikit-learn
Matplotlib, Seaborn

📈 Outputs

Customer segments with business interpretation

Churn probability for each customer

Predicted Customer Lifetime Value

Actionable recommendations ready for CRM or marketing use