# Supply Chain Analysis

## Overview

An end-to-end supply chain analytics project using Python to analyze delivery performance, identify operational bottlenecks, evaluate profitability risks, and predict delayed orders.

## Business Problem

The company faces inconsistent delivery performance, resulting in late deliveries, reduced profitability, and operational inefficiencies.

## Objectives

- Analyze delivery performance
- Identify major causes of delays
- Evaluate profitability by delay
- Detect operational bottlenecks
- Analyze seasonal and time-based delay patterns
- Predict high-risk delayed orders

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Key Analysis

### Data Cleaning & Feature Engineering
- Removed irrelevant and redundant columns
- Converted date fields
- Calculated order processing time
- Calculated delivery delays
- Created delayed-order indicators
- Created profitability classifications

### Exploratory Data Analysis
- Profitability distribution
- Delay distribution
- Profit vs. delay analysis
- Delay analysis by region
- Delay analysis by customer segment
- Delay analysis by shipping mode
- Delay analysis by department and product type

### Predictive Modeling

A Random Forest model was developed to identify high-risk delayed orders.

**Model Accuracy:** ~74%

## Key Findings

- Late delivery rate: **54.71%**
- Profit at risk: **$2.1M**
- First Class showed severe delivery-performance issues
- Second Class also showed significant delays
- Shipping mode was identified as a major operational driver

## Business Recommendations

- Correct shipping-mode configuration
- Deploy predictive risk scoring
- Improve payment-processing operations
- Plan for seasonal demand spikes
- Monitor high-risk orders proactively

## Project Structure

```text
Supply-Chain-Analysis-Python/
│
├── supply_chain_analysis.ipynb
├── README.md
├── requirements.txt
├── data/
└── images/
