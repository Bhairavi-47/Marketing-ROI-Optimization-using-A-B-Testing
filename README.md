# Marketing-ROI-Optimization-using-A-B-Testing
End-to-end marketing analytics project comparing Facebook and AdWords performance using statistical A/B testing and predictive modeling. Provides actionable recommendations for strategic budget reallocation and ROI optimization

## Business Problem

In digital marketing, organizations invest heavily across multiple advertising platforms without clear evidence of which channel generates superior returns.

As a marketing analytics team, our objective is to evaluate and compare the performance of two advertising platforms — **Facebook Ads** and **AdWords Ads** — to determine which delivers higher conversions and better cost efficiency.

Without data-driven evaluation, marketing budgets risk being misallocated, reducing overall return on investment (ROI).

---

## Project Objective

The primary objectives of this project are:

- Compare campaign performance between Facebook and AdWords
- Measure and analyze conversion effectiveness
- Evaluate cost efficiency across platforms
- Identify statistically significant differences in performance
- Provide strategic recommendations for optimal budget allocation

This project aims to support business **decision-making** through statistical analysis and marketing analytics.

---

## Research Questions

1. Which platform generates higher average daily conversions?
2. Do higher ad clicks lead to proportionally higher conversions?
3. Is the difference in conversion performance statistically significant?
4. How does advertising cost influence conversion outcomes?
5. Is there a long-term equilibrium relationship between ad spend and conversions?

---

## Dataset Overview

- Time Period: January 1, 2019 – December 31, 2019
- Observations: 365 daily records
- Platforms Analyzed:
  - Facebook Ads
  - AdWords Ads

### Key Features:

- Ad Views
- Ad Clicks
- Ad Conversions
- Cost per Ad
- Click-Through Rate (CTR)
- Conversion Rate
- Cost per Click (CPC)

The dataset enables both cross-platform comparison and time-based trend analysis.

---

## Analytical Approach

The following analytical techniques will be implemented in upcoming phases:

- Exploratory Data Analysis (EDA)
- Conversion distribution analysis
- Correlation analysis
- Hypothesis testing (Independent T-Test)
- Linear Regression Modeling
- Time Series Analysis
- Cointegration Testing

---

# Key Insights

## 1) Conversion Performance :-

- Mean Daily Conversions:
  - **Facebook:** 11.74
  - **AdWords:** 5.98

Facebook generates nearly **2x higher conversions** on average.

---

## 2) Click-to-Conversion Relationship :-

- Correlation Coefficient:
  - **Facebook:** 0.87 (Strong Positive)
  - **AdWords:** 0.45 (Moderate Positive)

Facebook clicks translate into conversions much more efficiently.

---

## 3) Statistical Significance :-

- T-statistic: 32.88  
- P-value: 9.35e-134  

The difference in conversions is statistically significant (p < 0.05).  
Facebook clearly outperforms AdWords.

---

## 4) Predictive Modeling :-

- R² Score (Facebook Regression Model): 76.35%
- Strong predictive power between clicks and conversions.

Facebook campaign scaling is highly predictable.

---

## 5) Cost Efficiency Trends :-

- Lower Cost Per Conversion observed in May & November.
- February shows highest CPC.

 Strategic monthly budget adjustments can further optimize ROI.

---

# Strategic Recommendation 

- Increase budget allocation toward Facebook campaigns.
- Optimize Facebook creatives to leverage strong click-conversion relationship.
- Monitor monthly CPC trends for cost-efficient spending.
- Further investigate optimization opportunities within AdWords campaigns.

---

## Visualizations

All charts and analytical visualizations are available in the `/visuals` folder.

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- Statsmodels
- Jupyter Notebook

---

This repository will evolve into a complete end-to-end marketing analytics case study demonstrating data-driven decision-making for marketing ROI optimization.
