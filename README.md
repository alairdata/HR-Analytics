# HR-Analytics

## 1. Dataset Overview

HR analytics, also referred to as people analytics, workforce analytics, or talent analytics, involves gathering, analyzing, and reporting HR data. It is the collection and application of talent data to improve critical talent and business outcomes. This enables organizations to measure the impact of various HR metrics on overall business performance and make data-driven decisions. HR analysts are primarily responsible for interpreting and analyzing vast datasets.

This dataset contains employee-related information for an organization, primarily focused on factors influencing employee attrition, job satisfaction, and compensation. The data can be used for HR analytics, predictive modeling, and understanding employee engagement trends.

## Project Relevance

This dataset has real-world applications in HR decision-making, workforce planning, and predictive analytics. Some key applications include:
- Analyzing factors contributing to employee attrition.
- Identifying relationships between salary, job satisfaction, and performance.
- Assessing work-life balance and overtime impacts.
- Understanding demographic trends within the workforce.

Data Source: Originally sourced from a publicly available HR analytics dataset from Kaggle - https://www.kaggle.com/datasets/anshika2301/hr-analytics-dataset/data

## 2. Project Goal

The purpose of this project is to analyze employee attrition and job satisfaction using the HR analytics dataset. By exploring key trends and patterns in the data, the goal is to uncover insights that can help businesses improve employee retention, enhance workplace satisfaction, and optimize compensation structures. Additionally, this project serves as a portfolio piece to showcase data analysis, visualization, and predictive modeling skills.

Key objectives include:
- Understanding the main drivers of employee attrition.
- Analyzing the impact of compensation and job satisfaction on retention.
- Investigating the role of work-life balance and career growth.
- Applying machine learning techniques to predict attrition.

## 3. Column Descriptions

- EmpID: Unique identifier for each employee.
- Age: Employee's age in years.
- AgeGroup: Categorized age range (e.g., 20-30, 30-40).
- Attrition: Indicates whether an employee has left the company (Yes/No).
- BusinessTravel: Frequency of business travel (No Travel, Rarely, Frequently).
- DailyRate: Employee’s daily income rate.
- Department: The department the employee works in (e.g., HR, IT, Sales).
- DistanceFromHome (mins): Travel time to work in minutes.
- Education: Education level (e.g., High School, Bachelor's, Master's).
- EducationField: Employee's field of study (e.g., Engineering, Marketing, HR).
- EmployeeCount: Likely a constant column representing total employee count.
- EmployeeNumber Another unique identifier for employees (may duplicate EmpID).
- EnvironmentSatisfaction: Employee’s satisfaction with the workplace environment (scale of 1-4).
- Gender: Employee's gender (Male/Female).
- HourlyRate: Employee’s hourly wage.
- JobInvolvement: Employee’s engagement level at work (scale of 1-4).
- JobLevel: Seniority level in the organization (e.g., Entry, Mid, Senior).
- JobRole: Specific job title within the department.
- JobSatisfaction: Employee’s satisfaction with their job role (scale of 1-4).
- MaritalStatus: Employee’s marital status (Single, Married, Divorced).
- MonthlyIncome: Employee’s total monthly salary.
- SalarySlab: Categorized salary range (e.g., Low, Medium, High).
- MonthlyRate - Monthly payment rate.
- NumCompaniesWorked - Number of previous employers before this company.
- Over18 - Whether the employee is over 18 (typically "Yes").
- OverTime - Indicates if the employee works overtime (Yes/No).
- PercentSalaryHike - Percentage increase in salary during performance review.
- PerformanceRating - Employee’s performance rating (scale of 1-5).
- RelationshipSatisfaction - Employee’s satisfaction with workplace relationships (scale of 1-4).
- StandardHours - Standard work hours per week (likely a fixed value).
- StockOptionLevel - Stock options granted to the employee (scale of 0-3).
- TotalWorkingYears - Total years of work experience.
- TrainingTimesLastYear - Number of training sessions attended in the last year.
- WorkLifeBalance - Employee’s perception of work-life balance (scale of 1-4).
- YearsAtCompany - Number of years the employee has worked at the company.
- YearsInCurrentRole - Number of years spent in the current job role.
- YearsSinceLastPromotion - Time since the employee’s last promotion.
- YearsWithCurrManager - Number of years working under the current manager.

## 4. Business Questions & Analytical Opportunities
### Attrition Analysis
- What factors contribute to employee attrition?
- Do employees with lower satisfaction scores leave more often?
- How does commute time affect attrition rates?
- Are younger employees or those with fewer years at the company more likely to leave?
- Does working overtime correlate with higher attrition?

### Compensation & Performance
- Does salary impact job satisfaction and retention?
- Are high performers receiving better salary hikes?
- Do employees in certain job roles or departments earn significantly more than others?
- Do employees with stock options tend to stay longer?

### Work-Life Balance & Engagement
- Do employees working overtime report lower job satisfaction?
- How does training impact retention and job involvement?
- What is the effect of work-life balance on performance?
- Do employees with a better work-life balance stay longer?

### Career Growth & Predictive Modeling
- Do employees who receive frequent promotions tend to stay longer?
- Can we build a model to predict which employees are most at risk of leaving?
- What combination of factors provides the best prediction accuracy?

### 5. Data Summary & Preprocessing Notes
- Missing Values: Some columns may have missing values (e.g., EnvironmentSatisfaction, WorkLifeBalance). Consider imputing missing data using mean/mode.
- Categorical Encoding: Columns like BusinessTravel, MaritalStatus, and JobRole need encoding for machine learning models.
- Standardization: MonthlyIncome, HourlyRate, and DistanceFromHome could benefit from normalization for better model performance.

