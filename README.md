🔬 **Predictive Analysis of Lung Cancer using Machine Learning**

This project aims to predict risk of lung cancer in patients using machine learning techniques.

------
📊 **Dataset**

Source: Kaggle (Lung Cancer Prediction)

Features include: age, gender, symptoms like smoking, air pollution, fatigue, and more.

Target: Whether the patient is at high risk of lung cancer.

-------
🧹 **Preprocessing**

Handled missing values, duplicates, and outliers

Removed highly correlated features

Checked skewness (none exceeded ±1)

Applied StandardScaler for normalization

Encoded categorical variables with LabelEncoder

--------
🤖 **Models Used**

Logistic Regression

Multi-layer Perceptron Classifier (MLPC)

Support Vector Machine (SVM)


**All models achieved:**

Accuracy: 1.0

Precision/Recall/Specificity: 1.0


(SVM used 10-fold cross-validation; others used hold-out with test size = 0.2)
------
📈 **Metrics Evaluated**

Accuracy Score

Confusion Matrix

Classification Report

ROC Curve & AUC Score


✅ Conclusion

All three models showed perfect performance, highlighting the power of machine learning in early lung cancer risk prediction. Future work can explore larger and more diverse datasets to improve generalizability.


