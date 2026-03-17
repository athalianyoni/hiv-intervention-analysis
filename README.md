# HIV Intervention Analysis
A causal inference analysis evaluating the impact of integrated HIV intervention programs on viral load suppression among children in Mazowe District, Zimbabwe.

This project applies propensity score matching and logistic regression to estimate treatment effects using observational health data.

## Project Overview

This project evaluates the impact of integrated HIV intervention programs on viral load suppression among children living with HIV in Mazowe District, Zimbabwe.

The analysis combines descriptive statistics, causal inference techniques, and regression analysis to examine how intervention programs influence treatment outcomes.

---

## Research Questions

1. What is the geographical distribution of children receiving HIV intervention programs across health facilities in Mazowe District?

2. To what extent do integrated HIV intervention programs contribute to viral load suppression among children living with HIV?

3. How do demographic factors such as age, sex, and disclosure status relate to viral suppression outcomes?

---

## Methods

The following statistical methods were used:

- Exploratory Data Analysis
- Propensity Score Matching (Nearest Neighbour Matching)
- Covariate Balance Diagnostics
- Treatment Effect Estimation
- Logistic Regression

Propensity score matching was used to reduce selection bias when estimating the causal effect of integrated HIV interventions.

---

## Key Findings

- Viral suppression among children receiving interventions was approximately *79.4%*.
- Viral suppression among children not receiving interventions was approximately *68.4%*.
- The estimated treatment effect indicates that the intervention increased viral suppression by *approximately 11 percentage points*.

Logistic regression analysis showed that:

- *Age* was positively associated with viral suppression.
- *Disclosure status* was significantly associated with viral suppression outcomes.
- *Sex* was not a significant predictor of viral suppression.

---

## Tools Used

- Python
- Pandas
- Scikit-learn
- Statsmodels
- Matplotlib

---

## Author

Athalia Nyoni  
BSc Operations Research and Statistics  
National University of Science and Technology (Zimbabwe)
