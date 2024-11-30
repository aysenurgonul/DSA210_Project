# DSA210_Project

## Description
This project aims to analyze the correlation between my daily step count and external factors such as how it changes during the exam seasons and weekday vs. weekend activity patterns.

## Table of Contents
- Overview and Motivation
- Objectives
- Tools
- Data Source
- Data Processing
- Data Visualizations
- Data Analysis
- Limitations
- Potential Outcomes
- Future Work
### Project Overview and Motivation:
The motivation behind this project is to better understand how my physical activity, as measured by daily step count, is influenced by external factors like academic workload and weekly routines. By exploring correlations with exam seasons and distinguishing activity levels on weekdays versus weekends, I aim to uncover patterns in my behavior and identify potential areas for lifestyle changes. I am planning to achieve this by analyzing this semester. 

### Objectives
- Correlation Analysis: Determine if there is a significant correlation between the number of steps taken daily and the presence of exam periods.
- Weekday vs. Weekend Analysis: Explore the differences in step counts between weekdays and weekends to identify patterns of activity.
- Visualization: Create visual representations of the data to make findings easily interpretable.

### Tools That I Will Probably Use In My Project
- Jupyter Notebook: For coding and documentation.
- Pandas: For data cleaning, manipulation, and filtering.
- Matplotlib: For creating visualizations.
- Numpy: For mathematical operations.
- Scipy: For statistical analysis.

### Data Source
The data used in this project comes from my step numbers per day, recorded with my phone. I will also use exam period data.

### Data Processing
The data processing phase involved:

- Converting raw step count data into a clean format with date, step count, and day type (weekday/weekend).
- Adding an "exam season" column based on predefined date ranges for exams.
- Aggregating and normalizing step counts for comparison across different days and periods.
- Exploratory Data Analysis (EDA) to calculate summary statistics (e.g., mean, median, variance) for step counts during exam and non-exam periods. Also to compare step counts for weekdays versus weekends.

### Data Visualizations
To uncover trends and patterns, I am planning to create the following visualizations:

- Line Plot: Daily step counts over time, highlighting exam season periods.
- Box Plot: Comparison of step counts during exam seasons versus non-exam seasons.
- Bar Chart: Average step count for weekdays versus weekends.

### Data Analysis
#### 1. Correlation Between Steps and Exam Seasons
I am planning to conduct a t-test to evaluate whether step counts significantly decrease during exam seasons and I will examine the trends to identify any significant shift related to academic workload.
#### 2. Weekday vs. Weekend Step Count
I will calculate average step counts for weekdays and weekends and perform statistical tests to determine if differences are significant.

### Limitations
#### Data-Related Limitations
- The dataset may not capture all physical activity, as it relies only on step count from my phone.
- External factors like weather or health conditions were not accounted for, which could affect my step counts.
#### Personal Limitations
- Limited ability to analyze long-term trends due to the dataset's time range.
- Potential biases in defining exam seasons.

### Potential Outcomes
- Understanding the impact of academic stress on my physical activity.
- Life style adjustments with healthier habits during exam seasons.

### Future Work
#### What more can be done at the end of the project?
- Comprehensive Analysis: Extend the analysis to include multiple academic terms or years to observe long-term patterns.
- Weather and Other Variables: Incorporate additional data, such as weather conditions or sleep patterns, to better understand fluctuations in activity levels.
- Predictive Modeling: Develop a model to predict step counts based on academic workload and weekly routines.
