[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=21487787)
# Predicting Post-Graduation Earnings Using Tuition, Institutional Metrics, and Student Demographics

INFO 523 - Final Project
Author: Ava Lasater
Institution: College of Information Science, University of Arizona

#### Project Overview
This project examines how tuition, financial aid indicators, and institutional characteristics relate to student retention and post-graduation earnings using the U.S. Department of Education’s College Scorecard dataset. The analysis focuses on bachelor’s-degree-granting institutions and investigates how structural, financial, and demographic factors contribute to long-term student outcomes.

The study incorporates exploratory data analysis, linear regression, Ridge regression, logistic regression, random forest classification, feature selection techniques, and permutation importance. The goal is to describe broad institutional patterns and provide insight into which variables are most strongly associated with institutional student success.

#### Research Questions
How do tuition and financial burden relate to student retention and post-graduation earnings?

Which institutional characteristics (e.g., region, locale, control, enrollment size) most strongly predict earnings outcomes?

Can institutional features be used to classify colleges into high-earning and low-earning groups?

Which features provide the strongest predictive signal across linear and machine-learning models?

#### Methods Used
##### Preprocessing
- Combined split CSV filed due to GitHub upload limits
- Filtered to primarily bachelor's degree-granting schools
- Removed columns with high missingness
- Scaled and log-transformed select variables
- One-hot encoded region, locale, and control categories

##### EDA
- Historgrams of all numeric variables
- Correlation heatmap
- Distribution checks of region, state, locale, and control
- Identification of skewed variables and outliers

##### Regression Models
- Multiple Linear Regression
- Ridge Regression
- Diagnoistic plots

##### Classification Models
- Feature selection using SelectKBest
- Random forest feature importance
- Permutation importance (self-taught extension)
- Logistic Regression
- Random Forest Classifier
- Evaluation plots (self-taught extension)

#### Key Findings
- Tuition has a positive but moderate association with long-term earnings.
- Retention and completion rates are among the strongest predictors of earnings.
- Pell Grant percentage is strongly negatively associated with earnings, reflecting socioeconomic patterns.
- Classification models achieve 77–82% accuracy.
- Institution size (UGDS), retention, completion, tuition, and socioeconomic mix provide the strongest predictive signal.
- Locale categories and school control type add minimal predictive value once other variables are included.

#### Data Source
U.S. Department of Education, Office of Federal Student Aid. College Scorecard Data. https://collegescorecard.ed.gov/data/

#### Disclosure:
Derived from the original data viz course by Mine Çetinkaya-Rundel @ Duke University
