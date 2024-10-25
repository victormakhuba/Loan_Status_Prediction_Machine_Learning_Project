# Loan_Status_Prediction_Machine_Learning_Project

**1. Overview**
In this project, the objective is to develop a machine learning model using Python that predicts whether a loan application will be approved (loan status: approved or not approved) based on various applicant details. A classification algorithm is used to categorize the loan status based on the provided data.

**2. Workflow**

**2.1 Data Collection**

The dataset used for this project contains multiple features related to loan applicants, such as:

ApplicantIncome
CoapplicantIncome
LoanAmount
Loan_Amount_Term
Credit_History
Gender
Married
Dependents
Education
Self_Employed
Property_Area
Loan_Status (target variable)

**2.2 Data Preprocessing**

Before training the model, I performed the following preprocessing steps:

Handling missing values: Imputed missing data to ensure the dataset was complete.
Categorical Encoding: Categorical variables such as gender and education were converted into numerical values using encoding techniques.
Feature Scaling: Standardized numerical features using StandardScaler to ensure they contribute equally to the model.

**2.3 Data Splitting**

The dataset was split into training and testing sets using an 80-20 ratio with train_test_split from Scikit-learn. The training set was used to fit the model, while the testing set helped evaluate its performance on unseen data.

**2.4 Model Training**

I implemented a classification model, initializing a Logistic Regression classifier. This algorithm was trained using the training dataset to predict the loan status based on the provided features.

**2.5 Model Evaluation**

The model was evaluated using accuracy, precision, recall, and F1-score metrics on both the training and testing sets. An accuracy score above 75% was considered a good indication of the model’s ability to generalize to new data.

**2.6 Prediction System**

Finally, a prediction system was created to allow users to input new loan application data and receive predictions on whether the loan will be approved or not.

**3. Coding Environment**

I used Jupyter Notebook in VSCode as the development environment for this project. Various libraries were imported to handle the data and build the model, including:

pandas for data manipulation
numpy for numerical operations
scikit-learn for model training and evaluation
matplotlib and seaborn for data visualization
