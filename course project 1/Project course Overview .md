## Project Overview
my project is a data analysis and machine learning project using a dataset of computer science students. The goal is to predict the students’ future career paths based on various features such as gender, age, GPA, and their interest in different domains.

## Key Steps in my Project

# 1.Data Loading and Inspection:
Load the dataset (cs_students.csv) and inspect its structure and contents.

# 2.Data Cleaning:
Remove unnecessary columns (Student ID, Name, Major, Projects) to focus on relevant features.

# 3.Data Visualization:
Create visualizations to understand the distribution of features like gender, age, GPA, and interested domains.

# 4.Encoding Categorical Variables:
Convert categorical variables (e.g., gender, interested domain, programming skills) into numerical format using LabelEncoder

# 5.Handling Missing Values and Duplicates:
Check for and handle any missing values and duplicate entries in the dataset.

# 6.Model Preparation:
Split the data into features (X) and target (y), and then into training and testing sets.

# 7.Scale the features using StandardScaler to standardize the data.

# 8.Model Initialization and Evaluation:
Initialize multiple machine learning models (Decision Tree, Random Forest, Gradient Boosting).
Define a function to train and evaluate these models using metrics like accuracy, precision, recall, and F1 score.

# 9.Results Display:
Compile the evaluation results into a DataFrame for easy comparison of model performance.
Objective
The main objective is to build and evaluate different machine learning models to predict the future career paths of students based on their academic and personal attributes.