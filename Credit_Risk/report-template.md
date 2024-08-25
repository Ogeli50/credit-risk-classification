# Module 12 Report Template

## Overview of the Analysis

The analysis aimed to develop machine learning models to predict loan risk. We aimed to build a model that accurately predicts healthy (0) or high-risk (1) loans. The data showed a significant imbalance, with more healthy loans (0) than high-risk loans (1).
The machine learning process included the following stages:
1. Data Preprocessing: We meticulously cleaned and prepared the dataset for modeling, including handling missing values, encoding categorical variables, and splitting the data into training and testing sets. This thorough process laid a solid foundation for our model's development.
2. Model Selection: We carefully chose the logistic regression model because of its suitability for binary classification tasks. This decision was based on its proven track record in similar analyses, which reassured us that it was appropriate for our task.
3. Model Training: Fitting the logistic regression model to the training data to learn the underlying patterns.
4. Model Evaluation: Assessing the model's performance using accuracy, precision, recall, and F1-score metrics to ensure it generalizes well to unseen data.


## Results

Machine Learning Model 1: Logistic Regression
- Accuracy: The model achieved an accuracy score of 0.99, indicating that 99% of the predictions were correct.
- Precision:
  For healthy loans (0): Precision was 1.00, meaning all predictions made for healthy loans were correct.
  For high-risk loans (1): Precision was 0.85, indicating that 85% of the predictions made for high-risk loans were correct.
- Recall:
  For healthy loans (0): Recall was 0.99, meaning the model correctly identified 99% of healthy loans.
  For high-risk loans (1): Recall was 0.91, meaning the model correctly identified 91% of high-risk loans.
- F1-Score:
  For healthy loans (0): F1-score was 1.00, showing perfect precision and recall.
  For high-risk loans (1), the F1 Score was 0.88, indicating a good balance between precision and recall but not perfection.


## Summary

The logistic regression model performed exceptionally well in predicting healthy and high-risk loans. The accuracy score of 0.99 suggests that the model is highly reliable overall, instilling confidence in its performance. However, when focusing on high-risk loans, the precision and recall metrics show that while the model is good, it could be more flawless.
Recommendation:
Best Performing Model: The logistic regression model performed best in this analysis, mainly predicting healthy loans with almost perfect accuracy, precision, recall, and F1-score. However, while the model is strong for high-risk loans, there is room for improvement.

Performance Dependence: The model's performance depends on the problem we are trying to solve. If predicting high-risk loans is more critical (e.g., to minimize financial losses), the model might need further refinement to reduce false negatives (high-risk loans predicted as healthy). In such cases, adjusting the model to prioritize recall for high-risk loans might be advisable.
Further analysis and model tuning may be necessary if no model meets the required performance standards, particularly in accurately identifying high-risk loans. This could involve exploring more complex algorithms, addressing data imbalance, or engineering additional features to improve model performance.