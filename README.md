# Project description
This project involved developing a robust machine-learning pipeline to predict the likelihood of diabetes in patients based on medical diagnostic features. Utilizing the Pima Indians Diabetes dataset, the project focused on data preprocessing, exploratory data analysis, multiple classification models, and performance comparison to determine the most effective predictive algorithm.

# Key Highlights:
📊 Exploratory Data Analysis (EDA):
Analyzed data distribution, correlations, and outliers using heatmaps and boxplots.
Identified and addressed zero or missing values in key medical attributes like Glucose and BMI.

⚙️ Preprocessing:
Scaled numerical features using StandardScaler.
Handled class imbalance with techniques like SMOTE (Synthetic Minority Oversampling Technique).
Split data into training and test sets (80/20).

🤖 Model Development:
Implemented and evaluated multiple classification algorithms:
Logistic Regression
K-Nearest Neighbors (KNN)

📈 Model Evaluation:
Assessed each model using Accuracy, Precision, Recall, F1-Score, ROC-AUC Score, and Confusion Matrix.

🔍 Feature Importance:
Interpreted feature significance using coefficients and tree-based importance metrics.
Visualized the impact of features like Glucose, BMI, and Age on the model predictions.

# Outcome
Achieved an accuracy of over 76.04% with KNN and 5fold CV as the best-performing model. The project showcased the ability to build and compare multiple models, perform feature engineering, and make data-driven decisions in a healthcare context.
