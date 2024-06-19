# Boston-Crash-Dataset

# Team Info
  Ayushi Walia
  Avi Jani
  Aditi Rajmane
  Pranjal Shah
  
# Project Overview
  This project analyzes Massachusetts motor vehicle crash data from 2002 to 2022 to identify trends, patterns, and areas for improving road safety using Python and various data analysis techniques.

# Key Objectives
•	Identify Common Crash Types: Understanding the most frequent types of crashes to prioritize safety measures.
•	Time of Day Analysis: Determining high-risk periods for targeted interventions like increased law enforcement.
•	Weather Impact: Assessing how weather conditions influence crash occurrences to inform mitigation strategies.
•	Trend Analysis: Monitoring changes in crash frequency and severity over time to implement proactive safety measures.
•	Demographic Analysis: Identifying high-risk groups based on driver demographics to guide education and enforcement efforts.
•	Geographic Analysis: Pinpointing high-crash areas to direct resources for infrastructure improvements and public awareness campaigns.

# Data Cleaning
•	Column Removal: Eliminated irrelevant columns like "Vehicle_Travel_Directions" and "Most_Harmful_Events."
•	Date Filtering: Retained data from January 1, 2012, onwards.
•	Null Value Assessment: Checked and accounted for missing data.
•	Duplicate Row Check: Ensured no duplicate entries in the dataset.

# Exploratory Data Analysis (EDA)
•	Crash Types: Identified most common crashes to prioritize interventions.
•	Accident Timing: Analyzed crash distribution across different times of the day.
•	Weather Conditions: Explored the relationship between weather and crash occurrences.
•	Crash Trends: Monitored changes in crash frequency and severity over time.
•	Driver Demographics: Analyzed age and gender data to identify high-risk groups.
•	Crash Locations: Identified high-frequency crash areas for targeted improvements.

# Predictive Modeling
•	Techniques Used: Applied linear and logistic regression models, incorporating L2 regularization to prevent overfitting.
•	Model Evaluation: Used ROC, PR curves, and confusion matrices to evaluate model performance.

# Results:
•	Linear regression model performed well with a perfect score of 1.0 in predicting the number of vehicles involved in crashes.
•	Logistic regression model showed room for improvement with an accuracy score of 0.626.
•	Applying L2 regularization did not significantly enhance the logistic regression model's performance.

# Advanced Analysis with CatBoost
•	Binary Classification: Transformed crash data into a binary classification problem to predict if a crash involved two or more vehicles.
•	Model Performance: Achieved high accuracy (0.9815) and AUC score (0.9917), indicating effective classification.
•	Feature Importance: Key factors like 'Vehicle_Configuration,' 'Crash_Date,' and 'Crash_Time' significantly influence crash predictions.

# Conclusion
The analysis provides actionable insights for improving road safety in Massachusetts. By identifying high-risk crash types, times, weather conditions, and locations, and developing predictive models, the study aids in the formulation of targeted interventions to reduce accidents and enhance public safety.
