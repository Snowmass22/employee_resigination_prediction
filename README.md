Employee Resignation Prediction 🏃‍♂️💼
This project focuses on predicting employee turnover using machine learning. By analyzing workplace factors, the model identifies employees who are likely to resign, allowing organizations to take proactive retention measures.

📊 Project Overview
The model performs binary classification to predict if an employee will stay (0) or leave (1). I implemented and compared three variations of Logistic Regression to find the most robust predictor
Baseline Logistic Regression
Lasso (L1 Regularization): Used for feature selection.
Ridge (L2 Regularization): Used to prevent overfitting.

🛠️ Tech StackLanguage: 
PythonPlatform: JupyterLabLibraries: * pandas & numpy (Data Processing)scikit-learn (Modeling & Metrics)matplotlib & seaborn (Analysis)

📈 Model Performance
Based on the current evaluation, the Lasso model is slightly outperforming the others:ModelAccuracyF1-Score (Class 1)Baseline85.9%0.84Lasso87.0%0.86Ridge85.9%
