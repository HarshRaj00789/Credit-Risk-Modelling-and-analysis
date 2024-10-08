# Credit-Risk-Modelling-and-analysis
Credit Risk Modelling
Introduction
This notebook performs credit risk analysis using a dataset containing loan information. The goal is to explore key variables that influence credit risk and develop models to predict the likelihood of default.

Dependencies
The following libraries are required to run the notebook:

numpy
pandas
warnings
os
google.colab (if running in Google Colab)
To install these dependencies, run the following command:

bash
Copy code
pip install numpy pandas
Instructions
Ensure that the dataset (CSV file) is available in the correct directory. If using Google Colab, mount Google Drive to access the data.
The dataset is loaded using pandas.read_csv() and contains 72 columns with detailed loan data, including:
loan_amnt: Amount of loan
term: Loan duration
int_rate: Interest rate
grade and sub_grade: Loan grade assigned based on risk factors
Other financial details related to loans and borrowers.
The notebook starts by loading and displaying the first few rows of the dataset to provide an overview of its structure.
Data cleaning and pre-processing steps may follow, including handling missing values, feature selection, and scaling of data.
Use Case
The notebook is designed to model credit risk by analyzing various loan attributes and identifying factors contributing to defaults. The modeling techniques used may include:

Logistic Regression
Decision Trees
Other machine learning models
Running the Notebook
Clone this repository:
bash

Open the notebook and run the cells in sequence to load the dataset, explore the data, and perform the modeling tasks.
