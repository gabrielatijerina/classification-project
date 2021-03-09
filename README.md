# Churn Prediction at Telco

## Goals
- Find drivers of churn for customers at Telco
- Construct a ML classification model that accurately predicts customer churn using Telco data 

## Deliverables 
- Deliverables for this project include:
  - A final model created to predict if a customer will leave the company
- This repo containing:
  - A Jupyter Notebook with details of how to construct a model using classification techniques
  - Individual modules (acquire.py and prepare.py files) that hold functions for data acquisition and preparation
  - A CSV file with customer_id, probability of churn, and prediction of churn 

## Data Dictionary
- customer_id: unique id for each customer
- churn: does not churn = 0, does Churn = 1
- senior: no = 0, 1 = yes
- tenure: how long a customer has been at Telco
- contract_type: Month to Month = 0, 1-Year = 1, 2-Year = 2
- tech_support: no = 0, yes = 1
- online_backup: no = 0, yes = 1
- phone_service:: no = 0, yes = 1

## Key Findings/Takeaways 
- Month-to-month customers churn at a higher rate than customers on one or two-year contracts
- Senior citizens have a higher churn rate than non-seniors

## Conclusion
- Baseline accuracy showed 73% of customers not churning
- Features: senior, tech_support, streaming_services
- Ran trained models of Logistic Regression, KNN, and Random Forest models
- Best 3 models used for validation
- Validation showed Logistic Regression to have the best accuracy of 74%
- Tested the model with an accuracy of 74%

## Recommendations 
- Encourage customers to use tech support 
- Offer senior discounts

## How to Recreate Project:
 1. Read this README.md
 2. Download the aquire.py and prepare.py into your working directory
 3. Run the telco_project.ipynb notebook
 4. Explore data and make your own models
