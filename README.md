# Body Fat Prediction using various various regression techniques

Objective- In this project, comparative analysis is conducted to evaluate the performance of various regression models in accurately predicting body fat percentage.

## Table of Contents
- [ProjectOverview](#ProjectOverview)
- [Dataset](#Dataset)
- [Regression Techniques](#RegressionTechniques)
- [Results](#Results)
- [Conclusion](#Conclusion)



### ProjectOverview
The primary goal of this project is to build predictive models for estimating body fat percentage and evaluate the performance of various regression techniques. This helps in identifying the most effective model for body fat prediction based on features like age, weight, height, and various body measurements.

### Dataset
The dataset used in this project contains various body measurements (e.g., age, weight, abdomen circumference) collected from individuals, along with their body fat percentage. This dataset is available here or can be sourced from publicly available health datasets.

Features:

Age
Weight
Height
Abdomen circumference
Hip circumference
Thigh circumference
Forearm circumference
Wrist circumference

Target:

Body Fat Percentage

### Regression Techniques
The following regression techniques were used to predict body fat percentage:

Linear Regression
Ridge Regression
Lasso Regression
Elastic Net Regression
Decision Tree Regression
Random Forest Regression
Gradient Boosting Regression

These models were chosen to provide a balance between simplicity, interpretability, and prediction power.

### Results

The best-performing model was found to be Random Forest Regressor, with the highest R² score and the lowest error rates, indicating strong predictive capability for this dataset.

### Conclusion
Through this comparative analysis, we found that Random Forest Regressor offers the best performance for predicting body fat percentage. This model's accuracy, combined with the robustness of the dataset, makes it an effective choice for health and fitness applications. Future work can explore additional models or feature engineering techniques to improve performance further.
