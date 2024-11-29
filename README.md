# DSA210_Project

## Description
This project aims to analyze the correlation between my daily step count and external factors such as how it changes during the exam seasons and weekday vs. weekend activity patterns.

Table of Contents
Motivation
Tools
Data Source
Data Processing
Data Visualizations
Data Analysis
Correlation Between Steps and Exam Seasons
Weekday vs. Weekend Step Count
Findings
Limitations
Future Work
Motivation
The motivation behind this project is to better understand how my physical activity, as measured by daily step count, is influenced by external factors like academic workload and weekly routines. By exploring correlations with exam seasons and distinguishing activity levels on weekdays versus weekends, I aim to uncover patterns in my behavior and identify potential areas for lifestyle changes.

Tools That I Will Probably Use In My Project
Jupyter Notebook: For coding and documentation.
Pandas: For data cleaning, manipulation, and filtering.
Matplotlib & Seaborn: For creating visualizations.
Numpy: For mathematical operations.
Scipy: For statistical analysis.
Data Source
The data used in this project comes from my step count logs, recorded with my phone. I will also use exam period data.

Data Processing
The data processing phase involved:

Converting raw step count data into a clean format with date, step count, and day type (weekday/weekend).
Adding an "exam season" column based on predefined date ranges for midterms and finals.
Aggregating and normalizing step counts for comparison across different days and periods.
Data Visualizations
To uncover trends and patterns, I created the following visualizations:

Line Plot: Daily step counts over time, highlighting exam season periods.
Box Plot: Comparison of step counts during exam seasons versus non-exam seasons.
Bar Chart: Average step count for weekdays versus weekends.
Data Analysis
1. Correlation Between Steps and Exam Seasons
Conducted a t-test to evaluate whether step counts significantly decrease during exam seasons.
Examined trends to identify any behavioral shifts related to academic workload.
2. Weekday vs. Weekend Step Count
Calculated average step counts for weekdays and weekends.
Performed statistical tests to determine if differences are significant.
Findings
Exam Seasons: Step counts decreased during exam periods, suggesting a reduction in physical activity due to increased academic stress.
Weekday vs. Weekend: Step counts were higher on weekends, reflecting more time for leisure activities.
Limitations
Data-Related Limitations
The dataset may not capture all physical activity, as it relies solely on step count from my smartwatch.
External factors like weather or health conditions were not accounted for, which could impact step counts.
Personal Limitations
Limited ability to analyze long-term trends due to the dataset's time range.
Potential biases in defining exam seasons based on personal academic schedules.
Future Work
Longitudinal Analysis: Extend the analysis to include multiple academic terms or years to observe long-term patterns.
Weather and Other Variables: Incorporate additional data, such as weather conditions or sleep patterns, to better understand fluctuations in activity levels.
Predictive Modeling: Develop a model to predict step counts based on academic workload and weekly routines.
