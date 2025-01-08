# Insights-and-Predictors-of-Academic-Success

This project explores the use of decision tree classification to analyze and predict student academic performance tiers (Low, Average, High) based on demographic, socioeconomic, and behavioral data. The goal is to understand key factors influencing academic outcomes and provide actionable insights for educators and policymakers.

## Overview

The project aims to identify factors that most influence student academic performance and build a predictive model to classify students into performance tiers. By leveraging decision tree analysis, the study sheds light on how various features impact performance and provides practical recommendations for targeted educational interventions.

## Dataset

The dataset includes the following features:
-**Math Score**: Numeric score representing the student's math performance.
-**Reading Score**: Numeric score representing the student's reading performance.
-**Writing Score**: Numeric score representing the student's writing performance.
-**Parental Level of Education**: Categorical feature indicating the highest level of education attained by the student's parent(s).
-**Lunch Type**: Indicates if the student is part of the free/reduced-price lunch program (proxy for socioeconomic status).
-**Test Preparation Course**: Indicates if the student completed a test preparation course (binary: completed/none).
-**Performance Category**: Target variable categorizing student performance into Low, Average, or High.

**Dataset Source**: [Student Performance Data](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)


## Features of the Project

1. **Data Cleaning**:
-Encoded categorical variables (e.g., gender, lunch type) into binary or one-hot representations for compatibility with the model.
-Verified data integrity by ensuring no missing or duplicate values.
2. **Exploratory Data Analysis (EDA)**:
-Visualized score distributions, highlighting correlations between features (e.g., math and reading scores).
-Used box plots and histograms to analyze trends and detect outliers.
-Explored the relationship between socioeconomic status (lunch type) and test scores.
3. **Feature Engineering**:
-Created an average composite score to represent overall performance.
4. **Decision Tree Modeling**:
-Built a decision tree classifier to predict performance categories.
-Visualized the decision tree structure to interpret feature importance and classification rules.
5. **Model Evaluation**:
-Achieved a test set accuracy of 95%, demonstrating strong predictive performance.
-Analyzed precision, recall, and F1-scores for each performance category to assess class-specific performance.
-Used a confusion matrix to identify areas of misclassification and refine model interpretation.
