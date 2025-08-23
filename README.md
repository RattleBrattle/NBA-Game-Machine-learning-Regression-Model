# NBA Player Salary Prediction Model

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.0%2B-orange)
![Pandas](https://img.shields.io/badge/Pandas-1.3%2B-brightgreen)
![License](https://img.shields.io/badge/License-MIT-green)

A machine learning project that predicts NBA player salaries based on player attributes, performance metrics, and demographic data from the NBA 2K video game series.

## Project Overview

This project uses machine learning regression techniques to predict NBA player salaries using data from NBA 2K20 and NBA 2K21 video games. The model analyzes various factors including player ratings, physical attributes, draft information, and team context to estimate player compensation.

## Features & Used Datasets

- **Data Source**: NBA 2K20, 2K21, and 2K22 player dataset (Cleaned & Preprocessed)
- **Target Variable**: Player salary in USD
- **Input Features**:
  - Player rating (0-100 scale)
  - Physical attributes (height, weight)
  - Draft information (year, round, peak)
  - Team affiliation
  - Player position
  - Age and experience
  - Game version
 
## Data Cleaning & Preprocssing

- Cleaned the dataset completely from missing values and made sure no duplicates are present.
- Added new columns for 'p_age', 'height_cm', 'weight_kg', and 'version_split' to make the dataset more readable and easier to work with.
- Dropped unnecessary columns that won't affect the player's salary (irrelevant).
- Used Label Encoding to Encode the 'team' and 'position' columns which where the only two remaining categorical columns.
- Saved the cleaned dataset to a new CSV file (version 1 for testing).

## Model Details & Score
The following picture has all the Model Scores:
![Model Results](https://github.com/RattleBrattle/NBA-Game-Machine-learning-Regression-Model/blob/main/Images/Model%20Error%20and%20Score%20Evaluation.png?raw=true)

## Model Residuals and Regression Line plots
The following picture has all the model results visualizations:
![Model Visualizations](https://github.com/RattleBrattle/NBA-Game-Machine-learning-Regression-Model/blob/main/Images/Model%20Error%20and%20Score%20Evaluation.png?raw=true)
