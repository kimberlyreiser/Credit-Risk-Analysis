# Credit-Risk-Analysis
The objective of this endeavor was to develop a machine-learning model capable of assessing borrowers and determining their creditworthiness.
## Analysis Overview
Data Preprocessing:

- Firstly, I imported the lending data from the CSV file and created a DataFrame with relevant columns, including loan_status as the target variable.
Next separated the target variable (loan_status) into y and the features (loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts, derogatory_marks, total_debt) into X.
Data Splitting:

- I then utilized the train_test_split module from scikit-learn to split the dataset into training and testing sets, ensuring randomness with a specified random state (1).
Model Training:

- I instantiated a logistic regression model and trained it using X_train and y_train, specifying a random state (1).
Model Evaluation:

After training the model, I used it to predict loan_status for the X_test data.
With the predictions, you generated a confusion matrix and a classification report to assess the model's performance.

### Results 

Machine Learning Model 0 
  - Accuracy: 1.00
  - Precision : 1.00
  - Recall: 0.99

Machine Learning Model 1 
  - Accuracy: 0.88
  - Precision: 0.85
  - Recall: 0.91

#### Summary 
The model achieves an impressive F1 score of 1.00 for healthy loans (0), indicating exceptional prediction accuracy. Even for high-risk loans (1), it maintains a strong F1 score of 0.88, signifying reliable prediction performance. With an overall F1 score of 0.99, the model demonstrates outstanding accuracy across both categories. Given its objective of identifying high-risk loans, the model excels in this task, making it a valuable tool for assessing an individual's risk level.
