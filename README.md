# Loan Approval Prediction Model
We build a loan prediction model that determines if an applicant's application for a loan should be approved or rejected.

# Problem Statement
Loan approval prediction is a binary classification with two outcomes. Whether a loan is approved or rejected. The goal is to identify the model with the maximum accuracy.

## Dataset
The dataset used for this model was taken from Analytics Vidhya: (https://datahack.analyticsvidhya.com/contest/practice-problem-loan-prediction-iii/). 

The dataset has the following columns:

| Column | Description |
| ----------- | ----------- |
| Loan_ID | Unique Loan ID |
| Gender | Male/Female |
| Married | Whether Married: Yes/No |
| Dependents | No. of people depending on the Applicant |
| Education | Graduate/Undergraduate |
| Self_Employment | Whether Self_Employment : Yes/No |
| ApplicantIncome | Applicant Income |
| CoapplicantIncome | Co-Applicant Income |
| LoanAmount | Loan Amount (in thousands) |
| Loan_Amount_Term | Loan Duration |
| Credit_History | Credit History of the Applicant |
| Property_Area | Urban/Semiurban/Rural |
| Loan_Status | Whether Loan Approved: Yes/No |

### Libraries required
* [NumPy](http://www.numpy.org/)
* [Pandas](http://pandas.pydata.org/)
* [SciKit-Learn](http://scikit-learn.org/stable/)
* [Matplotlib](http://matplotlib.org/)
* [Seaborn](https://seaborn.pydata.org/)

### Algorithms
* Random Forest Classifier
* Decision Tree Classifier
* Logistic Regression Classifier
* Ensemble models

# Project Workflow
* Get the data
* Perform Data handling with Pyspark if dataset is big.
* Data cleaning - Imputing missing values and data outliers.
* Explortory data analysis - Visualizing data to get an understanding of the underlying structure.
* Training machine learning models with scikit-learn, Logistic Regression, Decision Trees, Random Forest and Ensemble.
* Fine tune modelS
* Deploy data science model.