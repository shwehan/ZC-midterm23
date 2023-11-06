# ZC-midterm23
Midterm project

## Description of the problem
* Used the data of Synthetic Financial Datasets for Fraud Detection. https://www.kaggle.com/datasets/ealaxi/paysim1/data. It is a synthetic dataset of transaction data of one month from a mobile mone service simulator called PaySim that aggregated the data from the private dataset to generate the dataset that is similar to the normal operation of the transactions and having malicious behavior to classify the performance of the fraud detection methods.

## Instructions on how to run the project

## Data
* Data columns are
  step |	type  |	amount  |	nameOrig  |	oldbalanceOrg  |	newbalanceOrig  |	nameDest  |	oldbalanceDest  |	newbalanceDest  |	isFraud  |	isFlaggedFraud
* Explanation of the columns (Credit to kaggle data)
* In the notebook.ipynb, it already has added the kaggle set up to download the data.   
  - Includes, Data preparation and data cleaning
  - EDA, feature importance analysis
  - Model selection process and (parameter tuning)
* In the Script train.py 
  - Training the final model
  -  Saving it to a file (e.g. pickle)  
* Script predict.py 
  - Loading the model
  - Serving it via a web service (with Flask)
