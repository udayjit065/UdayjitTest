# Employee data, Heart diseases 

Section 1: Python for Data Science
Task 1: Data Manipulation and Cleaning
Given a CSV file named employee_data.csv with the following columns: EmployeeID,
Name, Department, Salary, JoiningDate, Status.Download the dataset from here:
https://github.com/gurmindero7/test_datasets/blob/main/employee_data.csv
1. Data Cleaning: Write Python code to:
○ Remove any duplicate entries.
○ Handle missing values (you can choose to fill them with a default value or
drop the rows).
○ Convert the JoiningDate column to a proper datetime format.
○ Filter out employees who are no longer working (where Status is
'Resigned').

2. Analysis: After cleaning the data, perform the following:
○ Find the average salary of employees in each department.
○ List all employees who joined after the year 2020.
3. Expected Output: Submit a cleaned DataFrame and the results of your analysis.

Task 2: Data Visualization
Using a public dataset of your choice (for example, Kaggle datasets or any other source),
perform the following:
1. Load the dataset into a Pandas DataFrame.
2. Create at least four meaningful visualizations using Matplotlib or seaborn to
understand the data better.
3. Include one correlation heatmap of all numerical variables in the dataset.
Expected Output: Submit the code, the dataset, and the visualizations.

Section 2: Machine Learning
Task 3: Predictive Modeling (Classification)
You are provided with the Heart Disease dataset. Your task is to build a classification model
to predict the presence of heart disease in a patient based on various health metrics.
1. Dataset Information:
○ Download the Heart Disease dataset from the UCI repository.
Direct link:
https://github.com/gurmindero7/test_datasets/blob/main/heart_data.csv
○ This dataset contains 14 attributes such as age, sex, chest pain type, resting
blood pressure, cholesterol level, and more. The target variable is target(0
indicates no heart disease, 1- indicates heart disease).

2. Data Preprocessing:
○ Replace any missing or undefined values.
○ Convert categorical variables into numerical (using techniques such as
one-hot encoding or label encoding).
○ Normalize or scale features if necessary.
3. Task: Build a machine learning classification model to predict heart disease (use
binary classification where 0 = no heart disease, 1 = presence of heart disease).
○ Split the data into training and testing sets.
○ Train the model using one of the following algorithms:
■ Logistic Regression
■ Decision Tree
■ Random Forest
○ Evaluate your model using accuracy, precision, recall, and F1 score.
4. Expected Output: Submit the code, evaluation metrics, and a brief explanation of
why you chose this specific model.
