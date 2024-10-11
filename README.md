# US-Census-Data

### Summary and Recommendations

1.  Data Cleaning Process:
   
- Missing Values: Some columns like Hispanic, Income, and Unemployment have missing values (nulls). 
- Data Types: The data types seem appropriate.
- Scale Differences: Some values might have different scales, such as TotalPop versus percentages like Hispanic, White, etc. 
- Outliers: Checked for outliers in columns like Income, Unemployment, and Poverty. Outliers could skew 

2.   Key Findings:
      
- Income: The average income is around $57,225 with a wide range (min: $2,611, max: $248,750).
- The standard deviation is high ($28,449), indicating that incomes vary significantly between areas.
- Poverty: The average poverty rate is 16.96%, with a wide spread from 0% to 100%. This shows there are areas with extreme poverty conditions, which could be visible as clusters of high poverty rates in the scatterplot.
- Unemployment: The average unemployment rate is 9.03%, with a large range from 0% to 100%. 

Source: The data here were collected by the US Census Bureau. https://www.kaggle.com/datasets/muonneutrino/us-census-demographic-data
