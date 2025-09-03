🧠 Introvert vs Extrovert Personality Prediction

This project predicts whether a person is an Introvert or Extrovert based on survey responses from a Kaggle dataset. The task is framed as a binary classification problem.

🔹 Workflow

Designed a complete Machine Learning pipeline using scikit-learn for end-to-end automation.

![PipeLine](/pipeline.png)

Applied a ColumnTransformer to preprocess numerical (scaling) and categorical (encoding) features.

Implemented and compared multiple models:

Decision Tree Classifier

Random Forest Classifier

XGBoost Classifier

Performed hyperparameter tuning with GridSearchCV to select the best model for each algorithm.

Evaluated model performance using accuracy scores provided by Kaggle along with confusion matrix and classification metrics.

🔹 Results

Kaggle evaluation provided the final accuracy scores, highlighting the strong performance of ensemble methods (XGBoost and Random Forest) compared to the baseline Decision Tree.
![Accuracy_Score](/acc_score_kaggle.png)


