# A/B Testing

# Description:

This project analyzes the effectiveness of different variants
in increasing an online store's revenue and conversion rate.
The goal was to determine which variant leads to better user
behavior without negatively affecting order value.

### Technologies Used:

- Pandas (data manipulation)
  
- NumPy (numerical computing)
  
- Matplotlib (data visualization)
  
- Seaborn (statistical plotting)
  
- SciPy / Statsmodels (statistical testing - Z-test)

### Dataset:

Includes user orders, conversion events, order values, and
variant group assignments (A/B). Outliers were filtered using
95th and 99th percentiles to ensure analysis reflects typical
user behavior.

### Methodology:

1. Hypothesis Prioritization:
   
   9 hypotheses were prioritized using ICE and RICE frameworks.

2. Cumulative Analysis:
   
   Tracked revenue and average order value over time for each
   variant to identify trends.

3. Outlier Removal:
   
   Extreme values or unusually active users were excluded
   using scatter plots and percentile thresholds.

4. Statistical Testing (Z-test):
   
   Conversion rates between groups were tested for statistical
   significance on both raw and cleaned data.

### Key Insights:

- Variant B shows a clear improvement in conversion rates.
- Increase in conversion does NOT negatively affect average
  order value.
- Results are consistent and statistically significant.

### Conclusion:

Leader Variant: B

Implementing variant B increases the number of purchases
without reducing spending per order.
Overall impact on business metrics is positive.
