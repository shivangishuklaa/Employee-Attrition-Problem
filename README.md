Employee Attrition Prediction 🚪💼
This project focuses on predicting employee attrition using machine learning techniques. By analyzing various features like job role, satisfaction level, salary, and working conditions, the model helps identify employees who are at risk of leaving the organization.

🔍 Problem Statement
Employee attrition is a major concern for HR departments. Understanding the factors that influence employees to leave can help organizations take preventive measures. The goal of this project is to build a predictive model that can classify whether an employee is likely to stay or leave.

🧠 Project Workflow
Data Exploration & Cleaning

Handled missing values and checked data distribution

Converted categorical variables using label encoding and one-hot encoding

Exploratory Data Analysis (EDA)

Visualized trends in attrition by department, satisfaction level, salary, and more

Identified key features correlated with employee churn

Feature Selection & Scaling

Selected relevant features for training

Standardized numerical features for better model performance

Modeling

Implemented classification models including:

Logistic Regression

Random Forest

Decision Tree

K-Nearest Neighbors

Evaluated models using accuracy, confusion matrix, precision, recall, and F1-score

Result

Random Forest gave the best results with an accuracy of ~87%

Feature importance showed that satisfaction level, number of projects, and average monthly hours were key drivers of attrition

📊 Tech Stack
Python

Pandas, NumPy – Data manipulation

Matplotlib, Seaborn – Data visualization

Scikit-learn – ML modeling and evaluation

Jupyter Notebook

📎 How to Use
Clone this repository:

bash
Copy
Edit
git clone https://github.com/shivangishuklaa/Employee-Attrition-Problem.git
cd Employee-Attrition-Problem
Open the notebook in Jupyter and run all cells in sequence to train and evaluate models.

📌 Conclusion
This project shows that machine learning can be a powerful tool for HR analytics. By predicting attrition risks early, companies can improve employee retention and reduce turnover costs.
