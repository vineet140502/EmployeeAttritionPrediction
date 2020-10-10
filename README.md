# EmployeeAttrition
Data analytics competition by CNA IITG

## Overview
This comeptition was organized by CNA club IITG as part of thier Summer Analytics Course 2020. 

## Aim
The am of the competition was to predict the probability that an employee will resign the company based on his previous data at work.

## Evalutaion
The evaluation metric for this competition wass AUC score under ROC. ROC is a probability curve and AUC represents degree or measure of separability. Higher the AUC, better the model is at predicting 0s as 0s and 1s as 1s.

## Data 
The data was provided by IBM in the csv format(the same has been included in the repo) and consists of basic-details about the employee, his role in the company and work records.

Data fields:

Id - an anonymous id given to an Employee

Age - Age of an Employee

Attrition - Did the Employee leave the company, 0-No, 1-Yes

BusinessTravel - Travlling frequency of an Employee

Department - Work Department

DistanceFromHome - Distance of office from home

EducationField - Field of Education

EmployeeNumber - Number of Employees in the division of a given Employee

EnvironmentSatisfaction - Work Environment Satisfaction

Gender - Gender of Employee

MartialStatus - Martial Status of an employee

MonthlyIncome - Monthly Income of Employee in USD

NumCompaniesWorked - Number of Companies in which Employee has worked before joining this Company

OverTime - Does The person work overtime

PercentSalaryHike - Average annual salary hike in percentages

StockOptionLevel - Company stocks given to an Employee

TotalWorkingYears - Total working experience of an employee

TrainingTimesLastYear - No. of trainings an employee went through last year

YearsAtCompany - Number of years worked at this company

YearsInCurrentRole - Number of years in current role

YearsSinceLastPromotion - Number of years since last promotion

YearsWithCurrManager - Number of years with the current manager

Education

1 'Below College' 

2 'College' 

3 'Bachelor' 

4 'Master' 

5 'Doctor'

EnvironmentSatisfaction


1 'Low' 

2 'Medium' 

3 'High' 

4 'Very High'

JobInvolvement


1 'Low' 

2 'Medium'

3 'High'

4 'Very High'

JobSatisfaction

1 'Low' 

2 'Medium' 

3 'High'

4 'Very High'

PerformanceRating

1 'Low' 

2 'Good'

3 'Excellent' 

4 'Outstanding'

Behaviour

1 'Good'

2 'Bad'

3 'Not Rated'

CommunicationSkill

1 'Bad'

2 'Average' 

3 'Good'

4 'Better'

5 'Best'

StockOptionLevel

0 'No stocks'

1 'Less Stocks' 

2 'Moderate Stocks'

3 'A lot of Stocks'
