# D2C Customer Churn Capstone - Part 1

## Data Audit, Exploratory Data Analysis (EDA) & Business Understanding

### Project Objective

The objective of this project is to understand customer behaviour, assess data quality, identify churn-risk patterns, and generate business insights that can support future retention strategies and predictive churn models.

---

## Dataset

The analysis uses multiple datasets from the D2C Customer Churn Capstone project.

Key data sources include:

* Customers
* Orders
* Support Tickets
* Web Activity Snapshots
* Campaign History
* Churn Labels

---

## Project Activities

### 1. Data Loading and Inspection

* Loaded all datasets
* Examined dataset dimensions
* Reviewed sample records
* Validated schema and data types

### 2. Data Quality Assessment

Performed data quality checks including:

* Missing values
* Duplicate records
* Invalid values
* Outlier detection
* Join validation
* Date consistency checks
* Data leakage assessment

### 3. Exploratory Data Analysis

Customer analysis based on:

* Age Group
* City Tier
* Acquisition Channel
* Loyalty Tier
* Preferred Category

Order behaviour analysis based on:

* Product Category
* Ratings
* Quantity
* Delivery Performance
* Discount Usage

Monetary behaviour analysis based on:

* Gross Amount
* Spending Distribution
* High-Value Customers

Support analysis based on:

* Issue Type
* Support Channel
* Resolution Hours
* Reopened Tickets
* Sentiment Scores

### 4. Churn-Risk Hypothesis Testing

The following business hypotheses were explored:

* Customers with lower web activity are more likely to churn.
* Customers with more support issues are more likely to churn.
* Customers with higher return rates are associated with higher churn.
* Customers without loyalty membership have higher churn risk.
* Low campaign engagement leads to higher churn.

### 5. Business Insights

Generated business observations and recommendations based on customer behaviour, support interactions, campaign engagement, and purchasing patterns.

---

## Repository Contents

* `eda_audit.ipynb` – Complete EDA and data audit notebook
* `data_quality_report.md` – Data quality findings and recommendations
* `business_memo.md` – Business-facing churn analysis summary
* `requirements.txt` – Required Python libraries

---

## Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## Outcome

The analysis identified customer behaviour patterns, potential churn indicators, and data quality considerations that provide a strong foundation for customer segmentation, retention planning, and predictive churn modeling in subsequent project phases.

