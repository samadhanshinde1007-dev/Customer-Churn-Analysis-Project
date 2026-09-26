# Customer-Churn-Analysis-Project
# Customer Churn Analysis & Predictive Analytics Dashboard

## 1. Project Title

**Customer Churn Analysis & Predictive Analytics Dashboard**

## 2. Short Description / Purpose

An end-to-end data analytics and predictive modeling solution designed to analyze customer retention, identify key churn drivers, and proactively detect at-risk customers. By combining **MySQL** database querying, a **Random Forest Machine Learning model**, and an interactive **Power BI dashboard**, this project transforms raw customer data into actionable business intelligence—enabling targeted retention strategies to reduce revenue loss.

## 3. Tech Stack

* **Database Management:** MySQL (Data extraction, transformation, cleaning, and aggregation)
* **Machine Learning & Predictive Modeling:** Python (Scikit-Learn - Random Forest Classifier)
* **Business Intelligence & Visualization:** Microsoft Power BI Desktop
* **Analytical Calculations:** Power Query ETL & DAX (Data Analysis Expressions)

## 4. Data Source

* Telecom Customer Churn Dataset (Processed and managed in MySQL)

## 5. Features & Highlights

### 📊 Historical Churn Summary & KPIs

* **Core KPI Metrics:** Real-time tracking of **Total Customers (6K)**, **New Joiners (411)**, **Total Churn (2K)**, and overall **Churn Rate (27.0%)**.


* **Demographic Dissection:** Churn breakdown by gender (64.15% female churners) and age groups, highlighting elevated churn among customers aged > 50 (31.6% churn rate).


* **Contract & Payment Insights:** Analysis revealing higher attrition in **Month-to-Month contracts (46.5%)** vs. Two-Year contracts (2.7%), and payment modes like Mailed Check (37.8%).


* **Geographic & Service Trends:** Mapping highest churn rates by region (Jammu & Kashmir at 57.2%, Assam at 38.1%) and service types (Fiber Optic churn at 41.1%).



### 🔍 Churn Root Cause Analysis

* **Categorical Drivers:** Breakdown of primary churn categories led by **Competitor offers (761 churned)**, **Customer Service Attitude (301)**, and **Dissatisfaction (300)**.


* **Specific Reasons:** In-depth breakdown attributing losses to competitor offers (better devices: 289, better offers: 274) and support team interactions (208).



### 🤖 Predictive Churn Modeling (Random Forest)

* **At-Risk Identification:** Machine learning predictions identifying **378 specific high-risk customers** likely to churn.


* **Predicted Churner Profile:** Demographics profile of predicted churners (246 Female / 132 Male), primarily concentrated in Month-to-Month contracts (355 customers) and states like Uttar Pradesh (44) and Maharashtra (40).


* **Customer-Level Risk Roster:** Actionable table displaying at-risk Customer IDs along with monthly charges, total revenue, refund history, and referral counts to prioritize customer success outreach.



---

## 6. Screenshots / Demos

Show what the dashboard looks like. - `![Alt_text](https://github.com/username/repo/assets/image.png)`[cite: 3]

Example: `![Dashboard Preview](https://github.com/username/repo/assets/image.png)`[cite: 3]

### Churn Analysis - Executive Summary

![Customer Churn Summary](https://github.com/samadhanshinde1007-dev/Customer-Churn-Analysis-Project/blob/main/Customer%20Churn%20Summary.png)

### Predictive Churn Profile & At-Risk Customers

![Churn Prediction](https://github.com/samadhanshinde1007-dev/Customer-Churn-Analysis-Project/blob/main/Churn%20Prediction.png)

### Churn Reason Breakdown

![Customer Churn Reason](https://github.com/samadhanshinde1007-dev/Customer-Churn-Analysis-Project/blob/main/Customer%20Churn%20Reason.png)
