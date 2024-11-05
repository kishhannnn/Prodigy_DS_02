# Prodigy_DS_02
Titanic Dataset: Data Cleaning & Exploratory Data Analysis (EDA)
Overview
This project explores the Titanic dataset to identify patterns and trends among passengers. The dataset provides information on passenger demographics, ticket details, and survival outcomes, allowing for meaningful insights into factors that influenced survival on the Titanic.

Steps
Data Loading

Load the Titanic dataset (usually a CSV file).
Check for initial data structure using functions like head(), info(), and describe() to understand column types and general statistics.
Data Cleaning

Handle Missing Values: Identify and handle missing data, particularly in columns like Age, Cabin, and Embarked.
Convert Data Types: Ensure appropriate data types for each column (e.g., Survived as categorical, Age as numerical).
Remove Duplicates: Check and remove any duplicate rows.
Feature Engineering: Create new features (e.g., FamilySize from SibSp and Parch) if they could provide additional insights.
Exploratory Data Analysis (EDA)

Univariate Analysis: Explore individual features, including distributions of Age, Fare, Pclass, etc.
Bivariate Analysis: Analyze relationships between features, especially factors influencing Survived, such as:
Pclass vs. Survived
Sex vs. Survived
Age distribution by Survived status
Multivariate Analysis: Use more complex visualizations to explore interactions, such as Sex, Pclass, and Survived.
Visualization

Use bar plots, histograms, and heatmaps to visualize relationships and distributions.
Summarize key insights from EDA to identify which factors most significantly impacted survival.
Key Insights
After EDA, note any patterns found in the dataset, such as:

Higher survival rates among women and children.
Survival differences by passenger class (e.g., 1st class had a higher survival rate).
Requirements
Programming Language: Python
Libraries: pandas, matplotlib, seaborn
