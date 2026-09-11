# Customer Segmentation & Behavioral Trend Dashboard

**Author:** Mohtasim Ahmed Awan
**Internship:** Progree Internship — Data Analytics Domain

## Overview
This project performs customer segmentation using RFM (Recency, Frequency, Monetary) analysis on retail transaction data, producing a segmented customer base to power a behavioral trend dashboard.

## Objectives
- Clean and correctly type transactional data
- Compute RFM metrics for each customer
- Score customers on Recency, Frequency, and Monetary dimensions using quantile-based scoring
- Combine individual scores into a single RFM score
- Assign customers to meaningful behavioral segments
- Prepare clean, exportable files for dashboard visualization

## Pipeline Steps
1. Import libraries and load the dataset
2. Initial data inspection
3. Clean and fix data types (dates, etc.)
4. Set the reference date for recency calculation
5. Compute RFM metrics by grouping on customer
6. Score each RFM metric on a 1–5 scale using quantiles
7. Combine individual scores into a combined RFM score
8. Assign customer segments based on RFM score
9. Visualize segment distribution as a sanity check
10. Export clean files for Power BI dashboarding

## Tools & Libraries
- Python
- pandas, numpy
- datetime

## Output
A customer-level RFM segmentation table and supporting exported files, used to build a Power BI behavioral trend dashboard.
