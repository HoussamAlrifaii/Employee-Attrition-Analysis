![Types-of-Employee-Attrition](https://github.com/user-attachments/assets/4379ebb0-e3c6-4701-832b-14090c9223ea)



# Employee Attrition Analysis: Predicting Employee Turnover

## Introduction
In today’s competitive job market, understanding employee attrition is vital for organizations aiming to retain top talent. This project utilizes data analytics to identify the key factors influencing an employee's decision to leave, using advanced modeling techniques to predict attrition risk. By leveraging historical employee data, we aim to inform organizational strategies and reduce turnover rates.




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
**Demographics**: Age, Attrition, Gender, Monthly Income, Job Satisfaction, Performance Rating  
**Job History**: Employee Number, Job Role, Years at Company, Years in Current Role, Num Companies Worked  
**Attrition Indicators**: Attrition Status, Reason for Leaving  
**Additional Variables**: Business Travel, Daily Rate, Department, Distance From Home, Education, Education Field, Employee Count, Environment Satisfaction, Hourly Rate, Job Involvement, Job Level, Marital Status, Monthly Rate, Over 18, Over Time, Percent Salary Hike, Relationship Satisfaction, Standard Hours, Stock Option Level, Total Working Years, Training Times Last Year, Work-Life Balance, Years Since Last Promotion, Years with Current Manager  

## Data Dictionary:
| Variable                    | Description                                                    |   
|-----------------------------|----------------------------------------------------------------|  
| Age                         | Age of the employee                                           |   
| Attrition                   | Indicates whether the employee left (Yes/No)                 |  
| Business Travel             | Frequency of business travel (Travel Frequently, Travel Rarely, Non-Travel) |  
| Daily Rate                  | Daily wage of the employee                                    |  
| Department                  | Department where the employee works                           |  
| Distance From Home          | Distance of the employee's home from the workplace           |  
| Education                   | Education level of the employee                               |  
| Education Field             | Field of education (e.g., Life Sciences, Marketing)         |  
| Employee Count              | Total count of employees (likely a constant value)           |  
| Employee Number             | Unique identifier for each employee                           |  
| Environment Satisfaction     | Satisfaction level with the work environment (scale of 1-4)  |  
| Gender                      | Gender of the employee (Male/Female)                         |  
| Hourly Rate                 | Hourly wage of the employee                                   |  
| Job Involvement             | Level of involvement in the job (scale of 1-4)              |  
| Job Level                   | Level of the job (scale)                                     |  
| Job Role                    | Current job role of the employee                              |  
| Job Satisfaction            | Employee's job satisfaction score                             |  
| Marital Status              | Marital status of the employee                                |  
| Monthly Income              | Monthly salary of the employee                                |  
| Monthly Rate                | Monthly rate for the employee                                 |  
| Num Companies Worked        | Number of companies the employee has worked for              |  
| Over 18                     | Indicates if the employee is over 18 years old (Yes/No)     |  
| Over Time                   | Indicates if the employee works overtime (Yes/No)            |  
| Percent Salary Hike         | Percentage increase in salary                                 |  
| Performance Rating          | Rating of employee performance                                 |  
| Relationship Satisfaction    | Satisfaction level with relationships at work (scale of 1-4) |  
| Standard Hours              | Standard hours for the employee's role                       |  
| Stock Option Level          | Level of stock options (scale)                               |  
| Total Working Years         | Total years of working experience                             |  
| Training Times Last Year    | Number of training sessions attended in the last year        |  
| Work Life Balance           | Work-life balance satisfaction level (scale of 1-4)         |  
| Years At Company            | Total years the employee has worked at the company           |  
| Years In Current Role       | Years in the current job role                                 |  
| Years Since Last Promotion   | Years since the last promotion                                |  
| Years With Current Manager  | Years working with the current manager                        | 



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
