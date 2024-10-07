# Employee Attrition Analysis: Predicting Employee Turnover

## Introduction
In today’s competitive job market, understanding employee attrition is vital for organizations aiming to retain top talent. This project utilizes data analytics to identify the key factors influencing an employee's decision to leave, using advanced modeling techniques to predict attrition risk. By leveraging historical employee data, we aim to inform organizational strategies and reduce turnover rates.


![Employee Attrition](docs/employee_attrition.jpg)

## Project Overview
The Employee Attrition Analysis project focuses on predicting employee turnover within an organization. Using a comprehensive dataset containing employee demographics and job performance metrics, this project explores patterns in attrition, assesses risk factors, and investigates potential biases in predictive modeling. The insights generated aim to support informed decision-making related to employee retention strategies.

## Features

### Data Preprocessing:
- Cleans and transforms data related to employees, including handling missing values and encoding categorical variables.

### Risk Assessment:
- Analyzes risk factors and generates insights based on predictive models, focusing on overall attrition risk.

### Visualization:
- Provides graphical representations of data trends, risk distributions, and attrition patterns.

### Predictive Modeling: 
- Implements machine learning models, including Random Forest and TensorFlow DNN, to predict the likelihood of attrition based on various factors.

### Bias Analysis:
- Investigates potential biases in predictions, ensuring fair treatment across different demographic groups.

## Dataset
**Demographics**: Employee ID, Gender, Age, Salary, Job Satisfaction, Performance Rating  
**Job History**: Years at Company, Job Role, Number of Companies Worked  
**Attrition Indicators**: Attrition Status, Reason for Leaving  
**Additional Variables**: Work-life Balance, Training Hours, Overtime Status

## Data Dictionary:
| Variable                | Description                                 | 
|-------------------------|---------------------------------------------|
| Employee ID             | Unique identifier for each employee        |
| Gender                  | Gender of the employee (Male/Female)      |
| Age                     | Age of the employee                        | 
| Salary                  | Annual salary of the employee              |
| Job Satisfaction        | Employee's job satisfaction score          |
| Performance Rating      | Rating of employee performance              |
| Years at Company        | Total years the employee has worked        |
| Job Role                | Current job role of the employee           |
| Attrition Status        | Indicates whether the employee left (Yes/No) |

![Employee Attrition Visualization](docs/attrition_visualization.png)

## Steps Taken to Train the Model:
**1. Data Preparation:**
- Collected and preprocessed data, ensuring demographic features and job history records were cleaned, encoded, and normalized where necessary. 
- Split the dataset into training and testing sets (typically 80-20) to ensure the model generalizes well to unseen data.

**2. Model Selection:**
- Experimented with several classification algorithms (e.g., Logistic Regression, Random Forest, Support Vector Machines) and selected models based on initial performance metrics.
- Focused on Random Forest and TensorFlow DNN for their ability to capture complex patterns.

**3. Training Process:**
- Trained models using the selected algorithms on the training data.
- Applied k-fold cross-validation to prevent overfitting and tune hyperparameters effectively.

## Key Objectives of the Project
### The key objectives of this project are:
**1. Develop Predictive Models:** Build and train classification models that accurately predict employee attrition based on available data.

**2. Utilize Demographic and Job History Data:** Incorporate demographic information and job performance metrics to enhance prediction accuracy.

**3. Evaluate Model Performance:** Assess model accuracy and identify the most important factors contributing to attrition predictions.

**4. Address Bias and Fairness:** Ensure the model minimizes bias, particularly regarding demographic variables that could disproportionately affect certain groups.

## Impact:
Through exploratory data analysis and predictive modeling, several key insights were discovered. The Random Forest model achieved an accuracy of **92.3%**, while the TensorFlow DNN reached **91.7%** accuracy, indicating strong predictive capabilities. The findings underscore the importance of factors such as **job satisfaction** and **salary levels** in influencing attrition decisions. Implementing targeted strategies to improve job satisfaction and offer competitive compensation can significantly enhance employee retention, driving long-term organizational success.
