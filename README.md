# 🧠 AI-Enabled Customer Segmentation & Churn Prediction System  
### 📊 Turning Retail Data into Predictive Business Intelligence

## 🚀 Project Overview

This project builds a **full-fledged AI-driven customer intelligence system** using retail transaction data.  
It goes beyond traditional analytics by combining **behavioral modeling, predictive machine learning, and decision intelligence** to generate actionable insights for business stakeholders.

**Key Capabilities:**
- Customer Segmentation
- Churn Prediction
- Customer Lifetime Value (CLV) Estimation
- AI-driven Next-Best-Action Recommendations

🎯 **Objective:**  
Enable **proactive, data-backed decision-making** for marketing, retention, and revenue optimization teams.

## 🎯 Business Problem

Retail organizations often struggle to answer critical questions:

- 💎 Who are the most valuable customers?
- ⚠️ Which customers are at risk of churning?
- 🎯 Who should be targeted, when, and with what incentive?

Most analytics systems explain **what happened**.  
This system predicts **what will happen next — and what to do about it**.

## 🔍 Feature Engineering (Behavioral Modeling)

Customer behavior is modeled using **RFM + features** derived from transaction history:

| Feature | Description |
|------|------|
| 🕒 Recency | Days since last purchase |
| 🔁 Frequency | Number of unique purchases |
| 💰 Monetary | Total spend |
| 📦 Quantity | Total items purchased |

These features capture **engagement intensity, loyalty, and revenue contribution**.

## 🧩 Customer Segmentation (Unsupervised Learning)

- Algorithm: **K-Means Clustering**
- Optimal number of clusters selected using:
  - Elbow Method
  - Business interpretability
- Final choice: **4 meaningful customer segments**

### 🧠 Segment Interpretation

| Segment | Description | Business Action |
|------|------|------|
| 💎 High-Value Loyalists | High spend, recent activity | Retain & reward |
| 🌱 Growth Customers | Low spend, high recency | Upsell & nurture |
| ⚠️ At-Risk High Value | High spend, inactive | Immediate retention |
| 💤 Low-Value Dormant | Low spend, inactive | Reactivate or deprioritize |

📌 **Key Insight:**  
Retail revenue is **highly skewed**, where a small percentage of customers drive the majority of revenue — a classic long-tail distribution.

## ⚠️ Churn Prediction (Supervised Learning)

- Churn defined using **behavioral inactivity thresholds**
- Model used: **Linear Regression**
- Outputs:
  - Churn probability score (0–1)
  - Risk classification: Low / Medium / High

🎯 **Why this matters:**  
Not all churn is equal; losing a high-CLV customer has a significantly higher business impact.

## 💰 Customer Lifetime Value (CLV) Estimation

- Built a regression-based CLV prediction model
- Combines:
  - Historical spend
  - Purchase frequency
  - Engagement patterns
- Enables **prioritization of retention and acquisition spend**

📈 Focus shifts from **short-term transactions** to **long-term customer value**.

## 🤖 Recommendation Engine (Next-Best-Action)

An AI-driven decision layer combines:

- Customer Segment
- Churn Probability
- Predicted CLV

### 🧠 Example Recommendations

| Customer Profile | Recommended Action |
|------|------|
| High CLV + High Churn | Exclusive loyalty rewards & early product access |
| Growth Segment | Personalized product bundles & upsell offers |
| Low CLV + High Churn | Discount coupons & gamified rewards |
| Loyal Customers | Win-back offers & reactivation discounts |

📌 **Output:**  
Actionable recommendations ready for CRM, marketing automation, or sales teams.

## 📊 Key Insights for Stakeholders

- 🔥 Retail revenue is **highly concentrated** among a small customer base
- 🕒 Recent activity does not always correlate with high value
- ⚠️ High-value customers with rising churn risk require **urgent intervention**
- 🌱 Younger and low-value customers show strong **long-term growth potential**


## 🛠️ Tech Stack

- **Programming:** Python  
- **Data Processing:** Pandas, NumPy  
- **Machine Learning:** Scikit-learn  
- **Visualization:** Matplotlib, Seaborn  
