# Unicorn Companies Analysis

> **Dataset Source**: [CB Insights Unicorn List](https://www.cbinsights.com/research-unicorn-companies)  
> **Date of Data**: November 2024  
> **Author**: Jamie Ogundiran

## Table of Contents
1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Project Goals](#project-goals)
4. [Installation](#installation)
5. [Methodology](#methodology)
6. [Key Findings](#key-findings)
7. [Conclusion](#conclusion)
8. [Future Work](#future-work)

---

## Overview

This project analyzes unicorn companies—privately held companies valued at over $1 billion USD—from around the world as of November 2021. This analysis seeks to uncover trends among unicorns, focusing on factors like geographical distribution, sector representation, and investor influence. Additionally, predictive modeling is used to explore if specific characteristics can predict a company’s potential to reach valuations above $5 billion. 

This project can serve as a reference for venture capitalists, data analysts, and anyone interested in the high-growth company landscape.

## Dataset

The dataset includes information on unicorn companies, such as:
- **Company Name**
- **Valuation** (USD)
- **Date Added** (to unicorn status)
- **Country** and **City**
- **Sector**
- **Select Investors**

**Source**: [CB Insights Unicorn List](https://www.cbinsights.com/research-unicorn-companies)

---

## Project Goals

This project explores several questions:
1. **Who are the top investors** among unicorn companies?
2. **What trends can we see** in company valuations over time?
3. **Is there a correlation** between the number of investors and company valuation?
4. **Can we predict** if a company will achieve a valuation above $5 billion based on its country, sector, and investors?

These questions are addressed through data exploration, visualization, and predictive modeling.

---

## Installation

To run this project locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/unicorn-analysis.git
## Methodology

### Data Cleaning and Preprocessing
- Removed duplicates and handled missing values.
- Encoded categorical features (e.g., country, sector) for analysis.

### Exploratory Data Analysis (EDA)
- Identified top investors and visualized the valuation distribution.
- Analyzed sector and geographical representation.
- Visualized valuation trends over time, with outliers annotated for clarity.

### Predictive Modeling
- **Objective**: Predict if a company’s valuation will exceed $5 billion.
- **Models Used**: Logistic Regression, Random Forest, and XGBoost.
- **Feature Selection**: Used country, sector, and investor information.
- **Evaluation Metrics**: Accuracy, precision, recall.

---

## Key Findings

1. **Top Investors in Unicorn Companies**
   - Investors such as **SoftBank**, **Tiger Global**, and **Sequoia Capital** are highly active in funding unicorn companies, indicating a focused investment strategy on high-growth ventures.

2. **Valuation Over Time**
   - The data visualizations highlight valuation peaks over time, with outliers like **Bytedance** and **SpaceX** standing out due to their exceptionally high valuations.

3. **Investor Influence on Valuation**
   - A moderate positive correlation exists between the number of investors and a company’s valuation, suggesting that increased investor interest often accompanies higher valuations.

4. **Prediction of $5 Billion+ Valuation**
   - **XGBoost** showed the highest accuracy, supporting the hypothesis that features like country, sector, and investors contribute to predicting a company’s potential to reach valuations above $5 billion.

---

## Conclusion

The analysis provides valuable insights into the unicorn ecosystem and suggests that factors like country, sector, and investor involvement play a significant role in a company’s valuation potential. The predictive model demonstrates reasonable accuracy in identifying companies likely to exceed $5 billion, offering a data-driven approach to venture investment decisions.

---

## Future Work

- **Additional Features**: Integrate more granular financial metrics to enhance predictive power.
- **Longitudinal Analysis**: Extend analysis to capture valuation trends post-2021.
- **Network Analysis**: Explore the effect of investor networks on valuation growth.
