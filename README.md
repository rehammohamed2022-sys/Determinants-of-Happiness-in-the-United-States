# Determinants of Happiness in the United States

## Categorical Data Analysis and Logistic Regression Project

### Overview

Understanding the factors that contribute to happiness is a central topic in social science, economics, and public policy. This project investigates the determinants of self-reported happiness in the United States using data from the World Values Survey (WVS) 2017.

The analysis applies categorical data analysis techniques, measures of association, contingency table methods, and logistic regression modeling to identify the most important predictors of happiness and evaluate their influence on subjective well-being.

---

## Research Objectives

* Identify the key social, economic, and demographic factors associated with happiness.
* Examine relationships between happiness and personal values such as religion, tolerance, and respect for authority.
* Assess the impact of economic satisfaction on subjective well-being.
* Evaluate demographic influences including age, gender, education, and region.
* Develop a logistic regression model to predict happiness status.
* Compare alternative model specifications using statistical model selection techniques.

---

## Dataset

The analysis uses data from the World Values Survey (WVS) 2017 – United States sample.

### Key Variables

#### Dependent Variable

* Happiness (Happy vs. Not Happy)

#### Social Values

* Importance of Religion
* Tolerance and Respect for Others
* Respect for Authority

#### Economic Factors

* Economic Satisfaction

#### Demographic Factors

* Gender
* Age Group
* Region (Urban/Rural)
* Education Level

---

## Statistical Methods

### Data Preparation

* Missing Value Handling
* Data Cleaning and Validation
* Recoding of Categorical Variables
* Binary and Ordinal Variable Construction

### Exploratory Data Analysis (EDA)

* Frequency Distributions
* Descriptive Statistics
* Distribution Assessment
* Data Visualization

### Bivariate Analysis

* Two-Way Contingency Tables
* Joint and Conditional Probabilities
* Chi-Square Tests of Independence
* Odds Ratios
* Mosaic Plots

### Measures of Association

* Cramer's V
* Contingency Coefficient
* Kendall's Tau-b
* Goodman–Kruskal Gamma
* Spearman Correlation

### Multivariate Analysis

#### Logistic Regression

Binary logistic regression was applied to model the probability of being happy using social, economic, and demographic predictors.

#### Model Selection

* Backward Elimination
* Akaike Information Criterion (AIC)
* Model Parsimony Assessment

### Model Evaluation

* Odds Ratio Interpretation
* Variance Inflation Factors (VIF)
* Multicollinearity Assessment
* Confusion Matrix
* Classification Accuracy
* Sensitivity and Specificity
* ROC Curve Analysis
* Area Under the Curve (AUC)
* Youden's Index Threshold Optimization

---

## Key Findings

### Economic Satisfaction

* Economic satisfaction was identified as the strongest predictor of happiness.
* Economically satisfied individuals were substantially more likely to report being happy than dissatisfied individuals.
* Measures of association confirmed a strong and consistent relationship between economic well-being and happiness.

### Social Values

* Religion was positively associated with happiness.
* Individuals who considered religion important reported higher levels of happiness.
* Respect for authority demonstrated a significant positive association with happiness.
* Tolerance showed only a weak relationship with happiness.

### Demographic Factors

* Education exhibited a modest but statistically significant positive effect on happiness.
* Age showed only limited association with happiness after controlling for other factors.
* Gender and region did not significantly influence happiness in the final model.

### Final Logistic Regression Model

The optimal model retained:

* Economic Satisfaction
* Religion
* Tolerance
* Respect for Authority
* Education

while excluding gender, age, and region through backward model selection based on AIC.

---

## Model Performance

The logistic regression model was evaluated using classification and discrimination metrics.

### Performance Results

* Accuracy: 87.6%
* Sensitivity: 99.9%
* Specificity: 1.9%
* AUC: 0.752

The model demonstrated strong ability to identify happy individuals and acceptable overall discrimination performance.

---

## Software

* R
* RStudio

---

## Repository Contents

* Final project report
* R scripts
* Data preprocessing code
* Contingency table analyses
* Odds ratio analyses
* Chi-square test results
* Logistic regression outputs
* Model diagnostics
* ROC and classification performance plots
* Visualizations and mosaic plots

---

## Skills Demonstrated

* Categorical Data Analysis
* Logistic Regression
* Odds Ratio Analysis
* Chi-Square Testing
* Measures of Association
* Model Selection Using AIC
* ROC Curve Analysis
* Classification Modeling
* Statistical Inference
* Data Cleaning and Transformation
* Exploratory Data Analysis
* Statistical Computing in R
* Social Science Analytics

---

## Keywords

Statistics, Categorical Data Analysis, Happiness Research, Subjective Well-Being, Logistic Regression, Odds Ratios, Chi-Square Tests, World Values Survey, Social Values, Economic Satisfaction, ROC Analysis, Predictive Modeling, Data Science, R Programming

---

## Author

Reham Mohamed

B.Sc. Statistics

Faculty of Economics and Political Science

Cairo University
