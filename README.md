# SalaryPredictionModel

This project builds a salary prediction model to determine whether a candidate’s requested $160,000 salary is reasonable based on their position level and experience.

Salary data was gathered from research on the candidate’s previous company, analyzing salaries per position level.
The candidate’s Regional Manager role with 2 years experience (Level 6.5 in dataset) was verified through their previous company.
Two models were trained: Linear Regression and Polynomial Regression (degree = 4).
The analysis helps in data-driven salary decisions by comparing the expected salary range with historical salary trends.

---

## Key Findings

- Polynomial Regression provided a more accurate salary trend than Linear Regression.
- The predicted salary for Level 6.5 was compared against the candidate’s $160,000 salary request to assess accuracy.
- The candidate's requested salary was found to be accurate with the model predicting an $158,862 salary.
- The model serves as a decision-support tool for salary negotiations.

---

## Tech Stack

**Python**
Included Libraries:
- Pandas (Data processing)
- NumPy (Numerical operations)
- Scikit-Learn (Machine Learning models)
- Matplotlib (Data visualization)

---
