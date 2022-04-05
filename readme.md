# Customer Analytics

Analyze customer churn data and provide business strategy to reduce customer churn

### Prepare Environment

```
pip install -r requirements.txt
```

### Deliverables

1. `Analytics.ipynb` provides data analysis to understand the dataset and its feature. It also provides comparison of ML models performance on the dataset. The ML models used are Gaussian, kNN, multi layer perceptron, and Random Forest.

2. `Data-Analysis (Problem 1-6).xlsx` analyzes the first 6 problems using Ms Excel.

3. `Telco Customer Churn Analytics.pdf` presents the results and insights from the experiments and recommends business strategy.

### Model Performance

| ML Model    | Accuracy Train | Accuracy Test | F1 Train | F1 Test |
| --- | --- | --- | --- | --- |
| Gaussian    | 0.77 | 0.77 | 0.78 | 0.78 |
| kNN         | 0.83 | 0.76 | 0.83 | 0.78 |
| MLP         | 0.75 | 0.75 | 0.73 | 0.73 |
| **RandomForest** | **0.85** | **0.84** | **0.85** | **0.85** |
