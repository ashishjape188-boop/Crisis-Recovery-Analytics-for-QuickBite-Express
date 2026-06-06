# 🚀 Crisis Recovery Analytics for QuickBite Express

> AI-Powered Customer Intelligence, Churn Prediction, Revenue Forecasting, and Business Recovery Analytics for a Food Delivery Platform.

---

## 📌 Project Overview

QuickBite Express experienced a major operational crisis caused by food safety incidents and delivery service disruptions, resulting in declining customer satisfaction, increased cancellations, customer churn, and revenue loss.

This project develops an end-to-end **AI-driven Crisis Recovery Analytics Framework** to help the company:

- Understand customer behavior during and after the crisis
- Predict customer churn before it occurs
- Identify key revenue drivers
- Simulate recovery strategies and estimate revenue uplift
- Analyze restaurant and delivery partner performance
- Generate actionable business recommendations

---

## 🎯 Business Objectives

- Measure the impact of the crisis on business performance
- Segment customers based on purchasing behavior
- Predict customer churn using Machine Learning
- Identify the strongest drivers of revenue
- Quantify revenue recovery opportunities
- Optimize restaurant partnerships
- Improve delivery partner performance

---

## 📊 Dataset Information

The project uses multiple operational datasets:

| Dataset | Description |
|----------|-------------|
| Orders | Transaction details, revenue, cancellations |
| Customers | Customer profiles and registration information |
| Restaurants | Restaurant details and preparation times |
| Delivery Partners | Rider information and ratings |
| Reviews & Ratings | Customer satisfaction metrics |

### Dataset Size

- 500,000+ Records
- Multi-table relational structure
- Simulated food delivery platform operations

---

## 🛠️ Tech Stack

### Programming Languages
- Python
- SQL

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

### Machine Learning
- K-Means Clustering
- Random Forest Classifier
- Random Forest Regressor
- GridSearchCV

---

## 📂 Project Workflow

```text
Data Collection
      ↓
Data Cleaning & Preprocessing
      ↓
Feature Engineering
      ↓
Exploratory Data Analysis
      ↓
Customer Segmentation
      ↓
Churn Prediction
      ↓
Revenue Driver Analysis
      ↓
Revenue Recovery Simulation
      ↓
Restaurant Intelligence
      ↓
Delivery Partner Intelligence
      ↓
Executive Dashboard
      ↓
Business Recommendations
```

---

## 📈 Phase 1: Data Cleaning & Preprocessing

### Tasks Performed

- Removed duplicate records
- Handled missing values
- Converted datetime columns
- Merged multiple datasets
- Created business-focused features

### Deliverable

A clean and analysis-ready dataset suitable for machine learning and business intelligence.

---

## 📊 Phase 2: Exploratory Data Analysis (EDA)

### Analysis Conducted

- Revenue trends
- Customer behavior analysis
- Order volume trends
- Delivery performance
- Restaurant performance
- Cancellation patterns

### Key Findings

- Significant decline in orders during crisis periods
- Increased cancellation rates
- Higher delivery delays during operational disruption

---

## 🤖 Phase 3: Customer Segmentation

### Algorithm Used

**K-Means Clustering (K = 3)**

### Features

- Total Spend
- Order Frequency
- Active Months
- Customer Tenure
- Cancellation Rate

### Segments Identified

#### Cluster 0 – High Value Customers
- Frequent orders
- Higher spending
- Lower churn risk

#### Cluster 1 – At-Risk Customers
- High cancellation behavior
- Low engagement

#### Cluster 2 – Dormant Customers
- Few purchases
- Long inactivity periods

### Business Impact

Supports targeted retention and customer engagement strategies.

---

## 🔮 Phase 4: Customer Churn Prediction

### Churn Definition

A customer is considered churned if:

```python
days_since_last_order > 90
```

### Model

**Random Forest Classifier**

### Hyperparameter Tuning

```python
GridSearchCV
```

### Model Performance

| Metric | Score |
|----------|---------|
| Training Accuracy | 97.36% |
| Test Accuracy | 89.67% |
| Precision | 94% |
| Recall | 93% |

