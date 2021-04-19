This dataset is from the Analytics-Vidhya Hackathon. This submission scored 81.25% and its on position 42 out of 60132 at 29/06/2020. 30 submissions were made in total
Feature Engineering including taken care of null values, outliers, skewed features were all implemented here. The solution is commented throughout to make it easy for all to
understand and use it as a guide in their own work. Hyperparameter tuning was also implemented to find the right combination of parameters to give the best results. This model
could have been improved and achieved a better score by removing certain features and null values that had a very negative correlation with the target data but due to competition
rules regrading keeping the same number of rows, this was not done.
Details about the dataset are as follows
Predict Loan Eligibility for Dream Housing Finance company
Dream Housing Finance company deals in all kinds of home loans. They have presence across all urban, semi urban and rural areas. Customer first applies for home loan and 
after that company validates the customer eligibility for loan.

Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form.
These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others.
To automate this process, they have provided a dataset to identify the customers segments that are eligible for loan amount so that they can specifically target these customers.
Variable Description
*Loan_ID ------> Unique Loan ID
*Gender ------> Male/ Female
*Married ------> Applicant married (Y/N)
*Dependents ------> Number of dependents
*Education ------> Applicant Education (Graduate/ Under Graduate)
*Self_Employed ------> Self employed (Y/N)
*ApplicantIncome ------> Applicant income
*CoapplicantIncome ------> Coapplicant income
*LoanAmount ------> Loan amount in thousands
*Loan_Amount_Term ------> Term of loan in months
*Credit_History ------> Credit history meets guidelines
*Property_Area ------> Urban/ Semi Urban/ Rural
*Loan_Status (Target) ------> Loan approved (Y/N)
Evaluation Metric
Your model performance will be evaluated on the basis of your prediction of loan status for the test data (test.csv), which contains similar data-points as train
except for the loan status to be predicted. Your submission needs to be in the format as shown in 
sample submission.
