# Machine Learning Model Comparison and Optimization for Classification Tasks

## Overview
This project involves comparing and optimizing different machine learning models for a classification task using R. The primary goal is to evaluate models such as **Random Forest**, **Support Vector Machine (SVM)**, and **Neural Network**, and determine the best-performing model based on accuracy metrics. After the initial comparison, hyperparameter tuning is applied to enhance model performance, and the optimized model is used for predictions on a test dataset.

## Project Structure

- **main1.m**: MATLAB script (details not provided in this README).
- **main.ipynb**: Jupyter Notebook with data processing and model training details.
- **R.txt**: R script implementing various classification models and evaluating their performance.
- **training_set.csv** and **test_set.csv**: Datasets used for model training, validation, and testing.

## Key Features

- **Data Preprocessing**:
  - Handling missing values and splitting the data into training, validation, and test sets.
  - Encoding categorical variables as factors for compatibility with R models.

- **Model Training and Evaluation**:
  - **Random Forest**: Baseline and tuned models with 100 trees.
  - **SVM**: Radial kernel SVM model with tuning for cost and gamma.
  - **Neural Network**: A neural network model with 10 nodes, trained with regularization.

- **Hyperparameter Tuning**:
  - Fine-tuning hyperparameters for **Random Forest** and **SVM** to achieve optimal performance.
  - Selection of the best model based on accuracy and out-of-bag error rates.

- **Feature Importance**:
  - Determining the most influential features in the best-performing model (Random Forest).

- **Prediction on Test Data**:
  - Generating predictions for the test dataset with the final model.
  - Saving predictions to a CSV file for further analysis or submission.

## Usage

1. **Install Required Packages**: Run the following in R to install necessary packages:
   ```r
   install.packages("caret")
   install.packages("randomForest")
   install.packages("e1071")
   install.packages("nnet")
