# Marketing Campaign A/B Testing
## Overview
This project analyzes the results of a marketing A/B test to evaluate whether showing advertisements increases user conversion compared with showing Public Service Announcements (PSAs).
Users were divided into two experimental groups:

1. Treatment Group (ad): Users were shown advertisements.
2. Control Group (psa): Users were shown Public Service Announcements instead of advertisements.

The primary objective is to determine whether advertising leads to a statistically significant improvement in conversion rate.

## Business Question
Does showing advertisements increase the user conversion rate compared with showing PSAs?
The analysis also explores whether advertising performance varies by:
1. Number of ad exposures
2. Day of the week
3. Hour of the day

## Dataset
The project dataset from Kaggle. Key features include:              
user id，test group，converted，total ads, most ads day, most ads hour	      

## Methodology

The analysis included:

1. Data cleaning and exploratory analysis
2. Conversion rate comparison
3. Absolute and relative lift calculation
4. A/B test hypothesis formulation
5. Two-proportion Z-test
6. Statistical significance evaluation
7. Data visualization

## Key Results

| Metric | Ad Group | PSA Group |
|---|---:|---:|
| Conversion Rate | 2.55% | 1.79% |

- **Absolute Lift:** ~0.77 percentage points
- **Relative Lift:** ~43.1%
- **Z-statistic:** 7.37
- **P-value:** 1.71 × 10⁻¹³

The p-value was significantly below the 0.05 significance level, providing strong evidence to reject the null hypothesis.

## Conclusion

The advertising group achieved a statistically significant improvement in conversion rate compared with the PSA control group.

From a business perspective, the results suggest that the advertising campaign was effective at increasing conversions. Before a full-scale rollout, additional analysis of incremental conversions, campaign costs, and ROI would help determine whether the improvement also provides meaningful business value.

## Tools & Technologies

- Python
- Pandas
- Matplotlib
- Statsmodels
- Google Colab

## Project File
marketing_AB.csv
