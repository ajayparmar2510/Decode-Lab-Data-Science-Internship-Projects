# Advanced EDA & Feature Engineering

## Overview

This project focuses on cleaning, analyzing, and transforming an E-Commerce transaction dataset.

The objective was to prepare raw business data for future Machine Learning applications through data cleaning, exploratory data analysis (EDA), outlier analysis, and feature engineering.

---

# Tasks Completed

## Missing Value Handling

* Identified missing values in the dataset.
* Found missing records in the `CouponCode` column.
* Replaced missing coupon values with **"No Coupon"**.
* Verified that the final dataset contains no missing values.

---

## Data Formatting & Consistency

* Converted the `Date` column to datetime format.
* Checked data types of all features.
* Verified dataset consistency and integrity.
* Confirmed that no duplicate records were present.

---

## Exploratory Data Analysis (EDA)

Performed detailed analysis on both numerical and categorical features.

### Numerical Analysis

* Quantity Distribution
* Unit Price Distribution
* Total Price Distribution
* Items in Cart Analysis

### Categorical Analysis

* Product Popularity Analysis
* Payment Method Analysis
* Order Status Analysis
* Referral Source Analysis
* Coupon Usage Analysis

---

## Outlier Analysis

* Detected outliers using the **Interquartile Range (IQR) Method**.
* Analyzed:

  * Quantity
  * UnitPrice
  * TotalPrice
* Evaluated whether detected outliers represented data errors or genuine business transactions.
* Retained meaningful high-value transactions to preserve business insights.

---

## Feature Engineering

Created new features to improve future Machine Learning performance.

| Feature         | Description                                           |
| --------------- | ----------------------------------------------------- |
| DiscountApplied | Indicates whether a coupon was used (0 = No, 1 = Yes) |
| AvgItemValue    | Average value of purchased items                      |
| BasketValue     | Average value per item in cart                        |
| HighValueOrder  | Indicates orders above average transaction value      |
| CartRatio       | Ratio of cart items to purchased quantity             |
| OrderMonth      | Month in which the order was placed                   |
| OrderQuarter    | Quarter in which the order was placed (Q1–Q4)         |

---

# Key Insights

* Coupon usage behavior was analyzed.
* Most frequently purchased products were identified.
* Popular payment methods were determined.
* Customer acquisition channels were analyzed using referral sources.
* Order status trends were examined.
* High-value purchasing patterns were identified.
* Seasonal ordering patterns were analyzed using monthly and quarterly features.

---

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab
* GitHub

---

# Dataset Summary

| Metric            | Value                   |
| ----------------- | ----------------------- |
| Total Records     | 1200                    |
| Total Features    | 14                      |
| Missing Values    | CouponCode Only         |
| Duplicate Records | 0                       |
| Dataset Type      | E-Commerce Transactions |

---

# Output

* Cleaned Dataset
* EDA Report
* Outlier Analysis
* Feature Engineered Dataset
* Business Insights
* Machine Learning Ready Dataset

---

# Project Structure

```text
Decode-Lab-Data-Science-Internship-Projects/
│
├── raw_dataset.csv
├── cleaned_dataset.csv
├── Project1_Advanced_EDA.ipynb
└── README.md
```

---

# Author

**Ajay Parmar**

Data Science Intern

Python | Data Analytics | Machine Learning Enthusiast
