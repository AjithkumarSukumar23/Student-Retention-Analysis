# Student Retention Prediction

## Overview

This project focuses on predicting student retention in educational institutions using machine learning. The goal is to identify students at risk of dropping out and enable timely interventions to improve graduation rates and ensure academic success.

## Business Question

In today's educational landscape, student retention and success are of utmost importance for educational institutions. Identifying students who are at risk of dropping out and implementing timely interventions can significantly contribute to improving graduation rates and ensuring academic success.

**Key Question:**
What are the factors that may affect student retention or dropout rates in academic institutions?

## Methodology

The project aims to develop a predictive model using machine learning classification algorithms to identify students likely to drop out. By leveraging data on student demographics, academic performance, socio-economic factors, and other relevant variables, we aim to build a robust predictive model.

**Steps:**
1. Data Preparation
2. Exploratory Data Analysis (EDA)
3. Feature Selection
4. Model Training and Evaluation

## Dataset

The dataset encompasses a wide range of information about students in higher education institutions, such as:
- Demographics
- Socioeconomic backgrounds
- Academic performance

**Dataset Size:**
- 4,424 observations
- 35 features

## Exploratory Analysis

### Key Findings:
- **Age:** Majority of students are in their late teens to early 20s. Dropout rate increases from mid-20s to early 30s.
- **Courses:** Management courses with evening attendance had the highest number of dropouts.
- **Gender:** Higher dropout rates among male students (45.1%) compared to female students (25.1%).
- **Attendance:** Nighttime students have a 12.1% higher dropout rate compared to daytime students.
- **Marital Status:** Legally separated students have the highest dropout rate (66.7%), followed by married students (47.2%).
- **Financial Status:** Students in debt and those with unpaid tuition have higher dropout rates (62% and 86.6% respectively).

## Models Used

We evaluated several machine learning models to predict student retention:
1. Logistic Regression
2. Decision Trees
3. Support Vector Machines (SVM)
4. Random Forest
5. K-Nearest Neighbors (KNN)

### Results

The choice of the best model depends on the dataset's unique needs and priorities. In this context, the models were competitive, with the decision leaning toward the Support Vector Classifier for its adaptability to non-linear data and strong accuracy. However, further assessment, such as cross-validation and considering the implications of false positives and false negatives, would provide a more comprehensive basis for selecting the ideal model for the specific application.

## Conclusion

By predicting the likelihood of students dropping out, educational institutions can provide targeted support and resources to at-risk students, thereby improving retention rates and fostering academic success.

