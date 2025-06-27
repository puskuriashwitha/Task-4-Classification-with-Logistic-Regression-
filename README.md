# Task-4-Classification-with-Logistic-Regression.
Task 4: Classification with Logistic Regression
About this Task: Hey! In this task, I worked on the famous Titanic dataset to build a binary classification model using Logistic Regression. The main goal was to predict whether a passenger survived (1) or not (0) based on their details like age, fare, class, etc.
What I did in this task:

1 Imported the Titanic dataset using Pandas.

2 Checked number of rows, columns, and basic info to understand the data types and structure.

3 Handled missing values — filled ‘Age’ with median, and dropped ‘Cabin’ column since it had too many nulls.

4 Converted categorical data to numbers using Label Encoding (like Sex, Embarked, etc.).

5 Split the data into train and test sets (80% for training, 20% for testing).

6 Standardized the numeric columns (like Age, Fare) using StandardScaler to keep all values on the same scale.

7 Fitted a Logistic Regression model using sklearn.linear_model.LogisticRegression().

8 Evaluated model performance:

Printed Confusion Matrix

Got Precision, Recall, F1-Score, and Accuracy using classification_report()

Plotted ROC Curve and calculated AUC Score

9 Tuned the prediction threshold from default 0.5 to 0.4 to check how it affects precision and recall.

10 Explained the sigmoid function working in logistic regression — which converts outputs into probabilities between 0 and 1.
