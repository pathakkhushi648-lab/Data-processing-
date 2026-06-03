# Automated Exploratory Data Analysis using YData Profiling

## Project Overview

This project demonstrates the use of **YData Profiling (formerly Pandas Profiling)** to perform automated Exploratory Data Analysis (EDA) on a Customer Churn dataset. The objective is to quickly understand the dataset, identify data quality issues, discover feature relationships, and generate a comprehensive analytical report with minimal code.

The generated profiling report provides valuable insights into missing values, duplicate records, feature distributions, correlations, outliers, and overall dataset structure.

---

# Objectives

The primary objectives of this project are:

* Perform automated exploratory data analysis.
* Identify missing values and duplicate records.
* Analyze feature distributions.
* Detect outliers and anomalies.
* Study correlations among variables.
* Generate an interactive HTML profiling report.
* Prepare the dataset for machine learning applications.

---

# Dataset Description

The dataset contains customer demographic information, purchasing behavior, membership details, website activity, and churn status.

## Features

| Feature                | Description                |
| ---------------------- | -------------------------- |
| CustomerID             | Unique customer identifier |
| Age                    | Customer age               |
| Gender                 | Customer gender            |
| Income                 | Annual income              |
| MembershipType         | Membership category        |
| PurchaseAmount         | Purchase amount            |
| Quantity               | Quantity purchased         |
| CustomerSatisfaction   | Satisfaction score         |
| WebsiteVisitsPerMonth  | Monthly website visits     |
| LastPurchaseDaysAgo    | Days since last purchase   |
| EmailSubscribed        | Email subscription status  |
| PreferredPaymentMethod | Payment method             |
| City                   | Customer city              |
| State                  | Customer state             |
| Churn                  | Customer churn status      |

---

# Technologies Used

## Programming Language

* Python 3.x

## Libraries

```python
pandas
numpy
matplotlib
seaborn
ydata-profiling
sweetviz
```

---

# Project Workflow
Import Libraries-Load Dataset-View Dataset
(head, shape, columns)-Check Data Types & Information-Generate Statistical Summary-Check Missing Value-Visualize Missing Values
Handle Missing Values-Check Duplicate Records-Remove Duplicates-Automated EDA
(YData Profiling / Sweetviz)-Univariate Analysis-Bivariate Analysis-Multivariate Analysis-Correlation Analysis
Outlier Detection-Feature Engineering-Feature Selectio-Pandas Operations-Conclusion

## Dataset Overview

* Number of rows
* Number of columns
* Missing values
* Duplicate records
* Memory consumption

## Variable Analysis

* Data types
* Unique values
* Statistical summaries
* Feature distributions

## Missing Value Analysis

* Missing value count
* Missing value percentage
* Missing value visualization

## Correlation Analysis

* Pearson Correlation
* Spearman Correlation
* Kendall Correlation
* Phi-K Correlation

## Duplicate Detection

* Duplicate rows count
* Duplicate percentage

## Outlier Detection

* Extreme values
* Unusual observations
* Distribution abnormalities

---

# Generated Report

The project generates an interactive HTML report:

```text
report.html
```

The report can be opened in any web browser and contains detailed visualizations and statistical summaries.

---

# Sample Insights

Some common insights obtained from the report include:

* Presence of missing values in customer attributes.
* Detection of duplicate records.
* Positive correlation between Income and PurchaseAmount.
* Customer Satisfaction influences churn behavior.
* Identification of potential outliers in Income and PurchaseAmount.

---

# Benefits of YData Profiling

* Automated EDA with minimal code.
* Saves significant analysis time.
* Improves data understanding.
* Detects data quality issues quickly.
* Generates professional analytical reports.

---

# Future Enhancements

* Integration with Machine Learning models.
* Automated feature engineering.
* Dashboard development using Streamlit.
* Real-time data profiling.
* Advanced anomaly detection.

---

# Conclusion

This project demonstrates how YData Profiling can automate the Exploratory Data Analysis process and provide deep insights into dataset quality, feature relationships, missing values, and statistical distributions. The generated profiling report serves as a valuable tool for understanding data before applying machine learning techniques.

---

# Author

**Swarna Pathak**

Data Analyst | Machine Learning Enthusiast | Python Developer

GitHub Portfolio Project
