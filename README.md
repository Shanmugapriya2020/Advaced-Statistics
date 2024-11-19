# MEAN INTEREST RATE CHARGED IN SIX AMERICAN CITIES
Codes and files related to statistics

## Introduction:
The annual Percentage Rate of Interest Charged on New-Car Loans at Nine of the Largest Banks in Six American Cities is provided and it is believed that the mean interest rate is same across the six american cities. Conduct the hypothesis test and provide the inference.

### Table of content:
-[Tools](#Tools)
-[Hypothesis Analysis](#Hypothesis Analysis)
-[Finding](#Finding)
-[Conclusion](#Conclusion)

### Tools
Python :Python

### Hypothesis Analysis
1. $H_0$: The mean interest rate in all six american cities is same
2. $H_1$: The mean interest rate is different in atleast one of the six american cities

### Findings

   df     sum_sq   mean_sq         F    PR(>F)
city       5.0  10.945667  2.189133  4.829385  0.001175
Residual  48.0  21.758133  0.453294       NaN       NaN

P value is less than 0.5 . Hence we reject the null hypothesis.

### Conclusion
Its clear that the mean interest rate is different in atleast one of the six american cities
