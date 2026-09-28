# A/B Testing for Conversion Rate Optimization

## Overview
This project analyzes the impact of a new design on user conversion rates using A/B testing.  
The goal is to determine whether the treatment group leads to a statistically significant improvement in conversions.

---

## Dataset
- Size: ~9,994 observations  
- Variables:
  - group (control / treatment)
  - converted (0/1)
  - gender
  - device_type  

---

## Methodology

### 1. Exploratory Analysis
- Calculated conversion rates for control and treatment groups  
- Segmented analysis by gender and device type  

### 2. Hypothesis Testing
- Null Hypothesis (H0): No difference in conversion rates  
- Alternative Hypothesis (H1): Treatment improves conversion  

- Applied **two-proportion Z-test**  

### 3. Statistical Results
- Control Conversion Rate: **11.87%**  
- Treatment Conversion Rate: **17.95%**  
- Absolute Lift: **6.08%**  

- Z-statistic: large magnitude  
- p-value: ~0  

- 95% Confidence Interval: **[5.82%, 6.33%]**

---

### 4. Power Analysis
- Simulated experiments with different sample sizes  
- Observed:
  - Low power at small sample sizes  
  - High power (~1) at large sample sizes  

---

### 5. Segmentation Analysis
- Consistent improvement across:
  - Gender segments  
  - Device types (Desktop, Mobile, Tablet)  

---

## Key Insights
- Treatment significantly improves conversion rate  
- Results are statistically significant and practically meaningful  
- Large sample size leads to high statistical power  
- Consistent uplift across segments indicates robustness  

---

## Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Statsmodels  
- Matplotlib  

---
