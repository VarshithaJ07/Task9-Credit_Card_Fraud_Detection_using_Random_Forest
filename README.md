# Task9-Credit_Card_Fraud_Detection_using_Random_Forest





## Overview

This task implements a **Credit Card Fraud Detection system** using **Machine Learning**.
A **Random Forest classifier** is trained and compared against a **baseline Logistic Regression model** to detect fraudulent transactions from highly imbalanced data.



##  Dataset

* **Source:** Kaggle – Credit Card Fraud Dataset
* **Target column:** `Class`

  * `0` → Non-Fraud
  * `1` → Fraud



## Models Used

* **Baseline Model:** Logistic Regression
* **Final Model:** Random Forest Classifier (Ensemble Learning)



##  Evaluation Metrics

* Precision
* Recall
* F1-Score

(Accuracy is not relied upon due to class imbalance.)



## Model Saving

The trained Random Forest model is saved using **joblib** as:

```
credit_card_fraud_rf_model.pkl
```



## Conclusion

Random Forest outperformed Logistic Regression by achieving higher recall and F1-score for fraud detection, making it more suitable for this imbalanced dataset.



