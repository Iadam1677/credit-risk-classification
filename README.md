# credit-risk-classification
Overview of the Analysis
The purpose of this analysis is to build a machine learning model to predict credit risk for loan applicants. The dataset contains various features related to the applicant’s personal and financial information, as well as the loan’s status (whether the loan is healthy or has a high risk of defaulting). The goal is to use the dataset to predict whether a loan is at risk of default (high-risk loan) or is healthy (non-defaulting loan) using a logistic regression model.
The analysis uses logistic regression because it is suitable for binary classification problems, where the output is either one class or another—in this case, whether a loan will be high-risk (1) or healthy (0). This project focuses on assessing the model's performance and determining its ability to accurately predict the status of loans.
Results
•	Accuracy Score: 99.0%
•	Precision for Healthy Loan (Class 0): 1.00
•	Recall for Healthy Loan (Class 0): 0.99
•	Precision for High-Risk Loan (Class 1): 0.84
•	Recall for High-Risk Loan (Class 1): 0.94
•	F1-Score for High-Risk Loan (Class 1): 0.89
Confusion Matrix:
	         Predicted 0 (Healthy)	          Predicted 1(High-Risk)
Actual 0        	18,765	                             50
Actual 1    	         40	                             579

Summary:
The logistic regression model performed exceptionally well, with an overall accuracy of 99%. It showed near-perfect results for predicting healthy loans, with a precision of 1.00 
and recall of 0.99. This indicates that the model is very reliable when identifying healthy loans and almost never misclassifies them as high-risk.
For high-risk loans, the model's performance was also strong, with a precision of 0.84 and recall of 0.94, resulting in an F1-score of 0.89. This means the model is fairly effective at identifying high-risk loans, but there is some room for improvement in reducing false positives (loans that are predicted to be high-risk but are actually healthy).
Recommendation:
I recommend using the logistic regression model for predicting loan risk due to its high accuracy (99%) and strong performance in identifying both healthy and high-risk loans. However, there is still room for improvement in precision for high-risk loans, which could be addressed through techniques like oversampling the minority class or further tuning the model's hyperparameters.
In summary, while the model is highly effective, further improvements could be made to reduce false positives and make the model even more robust for real-world use, especially in a financial context where reducing risk is critical.
