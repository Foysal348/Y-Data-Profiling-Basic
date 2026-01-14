# Y-Data-Profiling-Basic

YData Profiling is an automated Exploratory Data Analysis (EDA) library for Python that generates a comprehensive data profiling report with minimal code. It is widely used in data science and machine learning workflows to quickly understand datasets, identify data quality issues, and guide feature engineering.

**What does the Ydata Profiling do?**

It automatically analyzes a dataset and produces an interactive HTML report covering:

*1. Dataset Overview*

i.Number of rows and columns

ii.Missing values summary

iii.Duplicate rows

iv.Memory usage


*2. Variable (Column) Analysis*
For each column:

i.Data type (numeric, categorical, boolean, datetime, text)

ii.Mean, median, variance, min, max

iii.Unique values & frequency

iv.Missing value percentage

v.Zero / infinite values

*3. Correlations and Interactions*
Visual correlation heatmaps help detect multicollinearity.
i.Correlations
<img width="673" height="505" alt="image" src="https://github.com/user-attachments/assets/80dd1bee-2c9d-4206-ac32-ee0b3e7a0bb2" />

ii.Interactions
<img width="730" height="505" alt="image" src="https://github.com/user-attachments/assets/a5155fef-070f-47f8-a410-4c455cab0d6a" />


*4. Missing Value Analysis*

i.Missing value matrix

ii.Patterns of missingness

*5. Alerts & Warnings*

Automatically flags:

i.High cardinality features

ii.Skewed distributions

iii.Constant or quasi-constant columns

iv.Highly correlated variables
*Alerts & Warnings*
<img width="799" height="717" alt="image" src="https://github.com/user-attachments/assets/10aaedfc-fe0e-448e-8f98-7c6e2fb0db59" />


**Why is YData Profiling useful?**

From a professional data science perspective:

i.Saves hours of manual EDA

ii.Improves data quality awareness

iii.Helps in feature selection & engineering

iv.Ideal for ML preprocessing pipelines

v.Excellent for data validation before modeling
