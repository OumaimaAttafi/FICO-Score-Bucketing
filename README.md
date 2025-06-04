# FICO Score Bucketing

This project was completed as part of the J.P. Morgan Quantitative Research Virtual Experience (Forage).

## Objective
Convert continuous FICO credit scores into discrete risk buckets for use in a machine learning model that requires categorical input.

## Methods Implemented
1. **Mean Squared Error (MSE) Minimization**
   - Grouped scores into buckets minimizing within-bucket variance
2. **Log-Likelihood Maximization**
   - Formed buckets that best separate default risk using greedy likelihood optimization

##  Output
- Probability of Default (PD) per bucket
- Visualized with side-by-side bar charts

## Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
