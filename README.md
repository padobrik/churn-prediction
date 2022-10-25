# churn-prediction
Experiments with logistic regression and gradient boosting to predict users' churn.
Actual ROC-AUC score is 0.85525 made with CatBoost (Top 2% solutions).

## Task description
The problem is defined by Deep Learning School and posted on Kaggle:
``` https://www.kaggle.com/competitions/advanced-dls-spring-2021 ```

## Requirements
Libs: ```CatBoost```, ```XGBoost```, ```sklearn```, ```pandas```, ```numpy```
Environment: ```Google Colab``` is recommended

## Results
All the fits were implemented with GridSearchCV using ```CV``` = 10. Performance measurement is defined by ```ROC-AUC``` curve. A little analysis also implemented.

**LogisticRegression**: ROC-AUC = 0.84601
**XGBoost**: ROC-AUC = 0.85061
**CatBoost**: ROC-AUC = 0.85525
