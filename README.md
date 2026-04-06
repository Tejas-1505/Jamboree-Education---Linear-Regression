# Jamboree-Education---Linear-Regression
My Case studies with Scaler Academy

## About Jamboree

Jamboree has helped thousands of students like you make it to top colleges abroad. Be it GMAT, GRE or SAT, their unique problem-solving methods ensure maximum scores with minimum effort.
They recently launched a feature where students/learners can come to their website and check their probability of getting into the IVY league college. This feature estimates the chances of graduate admission from an Indian perspective.


## Problem Statement

Your analysis will help Jamboree in understanding what factors are important in graduate admissions and how these factors are interrelated among themselves. It will also help predict one's chances of admission given the rest of the variables.


## Dataset:

**Column Profiling:**

Serial No. (Unique row ID)

GRE Scores (out of 340)

TOEFL Scores (out of 120)

University Rating (out of 5)

Statement of Purpose and Letter of Recommendation Strength (out of 5)

Undergraduate GPA (out of 10)

Research Experience (either 0 or 1)

Chance of Admit (ranging from 0 to 1)

# Insights:

💡Situation:
Jamboree, a leading educational institution, aims to enhance student admissions to Ivy League colleges by predicting admission probabilities for Indian applicants using a newly introduced website feature.

💡Task:
We have conducted a comprehensive regression analysis to identify key predictors influencing admission chances and provide actionable insights for optimizing the admissions process.

💡Action:
* Conducted thorough data preprocessing, including handling missing values, treating duplicates, and checking for outliers to ensure data integrity.

* Implemented univariate and bivariate analyses using statistical and graphical methods to understand variable distributions and relationships, highlighting the significance of factors like GRE score, TOEFL score, and CGPA. Built and evaluated Linear Regression, Ridge Regression, and ElasticNet models to predict admission probabilities, assessing model performance metrics such as MAE, RMSE, R-squared, and adjusted R-squared.

* Investigated multicollinearity using VIF scores, confirming robust model predictors with minimal collinearity issues despite high correlations among variables.

* Analyzed residual plots for normality and heteroscedasticity, informing model refinement strategies and suggesting potential data augmentation opportunities.

💡Result:

* Our regression analysis revealed that CGPA, GRE score, and TOEFL score are critical predictors of admission chances. Despite minor issues with residual normality and heteroscedasticity, both Linear Regression and regularized models demonstrated strong performance, capturing up to 82% of the variance in admission probabilities.
* Recommendations include enhancing feature diversity in applicant profiles beyond academic metrics and focusing on improving key predictors to optimize admission outcomes.

* By implementing these insights, Jamboree can enhance its predictive admissions capabilities, providing valuable guidance to applicants and improving success rates for Ivy League college admissions among Indian students.
