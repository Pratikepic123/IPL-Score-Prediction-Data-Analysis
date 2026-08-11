# IPL Score Prediction & Data Analysis

## Project Overview

This project analyzes IPL innings data and predicts the final innings score using machine learning.

The project follows an end-to-end data analytics workflow, starting from PostgreSQL data storage and continuing through data cleaning, exploratory data analysis, visualization, feature engineering, machine learning, and final score prediction.

## Tech Stack

- PostgreSQL
- pgAdmin
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SQL

## Project Workflow

PostgreSQL / pgAdmin
↓
Data Loading
↓
Data Cleaning
↓
Exploratory Data Analysis
↓
Data Visualization
↓
Feature Engineering
↓
Train-Test Split
↓
Outlier Treatment
↓
Encoding
↓
Feature Scaling
↓
Machine Learning
↓
Model Evaluation
↓
Final IPL Score Prediction

## Dataset Features

The dataset contains information such as:

- Match ID
- Date
- Venue
- Batting Team
- Bowling Team
- Batsman
- Bowler
- Runs
- Wickets
- Overs
- Runs in Last 5 Overs
- Wickets in Last 5 Overs
- Striker
- Non-Striker
- Total Score

## Exploratory Data Analysis

The project includes analysis of:

- Score distributions
- Wicket distributions
- Overs
- Recent scoring performance
- Team performance
- Venue performance
- Runs vs final score
- Wickets vs final score
- Correlation analysis

Each major visualization includes an observation based on the analysis.

## Machine Learning Models

The following regression models were evaluated:

- Linear Regression
- K-Nearest Neighbors
- Decision Tree
- Random Forest
- AdaBoost

## Model Evaluation

Models were compared using:

- MAE
- RMSE
- R² Score

The final model was selected based on the evaluation results.

## Key Finding

The analysis indicates that current runs, recent scoring performance, and wickets are important factors for estimating the final innings score.

## Author

Pratik Manjare