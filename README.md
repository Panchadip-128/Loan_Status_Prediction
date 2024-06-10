# Loan_Status_Prediction

Loan Prediction Model:
-----------------------
This project involves building a loan prediction model using Support Vector Machine (SVM) and various data preprocessing techniques. The dataset used in this project contains information about various applicants and their loan status, which helps in predicting whether the loan will be approved or not based on the applicant's data.

Dataset:
---------
The dataset contains the following features:

Loan_ID
Gender
Married
Dependents
Education
Self_Employed
ApplicantIncome
CoapplicantIncome
LoanAmount
Loan_Amount_Term
Credit_History
Property_Area
Loan_Status

Data Preprocessing:
-------------------
Handling Missing Values: All missing values are removed from the dataset.
Label Encoding: The categorical variables are converted to numerical values:
        Loan_Status: 'N' to 0, 'Y' to 1
        Dependents: '3+' to 4
        Married: 'No' to 0, 'Yes' to 1
        Gender: 'Male' to 1, 'Female' to 0
        Self_Employed: 'No' to 0, 'Yes' to 1
        Property_Area: 'Rural' to 0, 'Semiurban' to 1, 'Urban' to 2
        Education: 'Graduate' to 1, 'Not Graduate' to 0

Data Visualization:
----------------------
Data visualization is performed using Seaborn:

        Countplot for Education vs Loan_Status
        Countplot for Married vs Loan_Status

        
Model Training:
----------------
Model: Support Vector Machine (SVM) with a linear kernel.
Train-Test Split: The dataset is split into training and test sets with a test size of 10% and stratified sampling based on Loan_Status.
Model Evaluation
The model's performance is evaluated using accuracy score:

Accuracy on training data: 79.86%
Accuracy on test data: 83.33%


Requirements:
--------------
Python 3.x
NumPy
Pandas
Seaborn
Scikit-learn

How to Run:
------------
Clone the repository.  git clone https://github.com/Panchadip-128/Loan_Status_Prediction.git
Install the required libraries.
Place the dataset (loan_data.csv) in the appropriate directory.
Run the provided code.

Contributions if any are welcome.
