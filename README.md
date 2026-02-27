# Power System Load Type Classification

## Overview

This project predicts power system **Load_Type** (Light, Medium, Maximum) using historical energy consumption data. A time-based split was used to avoid data leakage.

## Models Used

* Logistic Regression
* Support Vector Machine (SVM)
* Random Forest

## Results

* Logistic Regression: 59.9%
* SVM: 70.0%
* Random Forest: 92.98%

Random Forest achieved the best performance, effectively capturing non-linear patterns and temporal relationships.

<img width="1395" height="652" alt="image" src="https://github.com/user-attachments/assets/2d40fd3b-f067-423b-aa06-fc933984a3a4" />

## Conclusion

Tree-based ensemble methods are well-suited for load type classification in this dataset.
