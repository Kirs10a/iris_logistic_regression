# iris_logistic_regression
This project demonstrates the use of logistic regression for binary classification on the classic Iris dataset. Logistic regression is used here to build a simple yet effective classification model.
Objectives
Data Preparation:

Load and explore the Iris dataset.
Encode the target variable to represent Iris-setosa as 0 and other classes as 1 for binary classification.
Model Training:

Use sklearn’s logistic regression function to train the model on the training set.
Evaluation:

Generate predictions on the test set.
Create a confusion matrix to evaluate the model's performance.
Analyze precision, recall, and accuracy based on the confusion matrix.
Custom Accuracy Metrics:

Code Walkthrough
Data Loading and Encoding
Load the dataset and encode the target variable to classify Iris-setosa as 0 and the other species as 1.

Data Splitting
Split the data into training and testing sets to evaluate the model's generalizability.

Model Training
Train a logistic regression classifier using sklearn's LogisticRegression class on the training data.

Confusion Matrix Analysis
Generate a confusion matrix to analyze the model's performance, focusing on:

True Positives (TP): Correctly predicted Iris-setosa
False Positives (FP): Incorrectly predicted as Iris-setosa
True Negatives (TN): Correctly predicted as not Iris-setosa
False Negatives (FN): Incorrectly predicted as not Iris-setosa
Manual Metrics Calculation
Write custom functions to calculate accuracy, precision, and recall, and compare with sklearn’s built-in metrics.

Key Findings
The model provides insights into the accuracy, precision, and recall of logistic regression for binary classification.
The confusion matrix and custom accuracy functions give a deeper understanding of model performance, allowing you to make predictions about improvements in precision or recall.
.
Example Output
Include an example output for:

Confusion Matrix – Visual representation.
Precision, Recall, and Accuracy Metrics – Both custom and sklearn-generated metrics for comparison.

Python 3.x
pandas
matplotlib
numpy
sklearn

How to Use
Clone the repository.
Place the Iris.csv file in the working directory.
Run the Jupyter notebook (iris_logistic_regression.ipynb) cell by cell to see data processing, model training, and evaluation steps.
