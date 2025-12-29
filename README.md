# Diabetes Progression Modeling

# Overview
This project builds and evaluates regression models to analyze factors associated with diabetes disease progression. Using a standardized diabetes dataset, the notebook explores relationships between clinical measurements and a quantitative measure of disease progression, with the goal of developing predictive models and interpreting feature effects.

The analysis emphasizes statistical modeling concepts, feature relationships, and model evaluation rather than black-box prediction.

# Objectives
- Explore the diabetes dataset and understand variable relationships
- Apply data preprocessing and feature selection techniques
- Build regression models to predict disease progression
- Interpret model coefficients and assess statistical significance
- Evaluate model performance using standard regression metrics

#  Dependencies
This project uses the following Python libraries:
```
pandas
numpy
matplotlib
seaborn
scikit-learn
math
```
Install required packages with:
```
pip install pandas numpy matplotlib seaborn scikit-learn
```

# Model Evaluation
Models are evaluated using:
- R² (Coefficient of Determination)
- RMSE (Root Mean Squared Error)

These metrics are used to compare models and assess generalization performance.

# Results & Insights

Key insights from the analysis include:
- Certain physiological variables (e.g., BMI) show strong associations with disease progression
- Multivariate models outperform single-feature regressions
- Model interpretability provides clinical insight into contributing risk factors
