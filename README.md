# Titanic Dataset – Exploratory Data Analysis

### Overview
This project focuses on performing Exploratory Data Analysis (EDA) on the classic Titanic dataset from Kaggle.
The goal is to explore the data, clean it, visualize key relationships, and uncover insights about passenger survival- all without using any machine learning models.

### Objectives
- Understand the structure and key attributes of the Titanic dataset
- Clean and preprocess missing or irrelevant data
- Perform univariate and bivariate analysis using Python
- Visualize survival trends based on gender, age, passenger class, and embarkation port
- Draw meaningful conclusions from observed patterns

### Tools & Libraries Used
- Python
- Pandas – for data manipulation and analysis
- Matplotlib – for visualization

### Dataset Information
- Dataset: Titanic – Machine Learning from Disaster (Kaggle)
- Main file used: train.csv

### EDA Process
- Data Loading – Import CSV and check structure
- Data Cleaning – Handle null values, drop redundant columns
- Descriptive Statistics – Overview of numerical and categorical columns
- Univariate Analysis – Study single-variable distributions
- Bivariate Analysis – Explore relationships between survival and other factors
- Correlation Study – Observe numeric relationships
- Insights Summary – Document- findings and trends

### Key Insights
- Around 38% of total passengers survived.
- Females had a significantly higher survival rate.
- 1st class passengers were more likely to survive.
- Younger passengers (especially below 10) showed better survival odds.
- Most passengers embarked from Southampton, but Cherbourg passengers had slightly better survival chances.

### Repository Structure
Titanic-EDA/
│
├── train.csv                 # Dataset
├── titanic_cleaned.csv       # Cleaned dataset (after preprocessing)
├── titanic_eda.ipynb         # Main EDA notebook
└── README.md                 # Project documentation
