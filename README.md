# Loan_Prediction
This is an Analytics Vidhya Hackathon problem statement.I have got an accuracy of 77.77%

## Predict Loan Eligibility for Dream Housing Finance company
Dream Housing Finance company deals in all kinds of home loans. They have presence across all urban, semi urban and rural areas. Customer first applies for home loan and after that company validates the customer eligibility for loan.

Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have provided a dataset to identify the customers segments that are eligible for loan amount so that they can specifically target these customers.

### Train file: CSV containing the customers for whom loan eligibility is known as 'Loan_Status'
                   
Loan_ID-	                     Unique Loan ID,
Gender-	                     Male/ Female,
Married	Applicant  -          married (Y/N),
Dependents-	                 Number of dependents,
Education	 -                  Applicant Education (Graduate/ Under Graduate),
Self_Employed	 -              Self employed (Y/N),
ApplicantIncome	-             Applicant income,
CoapplicantIncome	-           Coapplicant income,
LoanAmount	-                 Loan amount in thousands,
Loan_Amount_Term	   -        Term of loan in months,
Credit_History	-             credit history meets guidelines,
Property_Area	   -            Urban/ Semi Urban/ Rural,
Loan_Status	(Target) -        Loan approved (Y/N)-------->To be Predicted.

### Test file: CSV containing the customer information for whom loan eligibility is to be predicted


Loan_ID	      -               Unique Loan ID,
Gender	   -                  Male/ Female,
Married	     -                Applicant married (Y/N),
Dependents	   -              Number of dependents,
Education	    -               Applicant Education (Graduate/ Under Graduate),
Self_Employed	  -             Self employed (Y/N),
ApplicantIncome	   -          Applicant income,
CoapplicantIncome	 -          Coapplicant income,
LoanAmount	     -            Loan amount in thousands,
Loan_Amount_Term	 -          Term of loan in months,
Credit_History	  -           credit history meets guidelines,
Property_Area	   -            Urban/ Semi Urban/ Rural.

### Submission file format


Loan_ID	      -          Unique Loan ID,
Loan_Status	(Target) -   Loan approved (Y/N)
