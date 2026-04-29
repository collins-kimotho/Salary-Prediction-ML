# Salary Prediction using Simple Linear Regression

<img width="1400" height="933" alt="regression" src="https://github.com/user-attachments/assets/d2e783b9-42a1-45d6-8839-d3341449df93" />


## Project Overview
The project applies **Simple Linear Regression** to model and predict salaries based on years of experience.

## Problem Statement
Can we predict a person's salary based on their years of experience?

Using historical salary data, we train a regression model to learn the relationship between:
* Input(X): Years of Experience
* Output(Y): Salary

**Model Used:** Simple Linear Regression(`sklearn.linear_model.LinearRegression`)

The model learns a linear relationship of the form:

y = mx + c

For this project:

y = 194.68x + 2218.33

## Key Insights
1. **Slope (m=104.68)**
* For each additional year of experience, salary increases by approximately 194.68 units.
* This quantifies the rate of growth in salary.
* Experience has a positive and consistent impact on salary

2. **Intercept(c=2218.22)**
* Estimated salary when experience = 0
* Represents a baseline salary
* May not always be realistic in real life, but is mathematically necessary for the model

3. **R^2 Score = 0.88**
* The model explains 88% of the variation in salary
* Represents a strong relationship between experience and salary
* The model fits the data well
* The remaining 12% could be due to factors like:
    * Education
    * Industry
    * Location
    * Skills

4. **Mean Squared Error = 35,796.96**
* Measures average squared difference between predicted and actual salary.
* Some prediction error exists as expected in real-world data
* Error grows larger for outliers or unusual salary values

## Tech Stack
* Python
* Pandas
* Numpy
* Matplotlib
* Scikit-learn

