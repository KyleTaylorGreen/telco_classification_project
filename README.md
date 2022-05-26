# Burned by Telco Churn - Classification Project

# Project Overview:

## What? 
> * Discover key drivers of churn at Telco                                               
> * Make a predictive model of how likely someone is to churn                               
> * Make recommendations to curb churn                                                   
> * Deliver results in a final report notebook and record predictions.                       

## Why? 
> Find out why customers churn to make data-driven business changes and target our highest areas of opportunity to create the most financial gain/impact.

## How? 
> Acquire data, clean it, explore it, model it.


## Questions:
- Which categories are related to churn?
- Is churn related to tenure?
- Is churn related to monthly charges?
- Do people churn quickly or are they a customer for years before quitting?

Data Dictionary

# Project Planning

* Create acquire.py module to obtain data from the codeup database, cache them for later use.
* Create prepare.py module to prepare/clean the data (handling missing values, encoding for the model, etc.)
* Create/use functions to explore variables through visualization and statistical testing, write down any insights gained through both methods. Hypothesis required for each statistical test.
* Establish baseline accuracy for our target variable.
* Create several models using training data, then evaluate the models on both training and validate data.
* Take the best performing model and test it on the test data.
* At the same time, save the predictions to a csv with the values of customer_id, the probability of our target variable, and the model's prediction.
* Document conclusions, takeaways, and recommendations.

To reproduce this project:

 Read this README.md
 Download the and place the following files in your directory:
  >acquire.py
  >prepare.py
  >modeling.py
  >exploration.py
  >split.py
  >Final_Report_notebook.ipynb
 Add your own env file to your directory with user, password and host credentials.
 Run the Final_Report_notebook.ipynb notebook.

# Executive Summary - Findings & Next Steps

### Key Drivers of Churn: Electronic Check, Monthly Charges

### Model:
 - Logistic Regression had the best performance and had **80.67%** accuracy on testing data.
 - Beat baseline accuracy by **9.86%**

### Recommendations: 
- Text reminders of upcoming bills
- Small monthly discounts when enrolled in autopay
- Normalization of monthly charges


### Future Analysis/Action:
* Identify differences in subgroups of customers and determine the reason for variance in monthly cost for churning and non-churning customers.
* Employ measures to reduce the variance in costs to reduce monthly costs for churning customers.                                                                                       
* Conduct a study on the website sign-in and payment system process to see if customers are quitting out at specific spots. 



