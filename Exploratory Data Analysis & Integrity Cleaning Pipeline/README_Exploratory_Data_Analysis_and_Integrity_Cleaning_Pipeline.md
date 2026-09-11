# Exploratory Data Analysis and Integrity Cleaning Pipeline

**Author:** Mohtasim Ahmed Awan
**Internship:** Progree Internship — Data Analytics Domain

## Overview
This project implements a complete Exploratory Data Analysis (EDA) and data integrity cleaning pipeline on a retail transactions dataset. It walks through inspecting raw data, identifying quality issues, treating them systematically, and producing clean, analysis-ready data along with visual insights.

## Objectives
- Assess dataset structure, data types, and overall quality
- Detect and quantify missing values and duplicate records
- Identify and treat outliers in numerical columns using the IQR method
- Correct and standardize date and time data types
- Apply a systematic missing value imputation pipeline (median for numerical, mode for categorical)
- Cap outliers using IQR-based winsorization
- Visualize distributions, correlations, and sales trends

## Pipeline Steps
1. Import libraries and load the dataset
2. Initial data preview, shape, and column inspection
3. Descriptive statistics and data type review
4. Missing value check and percentage breakdown
5. Duplicate row detection and inspection
6. Unique value checks for categorical columns
7. Min/max range checks for numerical columns
8. Outlier detection and treatment (IQR method)
9. Date and time data type correction
10. Missing value imputation pipeline
11. Outlier capping (winsorization)
12. Distribution analysis: histograms, boxplots, categorical distributions
13. Correlation heatmap
14. Sales trend analysis by hour of day
15. Final pipeline summary and conclusion

## Tools & Libraries
- Python
- pandas, numpy
- matplotlib, seaborn

## Output
A cleaned, integrity-checked dataset ready for downstream analysis, along with supporting visualizations summarizing data quality and distribution patterns.
