# Gaming Study: Predicting Anxiety from Gaming Habits

## Overview
This project explores the potential of machine learning models to predict psychological well-being, specifically anxiety, based on gaming habits and socio-economic factors. It utilizes a comprehensive dataset that includes various aspects of gaming behavior and personal demographics.

## Dataset
The dataset includes variables related to gaming frequency (`Hours`), gaming platforms (`Platform`), and psychological scales (`SWL_T`, `SPIN_T`). We process the data to create factors and address missing values, preparing it for effective model training.

## Model
The Random Forest model is trained to predict whether gamers experience anxiety (`Anxiety`), classified into two categories: 0 (No Anxiety) and 1 (Anxiety). We optimize prediction accuracy through feature engineering and parameter tuning.

## Files
- `GamingStudy_data.csv`: Before cleaning the dataset.
- `GamingStudy_data_IMP_cleaned.csv`: Cleaned and pre-processed dataset.
- `Data Cleaning.Rmd`: Script for cleaning the GamingStudy_data.csv dataset.
- `Random Forest Model.Rmd`: Script for training the Random Forest model and evaluating its performance.

## Usage
Run the `Random Forest Model.Rmd` script in R or RStudio to train the model and view the performance metrics. The script requires the following R packages: `randomForest`, `caret`, `pROC`, `ggplot2`.

## Results
The model achieves an accuracy of 84.19%, with an AUC of the ROC curve indicating robust predictive power. Feature importance is analyzed to understand the impact of various factors on the prediction of anxiety.
