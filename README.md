# Hiring Salary Prediction For HR Department

## Table of Content

- [Project Overview](#project-overview)
- [Technologies](#technologies)
- [Dataset](#dataset)
- [Predictive Analysis](#predictive-analysis)


### Project Overview

![hiring salary prediction](https://github.com/user-attachments/assets/55467e2a-8681-4212-bf43-a73a58815515)


HR will decide the salary of candidates from the hiring statics for a firm

This project is aimed at building a machine learning model for HR Department that can help them decide salaries for future candidates based on their Experience, Written Test Score and Personal Inrterview Score

### Technologies

- Programming Language: Python
- Libraries: NumPy, Pandas, Scikit-Learn, Matplotlib, Seaborn
- Tool: Jupyter Notebook

### Dataset

The Dataset used in this analysis is hiring.csv, which contains three independent features(experience, test_score(out of 10), interview_score(out of 10)) and one dependent feature (salary($))

### Predictive Analysis

Predict salaries for candidates with
1. 2 years experience, 9 test score, 6 interview score
2. 12 years experience, 10 test score, 10 interview score

        reg = linear_model.LinearRegression()
        reg.fit(data[['experience','test_score(out of 10)','interview_score(out of 10)']], data['salary($)'])
        
        reg.predict([[2, 9, 6]])
        
        reg.predict([[12, 10, 10]])

(See the .ipynb file for code and steps)
