# Data Analysis of Company Employees - Classification of Employees into Resigned and Non-Resigned

***STATUS:*** **Completed**


## Project Objective:

Based on HR data, perform the following tasks:

1. Calculate basic statistics for variables.
2. Calculate and visualize the correlation matrix for quantitative variables. Identify the two most correlated and two least correlated variables.
3. Calculate the number of employees in each department.
4. Show the distribution of employees by salaries.
5. Show the distribution of employees by salaries in each department separately.
6. Test the hypothesis that employees with high salaries spend more time at work than employees with low salaries.
7. Calculate the following indicators among resigned and non-resigned employees (separately):
  ● Percentage of employees with promotions in the last 5 years
  ● Average satisfaction level
  ● Average number of projects
8. Split the data into test and training samples. Build an LDA model predicting whether an employee resigned based on available factors (excluding department and salary). Evaluate the model's quality on the test sample.

## Project Description:

The project involves analyzing a dataset collected by the HR department. It is necessary to provide general information about the dataset, calculate a few indicators, and classify the data into two target variables using Linear Discriminant Analysis (LDA).


## Research Findings:

1. There are a total of 10 departments. In the Sales department, 3239 people work, in Technical - 2244, Support - 1821, IT - 976, R&D - 694, etc.
2. The distribution of salaries in the company cannot be called normal; a large part of the staff receives a low salary.

### Salary Distribution Graph from Low to High:

<img src="https://i.imgur.com/us6IBdI.png" alt="Top"/>

1. The only department with a normal distribution of salaries is management.
2. There are no statistically significant differences in the time spent at work between employees with high and low salaries. In other words, we cannot say that one group spends more time at work than the other.
3. The LDA model classifies employees as resigned or non-resigned with an accuracy of 76%.

## Utilizing Research Results:

The research results are intended to be used to predict whether an employee is likely to resign in the near future.


## Project Technical Features:

The data is noisy with duplicates (both explicit and implicit) - preprocessing has been conducted.
To answer the research questions, data was grouped in various dimensions.


## Project Tools

- Python
- Pandas
- Sklearn
- Matplotlib.pyplot
