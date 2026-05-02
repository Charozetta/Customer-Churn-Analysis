# Happy Beans Coffee Customer Churn Prediction

[[![Uploading image.png…]()](https://www.europosters.de/coffee-beans-and-ground-coffee-f68508148?srsltid=AfmBOoryxlPQFQesTVMeqHkPARVCVMO0C-bn7JhdvB7XwRIf42d1DqU1)](https://imgur.com/gallery/bunday-coffee-just-hits-so-right-BeoNdy2#/t/coffee)



A machine learning educational project aimed at predicting customer churn for a coffee delivery service.

## Project Description
Happy Beans Coffee recently launched a coffee delivery service but faced a customer churn issue — the service loses about 10% of its customer base every month. Since acquiring a new customer is 5–7 times more expensive than retaining an existing one, accurate churn prediction will allow the company to focus its marketing efforts and budget on retaining high-risk customers.

## Goals and Objectives
- Perform Exploratory Data Analysis (EDA) and data preprocessing.
- Train a machine learning model to predict customer churn.
- Tune hyperparameters to maximize the PR AUC metric (under conditions of severe class imbalance).
- Save the final model as a pipeline for future deployment.

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn (Logistic Regression, Pipeline, GridSearchCV)
- Matplotlib, Seaborn

## Project Structure
- `coffee_churn_prediction.ipynb` — The main Jupyter Notebook containing the research code, comments, and conclusions.
- `best_pipeline.pkl` — The saved machine learning model (the result of the notebook execution).

## Results
A Logistic Regression model was developed and trained. Through hyperparameter tuning and feature engineering, the model achieved a **PR AUC of 0.7309** on the test set (compared to a baseline of 0.0602, a 12-fold improvement). The model is ready for production deployment.
