# credit-risk-classification

# Machine Learning Model Performance Report

## Overview of the Analysis

The purpose of this analysis is to evaluate the performance of a logistic regression model trained to predict loan statuses based on provided features. The dataset includes information about loans labeled as either healthy or high-risk. The goal is to assess how well the model can accurately classify loans into these categories.

## Results

- **Accuracy Score**: 0.99
- **Precision Score (weighted average)**: 0.99
- **Recall Score (weighted average)**: 0.99

Detailed breakdown:
- For healthy loans (class 0):
  - Precision: 1.00
  - Recall: 0.99
- For high-risk loans (class 1):
  - Precision: 0.85
  - Recall: 0.91

## Summary

The logistic regression model demonstrates outstanding performance overall with an accuracy, precision, and recall scores of approximately 0.99. It excels in correctly predicting healthy loans, achieving perfect precision and high recall. However, for high-risk loans, while the model maintains strong recall, precision is slightly lower, indicating a small number of healthy loans being misclassified as high-risk.

### Justification for Recommendation

Based on the analysis, I recommend the logistic regression model due to its high accuracy and balanced performance across both classes. The model's ability to accurately predict healthy loans is crucial for minimizing financial risk, while its respectable performance with high-risk loans provides valuable insights for risk assessment strategies.

### Considerations

While the model performs well, further enhancements could focus on improving precision for high-risk loans to reduce misclassifications. Additionally, ongoing monitoring and periodic model updates are recommended to adapt to evolving loan patterns and maintain optimal performance.

---

This report summarizes the evaluation of the logistic regression model's performance in predicting loan statuses.
