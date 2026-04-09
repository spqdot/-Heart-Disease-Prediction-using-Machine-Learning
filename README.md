# -Heart-Disease-Prediction-using-Machine-Learning

📌 Project Overview

This project focuses on predicting the presence of heart disease in patients using multiple machine learning algorithms. The goal is to compare different models and identify the best-performing one based on accuracy.

📊 Tasks Performed
1. Data Analysis
Imported the dataset
Generated descriptive statistics (mean, min, max, quartiles)
Checked correlations between features
2. Data Visualization
Visualized distribution of patients with and without heart disease
Analyzed age vs disease relationship
Created a correlation heatmap for all features
🤖 Models Implemented
1. Logistic Regression
Data split: 70% training, 30% testing
Model trained and evaluated using:
Confusion Matrix
Accuracy Score

Accuracy: 0.8132

2. Decision Tree
Built and trained a Decision Tree model
Visualized using Graphviz
Evaluated using confusion matrix and accuracy

Accuracy: 0.8242

3. Random Forest
Built Random Forest model with different n_estimators
Evaluated performance for multiple values:
n_estimators	Accuracy (%)
50	81.31
100	83.51
200	84.61
300	84.61
400	85.71
500	85.71
🏆 Best Model

The Random Forest model achieved the highest accuracy of 85.71%, making it the best-performing model for this dataset.

📌 Reason:
Combines multiple decision trees (ensemble learning)
Reduces overfitting
Handles complex feature relationships effectively
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib / Seaborn
Scikit-learn
Graphviz
📈 Conclusion

Random Forest outperformed Logistic Regression and Decision Tree in this project. However, model performance depends on dataset characteristics and proper tuning.

🚀 Future Improvements
Hyperparameter tuning (GridSearchCV)
Feature engineering
Try advanced models (XGBoost, LightGBM)
Cross-validation for better evaluation
