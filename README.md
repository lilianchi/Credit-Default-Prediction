### Credit-Default-Prediction
In-class Kaggle competition for MGMT 571 at Purdue University.
https://www.kaggle.com/c/credit-default-project

Credit Default forecast has been a subject of interest for every credit card company, and the accurate prediction on default can balance the lenders' risk and return. Based on users' historical and demographical information, lenders can modify their policy to the borrowers such as charging a higher rate for higher risks. Overall speaking, the aim of predicting credit default is to develop a predictive model that utilizes historical payment status and certain demographical information to evaluate the likeliness of credit default.

### Programming language
SAS EM

### Authors
* Li-Ci Chuang
* Rachel Fagan
* Yi-Hsuan Hsu

### Data
* creditDefault_Train.csv - the training set with 23 attributes and 1 target variable
* creditDefault_Test_X.csv - the test set with 23 predictors
* creditDefault_sample_submission.csv - a sample submission file in the correct format (Submission files should contain the predicted probability of bankruptcy for each test sample.
The file should contain a header and have the following format:
ID, Default
1,0.01
2,0.11
3,0.23
4,0.63

### Data Fields
* Limit - Credit limit
* Sex - The Sex of users
* Education - The education level of users
* Marriage - The marriage status of users, they are either Married, Single, or Other.
* Age - The normalized age of users
* Status_1 - Number of months that payment was delayed for the first time period.
* Status_2 - Number of months that payment was delayed for the second time period.
* Status_3 - Number of months that payment was delayed for the third time period.
* Status_4 - Number of months that payment was delayed for the fourth time period.
* Status_5 - Number of months that payment was delayed for the fifth time period.
* Status_6 - Number of months that payment was delayed for the sixth time period.
* Statement_1 - Statement balance for the first time period.
* Statement_2 - Statement balance for the second time period.
* Statement_3 - Statement balance for the third time period.
* Statement_4 - Statement balance for the fourth time period.
* Statement_5 - Statement balance for the fifth time period.
* Statement_6 - Statement balance for the sixth time period.
* Payment_1 - Payment made for the first time period.
* Payment_2 - Payment made for the second time period.
* Payment_3 - Payment made for the third time period.
* Payment_4 - Payment made for the fourth time period.
* Payment_5 - Payment made for the fifth time period.
* Payment_6 - Payment made for the sixth time period.
* Default - Indicating whether or not the user default: 1 = default, 0 = not default.

### Model 1
Gradient Boosting

### Model 1
Neural Network
Gradient Boosting
HP Forest

### Evaluation Metric
AUC (area under the receiver operator curve)
Team Final Best AUC: 0.74

### Reference
Citation:
We used this source to learn how to use Metadata and Control Point Nodes. 
https://github.com/sassoftware/dm-flow/tree/master/EnsembleModelin
