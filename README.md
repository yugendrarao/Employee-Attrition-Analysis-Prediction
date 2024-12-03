# Employee-Attrition-Analysis-Prediction
Employee Attrition Analysis &amp; Prediction

### Problem Statement
A client X has an employee attrition/employee turnover problem. They are experiencing loss of employees. HR is seeking to understand why employees are leaving so as to come up with ways of retaining them. According to Statistics, The cost of employee turnover is up to 20% of that employee's salary. This means that if an employee was earning USD 100k, and they leave a company, it would cost that company up to USD 20k to replace that employee.

Cost include:
        
        Cost of off-boarding
        Cost of hiring (advertising, interviewing, hiring)
        Cost of onboarding a new person (training, management time)
        Lost productivity (a new person may take 1-2 years to reach the productivity of an existing person)

        ### Description of the Data
There are two sets of data: “Existing employees” and “Employees who have left”. Following attributes are available for every employee:

    Satisfaction Level
    Last evaluation
    Number of projects
    Average monthly hours
    Time spent at the company
    Whether they have had a work accident
    Whether they have had a promotion in the last 5 years
    Departments (column sales)
    Salary
    Whether the employee has left

    Objective

To understand what factors contributed most to employee turnover/attrition.
To perform clustering to find any meaningful patterns of employee traits.
To create a model that predicts the likelihood if a certain employee will leave the company or not.
To create or improve different retention strategies on targeted employees.
The implementation of this model will allow management to create better decision-making actions.
Summary

Analysis of the data showed some amazing insights.

There were 4 features that contributed the most to employees leaving:

1. Job satisfaction
2. Last evaluation
3. Number of Projects done
4. Average monthly hours worked
There were 3 clusters of employees who left.

1. Employees who had low job satisfaction and high evaluation
2. Employees who had low job satisfaction and low evaluation
3. Employees who had high job satisfaction and high evaluation
The number of Projects done by each employee was also analyzed. It was seen that:

Those who had less than 3 projects left
About half of people who had between 4 to 5 projects left
Those who had 6 projects and above left
There was generally an increase in turnover the more the projects were done or the fewer the projects were done

EDA also showed that:

Sales, IT and Support had the highest attrition rates in the departments
Employees who had less than 150 monthly hours left the company more
Employees who worked between 170 to 230 hours stayed
Employees who worked more than 250 hours left the company more
Overall, analysis showed that attrition rate is 23.8% and job satisfaction is the highest contributing factor/feature

--Process Workflow--

#### Importing the libraries

#### Understanding the data

## Exploratory Data Analysis (EDA)

### Feature Correlation

### Distribution of Employee Satisfaction, Evaluation and Project Count

### Evaluating Satisfaction level vs Last Evaluation Score

### Clusters of employees who left

## Number of Projects
Those who had less than 3 projects left
About half of people who had between 4 to 5 projects left
Those who had 6 projects and above left
###### There is an increase in the rate of leaving with more projects working

## Analysis of those who left by departments

### Distribution of employees who left per department

Sales department had the highest turnover
Sales, Technical Support and support had the overall highest attrition

### Analysis of the distribution of monthly hours for those who left
    Employees who had less than 150 monthly hours left the company more
    Employees who worked between 170 to 230 hours stayed
    Employees who worked more than 250 hours left the company more

### The Turnover or Attrition rate is 23%

### Train 3 models and compare their perfomances on the data

### Logistic Regression F1 (87%)

### Random Forest F1(99%) Accuracy (96%)

### Gradient Boost Classifier Accuracy (94%) F1 (99%)

### We use a ROC graph to compare the perfomance of the models

### Applying some random noise on the Feature importances

Conclusion
Employee satisfaction, number of projects done, evaluation and time spent with the company are the most important features that have been shown to affect turnover.The model can predict attrition or who is most likely to leave up to 94% accuracy
Recommendations

Strategic Recommendations for Retention:

Budget Allocation: Rank employees based on their likelihood of leaving and allocate retention resources accordingly.
Focus on High-Impact Retention: Address dissatisfaction for employees critical to the organization's success.
Continuous Monitoring: Regularly evaluate employee satisfaction and workload to prevent attrition.
