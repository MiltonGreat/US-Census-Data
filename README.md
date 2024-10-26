# US-Census-Data

### Summary and Recommendations

#### 1. Overview

This project focuses on cleaning and preprocessing a dataset using Pandas in Python. The goal is to prepare the data for further analysis or modeling by handling missing values, outliers, and other common data quality issues.

#### 2. Data

This dataset is taken from the DP03 and DP05 tables of the 2015 American Community Survey 5-year estimates. The full datasets and much more can be found at the American Factfinder website. 

#### 3. Data Cleaning Process
   
- Missing Values: Some columns like Hispanic, Income, and Unemployment have missing values (nulls). 
- Data Types: The data types seem appropriate.
- Scale Differences: Some values might have different scales, such as TotalPop versus percentages like Hispanic, White, etc. 
- Outliers: Checked for outliers in columns like Income, Unemployment, and Poverty. Outliers could skew 

#### 4. Key Findings
      
- Average Income: $57,009.07
- Average Poverty Rate: 16.87%
- Average Unemployment Rate: 8.97%
- The correlation between Poverty and Unemployment is positive (0.64), indicating that areas with higher poverty rates also tend to have higher unemployment rates.

#### 5.  Source

The data here were collected by the US Census Bureau. https://www.kaggle.com/datasets/muonneutrino/us-census-demographic-data