### Business Impact

Identifies customers likely to stop ordering, enabling proactive retention campaigns.

---

## 💰 Phase 5: Revenue Driver Analysis

### Model

**Random Forest Regressor**

### Target Variable

```python
total_spend
```

### Top Revenue Drivers

1. Order Frequency
2. Favorite Restaurant Ratio
3. Customer Cancellation Rate
4. Active Months
5. Customer Tenure

### Key Insight

Customer engagement metrics are the strongest drivers of revenue growth.

---

## 📈 Phase 6: Revenue Recovery Simulation

A recovery scenario was simulated using the trained revenue prediction model.

### Recovery Assumptions

| Driver | Improvement |
|----------|------------|
| Order Frequency | +20% |
| Favorite Restaurant Ratio | +10% |
| Active Months | +20% |
| Cancellation Rate | -30% |

### Results

| Metric | Value |
|----------|----------|
| Current Crisis Revenue | ₹2.68M |
| Projected Revenue | ₹2.77M |
| Revenue Growth | 3.16% |
| Incremental Revenue Gain | ₹84.9K |

### Business Impact

Demonstrates how targeted improvements can increase revenue without acquiring new customers.

---

## 🍽️ Phase 7: Restaurant Intelligence

### Restaurant Segmentation

| Segment | Revenue Threshold |
|----------|------------------|
| Elite | > ₹5,000 |
| High | ₹2,500 – ₹5,000 |
| Medium | ₹1,500 – ₹2,500 |
| Low | < ₹1,500 |

### Analysis Performed

- Top Revenue Restaurants
- Top Restaurants by City
- Restaurant Tier Classification
- Revenue Contribution Analysis

### Business Impact

Helps prioritize strategic partnerships and promotional investments.

---

## 🚴 Phase 8: Delivery Partner Intelligence

### Metrics Used

- Total Deliveries
- Delivery Delay
- SLA Breach Rate
- On-Time Delivery %
- Average Rating

### Partner Segments

- Star
- Reliable
- Average
- Needs Improvement

### Analysis Performed

- Partner Performance Evaluation
- City-Wise Delivery Analysis
- Bonus Eligibility Framework
- Operational Improvement Recommendations

### Business Impact

Improves delivery efficiency and customer experience.

---

## 🤖 AI Components

### Customer Segmentation
- K-Means Clustering

### Churn Prediction
- Random Forest Classification

### Revenue Forecasting
- Random Forest Regression

### Revenue Recovery Simulation
- AI-based Scenario Modeling

### Explainable AI
- Feature Importance Analysis

---

## 📊 Executive Dashboard

The project concludes with an executive dashboard containing:

- Customer Segmentation Insights
- Churn Risk Analysis
- Revenue Forecasting
- Revenue Recovery Simulation
- Restaurant Intelligence
- Delivery Partner Intelligence
- Strategic Recommendations

---

## 🎯 Key Business Recommendations

### Customer Growth
- Increase order frequency through loyalty programs
- Launch churn prevention campaigns

### Revenue Growth
- Focus on high-frequency customers
- Promote restaurant loyalty

### Restaurant Strategy
- Strengthen partnerships with Elite restaurants
- Improve visibility for high-performing restaurants

### Delivery Operations
- Reward top-performing delivery partners
- Reduce delivery delays through incentive programs

### City-Level Strategy
- Invest in high-performing markets
- Develop recovery plans for underperforming cities

---

## 📌 Key Outcomes

✅ Segmented customers into actionable behavioral groups

✅ Achieved **89.67% churn prediction accuracy**

✅ Identified the strongest drivers of customer revenue

✅ Quantified crisis recovery opportunities using AI

✅ Developed restaurant and delivery partner intelligence frameworks

✅ Generated actionable recommendations for customer retention, operational optimization, and revenue growth

---

## 👨‍💻 Author

**Ashish Jape**

Data Analytics | Machine Learning | Business Intelligence

---

### ⭐ If you found this project useful, consider giving it a star!
