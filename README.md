# SalaryEstimation
Overview

This project focuses on estimating salaries using relevant job-related metrics such as rating, job title, location, and more. The goal is to build a clean, structured dataset that can be used to model salary predictions with high reliability.

Key Features

End‑to‑end salary estimation workflow

Extensive data cleaning and preprocessing

Conversion of raw salary ranges into usable numerical averages

Categorization of job titles for better model performance

Location normalization into U.S. states


How It Works

Library Upload – Import all necessary Python libraries for data wrangling and model development.

Data Frame Overview – Inspect the dataset to understand available fields and identify columns requiring transformation.

Salary Cleaning:

Convert the Salary Estimate column into a clean numerical average.

Remove non‑numeric symbols (e.g., $, K, /hr, /yr).

Filter out entries where salary = -1 as these are invalid.

Job Title Categorization – Normalize job titles into meaningful categories for better comparison and modeling.

Location Cleaning – Extract state-level information from location fields.

Rating Cleanup – Remove or adjust negative values to keep data consistent.

Column Filtering – Retain useful columns and drop irrelevant ones.

Model Preparation – The cleaned dataset is now ready for exploration or machine learning.

Linear Regression Model

After cleaning and preparing the dataset, a Linear Regression model was implemented to estimate salaries based on transformed features.

Splitting the dataset into training and testing sets

Fitting a Linear Regression model using Scikit‑Learn

Evaluating model performance using metrics such as MAE, MSE, and R²
MAE 23.497127381171865
MSE 892.6741348864775
