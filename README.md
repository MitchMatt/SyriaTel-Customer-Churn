# SyriaTel Customer Churn Analysis


## Overview
- **Company:** SyriaTel, a telecommunications company in Syria
- **Issue:** Customers discontinuing service
- **Objective:** Identify features indicating potential customer churn

## Problem Statement
- **Challenge:** Predicting and understanding customer churn to maintain stability and income
- **Goal:** Prevent customer churn and enhance customer satisfaction

## Main Objective
- **Classification Modeling:** Analyze customer churn data to identify contributing factors

## Subjective Objectives
1. **Explore Data:**
   - Understand relationships between variables and churn
2. **Create Classification Model:**
   - Build models like Logistic Regression, Random Forest
3. **Analyze Feature Importance:**
   - Identify influential factors in churn prediction
4. **Assess Model Performance:**
   - Evaluate accuracy, precision, recall, and confusion matrix
5. **Offer Recommendations:**
   - Provide actionable insights based on model findings

## Data Understanding
- **Columns:** state, account length, area code, phone number, international plan, voice mail plan, number vmail messages, total day minutes, total day calls, total day charge, total eve minutes, total eve calls, total eve charge, total night minutes, total night calls, total night charge, total intl minutes, total intl calls, total intl charge, customer service calls, churn

## Baseline Model
- **Accuracy:** 87.03%
- **Interpretation:** Reasonable accuracy, correctly predicting 87 out of 100 instances

## Random Forest Classifier
- **Accuracy:** 89.40%
- **Best Parameters:** max_depth: None, min_samples_split: 2, n_estimators: 200
- **Improved Accuracy:** 89.80%

## XGBoost Classifier
- **Accuracy:** 91.24%
- **Interpretation:** Highest accuracy, correctly predicting 91 out of 100 instances

## Conclusions
- **Model Performance:** 
  - XGBoost: 91%, Random Forest: 89%, Logistic Regression: 87%
- **Prediction of Churn:** 
  - Models provide insights to identify high-risk churn customers
- **Key Predictors:**
  - 'Customer service calls,' 'international plan,' 'total day minutes'

## Investigate International Plan Churn Rate
- **Observation:** High churn rate among international plan holders
- **Action:** Implement personalized retention strategies

## Recommendations
1. **Targeted Retention Strategies:**
   - Implement targeted strategies for high-risk churners
2. **Improved Customer Service:**
   - Enhance service quality to reduce churn
3. **Continuous Monitoring:**
   - Update models with new data for reliability
4. **Explore Strategies for International Plans:**
   - Tailored retention strategies for international plan holders

## Questions and Discussion
- **Open Floor:** Invite questions and feedback from the audience
