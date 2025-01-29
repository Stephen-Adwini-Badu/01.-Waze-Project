# Waze Project

## Project Overview
This notebook focuses on exploring and analyzing Waze user data to uncover insights about user behavior, identify key patterns in app usage, and develop predictive models for user retention and engagement.

## Objectives
1. **Conduct a T-Test** to analyze the difference in the average number of rides between Android and iPhone users.
2. **Build a Logistic Regression Model** to predict user churn.
3. **Develop Classification Models** to differentiate between claims and opinions within user comments and video reviews.

---

## Methodology
### 1. Data Exploration & Preprocessing
- Dataset loading and initial inspection using Pandas.
- Handling missing data by dropping incomplete rows.
- Reviewing dataset characteristics such as size, types, and distributions.

### 2. Data Visualization
- Visualization of key variables (e.g., sessions, drives, app usage duration).
- Generation of box plots and histograms to explore data distribution and identify trends.
- Comparative bar plots for device type usage and user retention rates.

### 3. Statistical Testing
- **Hypothesis Testing:** 
  - Null Hypothesis: No difference in average rides between Android and iPhone users.
  - Alternative Hypothesis: A significant difference exists.
- Execution of T-tests to validate hypotheses.

### 4. Machine Learning Models
- Development of predictive models using:

#### 4.1 Logistic Regression For Churn Prediction.
![1 1](https://github.com/user-attachments/assets/4d606085-5911-49be-b8c1-366572d824a2)


#### 4.2.1 Classification Models Evaluation Using Confusion Matrices.
![1 1](https://github.com/user-attachments/assets/9fb2e01f-57cc-41cd-948d-9f688353f29c)

#### 4.2.2 Classification Models Evaluation Using ROC and Calibration Curves
![1 2](https://github.com/user-attachments/assets/c485fae5-f79e-4fe3-8b24-e401349e8ae1)

#### 4.3 Feature Importance Of Classifiaction Models
![Image](https://github.com/user-attachments/assets/25ac6bdf-52dd-4de9-90d5-3ea141bcf333)
