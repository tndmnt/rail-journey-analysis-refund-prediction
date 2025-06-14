# Rail Journey Analysis & Refund Prediction

This project involves analyzing a synthetic UK rail journey dataset (MavenRail.csv) to explore delay patterns and build predictive models for refund requests. 

## Dataset
- `MavenRail.csv`: Synthetic data of UK rail journeys from Jan–Apr 2024 (train data).
- `ToPredict.csv`: test data.
- Contains attributes like departure/arrival time, journey status, delay reason, price, and refund status.

## Objectives
1. Perform Exploratory Data Analysis (EDA) on categorical and time-based features.
2. Calculate delay duration in minutes.
3. Engineer features such as `MediumPrice` for classification purposes.
4. Fit logistic regression models to predict refund likelihood based on pricing and other attributes.
5. Apply the best-fit model to new records in `ToPredict.csv`.

## Files
- `StudentID11585796_CourseWork_EDA_Regression.ipynb`: Full notebook with preprocessing, EDA, feature engineering, model fitting, and predictions.
- `StudentID11585796.pdf`: Accompanying report summarizing the methodology, analysis, and results.
- `MavenRail.csv`: Raw train dataset used in the analysis.
- `ToPredict.csv`: test dataset used.
