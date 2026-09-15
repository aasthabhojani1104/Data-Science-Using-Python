## Machine Learning Suitability

The EV Battery Failure Prediction dataset is suitable for Machine Learning, particularly for a **binary classification problem**.

- **Records:** 20,000
- **Original Features:** 70
- **Target Variable:** `battery_failure`
  - `0` → No Failure
  - `1` → Battery Failure
- **Problem Type:** Binary Classification
- **Categorical Features:** Prepared using One-Hot Encoding
- **Numerical Features:** Prepared using StandardScaler and MinMaxScaler
- **Preprocessing:** Missing values handled and duplicate records checked
- **Recommended Models:** Logistic Regression, Decision Tree, and Random Forest
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score, Confusion Matrix, and ROC-AUC

The dataset can be used to build and evaluate Machine Learning models for predicting the likelihood of EV battery failure.
