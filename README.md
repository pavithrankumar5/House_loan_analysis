# House_loan_analysis

DESCRIPTION:

For safe and secure lending experience, it's important to analyze the past data. In this project, you 
have to build a deep learning model to predict the chance of default for future loans using the 
historical data. As you will see, this dataset is highly imbalanced and includes a lot of features that 
make this problem more challenging.


Objective: Create a model that predicts whether or not an applicant will be able to repay a loan 
using historical data.

The following procedures are followed in this project:

- Exploratory data analysis and visualization
- Splitting a dataset into training, validation & test sets
- Filling/imputing missing values in numeric and categorical columns
- Scaling features to a (0,1) range
- Encoding categorical columns as dummy variables (one hot encoder) - Used oversampling smote technique to make data balanced
- Training deep learning models using tensorflow with keras
- Evaluating a model using a validation set 
- Plotting auc curve


The project achieves the following results:

a) Developed a predictive model with an accuracy of 95% and Sensitivity of 90% and an AUC-ROC of 
98% on the test data.
