# Bank-Customer-Churn-Prediction

Problem: Bank Customer Churn Prediction

The task is to build a model that predicts whether a bank customer will leave (churn) or stay. 
This binary classification problem involves using customer data to train machine learning algorithms 
and determine the likelihood of customer churn.

Approach:

Data Preparation: The initial step involves loading and preprocessing the dataset. 
The data is split into feature variables (X) and the target variable (Y). To handle categorical features like "Country," 
one-hot encoding is utilized to convert them into numerical representations. The data is then divided into training and 
testing sets using train_test_split for model evaluation.

Model Selection and Training: Various supervised machine learning algorithms are employed to build predictive 
models for customer churn. The selected algorithms include Logistic Regression, Decision Tree, Random Forest, 
Support Vector Machine (SVM), and Gradient Boosting Classifier. 

Model Evaluation: After training the models on the training data, they are assessed on the testing data using performance 
metrics such as accuracy, precision, recall, and F1-score. Additionally, confusion matrices are generated to analyze 
the models' effectiveness in correctly classifying churned and non-churned customers.

Visualization: For effective model comparison and result interpretation, the evaluation metrics for each algorithm are 
presented in a bar chart. The confusion matrices are visualized as heatmaps to provide a clearer understanding of 
the models' performance.
