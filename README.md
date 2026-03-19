# Customer Churn Analysis for SaaS Subscription Platform
### 📌 Project Overview

This project focuses on analyzing customer churn behavior in a SaaS-based subscription platform. The goal is to identify patterns behind user cancellations, measure retention performance, and provide actionable insights to reduce churn and improve customer lifetime value.

The analysis is performed using SQL Server for data processing and Power BI for visualization.

### 🎯 Objectives

Calculate and analyze monthly churn rate

Identify high-risk customer segments

Measure customer retention and engagement trends

Evaluate revenue impact due to churn

Provide data-driven recommendations for improving retention

### 📂 Dataset Description

The dataset simulates a real-world SaaS business with 10,000 users and includes:

1. Users Table

User ID

Signup Date

Country

Acquisition Channel (Ads, Organic, Referral, Social)

Plan Type (Monthly / Yearly)

Age

2. Subscriptions Table

Subscription Start & End Date

Status (Active / Cancelled)

Monthly Price

3. Payments Table

Payment Date

Amount

Payment Status (Success / Failed)

4. User Activity Table

Activity Date

Session Duration

Feature Usage

🛠️ Tools & Technologies

SQL Server – Data generation, transformation, and analysis

Power BI – Dashboard development and visualization

DAX – KPI calculations and metrics


### 📊 Key Analysis Performed
1. Monthly Churn Rate

Calculated churn percentage across months

<img width="447" height="332" alt="image" src="https://github.com/user-attachments/assets/d08b3d55-7cec-454c-90c3-982b4dacc6c6" />

Identified fluctuations and peak churn periods

<img width="339" height="158" alt="image" src="https://github.com/user-attachments/assets/0b260feb-8cb4-472f-985a-ddd7c33d34a7" />

2. Churn by Acquisition Channel

<img width="310" height="133" alt="image" src="https://github.com/user-attachments/assets/352e3fe9-983e-4ba6-a716-75297fe91843" />


3. Churn by Plan Type

Monthly plans showed higher churn compared to yearly subscriptions

<img width="457" height="80" alt="image" src="https://github.com/user-attachments/assets/4bbf686f-5813-4610-8e87-c4e16069bbcb" />

4. Engagement Analysis

Compared session activity between active and churned users

<img width="341" height="82" alt="image" src="https://github.com/user-attachments/assets/e129883a-6c89-4e60-841c-47f80165732d" />

Found lower engagement strongly correlated with churn:

<img width="499" height="105" alt="image" src="https://github.com/user-attachments/assets/3bd8027d-ab15-4501-816e-2a6bf8b1619c" />

5. Revenue Impact

Estimated revenue loss due to customer churn

<img width="229" height="63" alt="image" src="https://github.com/user-attachments/assets/c555780f-6fc7-454f-9765-3c9ed2743186" />


6. Cohort Analysis

Analyzed retention trends based on user signup month

<img width="398" height="678" alt="image" src="https://github.com/user-attachments/assets/641f998a-2dba-4ef5-a400-32730cc33617" />


### 📈 Key Insights

Average churn rate observed: ~30%, indicating significant customer loss

Users with low engagement were more likely to churn

Monthly subscription users had higher churn compared to yearly users

Certain acquisition channels contributed to lower retention

Failed payments and inactivity acted as early churn indicators

### 📊 Dashboard Features (Power BI)

Monthly churn trend visualization

Active vs churned user comparison

Revenue and LTV metrics

Engagement analysis

Channel-wise performance breakdown

Cohort retention heatmap

### 💡 Business Recommendations

Improve user onboarding and engagement strategies

Identify high-risk users early and target them with retention campaigns

Optimize marketing spend by focusing on high-retention channels

Offer incentives for long-term subscription plans

Address payment failures proactively
