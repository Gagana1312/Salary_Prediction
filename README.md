Overview

This repository contains a Python implementation of linear regression. The model is trained on a dataset containing information about salaries and years of experience.

Files
ML_internship.ipynb: Python script containing the implementation of linear regression from training to evaluation.
salary_data.csv: Dataset file containing information about salaries and years of experience.

Dependencies
Make sure you have the following Python libraries installed:
numpy
pandas
matplotlib
scikit-learn


Usage
Clone the repository:
git clone https://github.com/gagana1312/Salary_Prediction.git

Navigate to the project directory:
cd Salary_Prediction

Open the Jupyter Notebook:
jupyter notebook LR_Model.ipynb

Run the notebook cell by cell to execute the linear regression implementation.


Dataset
The dataset (salary_data.csv) contains two columns: Years of Experience (feature) and Salary (target).

Custom Linear Regression Class
The notebook includes a custom implementation of linear regression in a LinearRegressionFromScratch class. You can adjust hyperparameters such as learning rate and epochs within the notebook.

Evaluation
The notebook calculates the R-squared value, MSE, and RMSE to evaluate the model's performance on the test set. R-squared measures how well the model explains the variance in the target variable.
