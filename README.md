# Game_Addiction_Risk_Prediction
End-to-end machine learning project to predict game addiction risk using data analysis, feature engineering, and predictive modeling techniques.


This project builds an end-to-end Machine Learning pipeline to predict gaming addiction risk levels using behavioral and lifestyle features.

The workflow follows industry best practices, starting from exploratory data analysis and feature selection to model training, evaluation, and deployment-ready pipeline creation. From an initial set of 30 features, the most impactful predictors were selected based on feature importance analysis to improve model performance and reduce noise.

The final solution leverages a robust preprocessing pipeline using ColumnTransformer, handling numerical scaling, ordinal encoding, and one-hot encoding, combined with a Random Forest classifier. The entire workflow is encapsulated in a single reusable pipeline, ensuring consistency and preventing data leakage.

Key highlights:

Modular project structure using a directory for clean and maintainable code
Proper train-test splitting with stratification
Feature engineering and selection based on importance
End-to-end Pipeline integrating preprocessing and model
Model persistence using joblib for deployment readiness
Evaluation using cross-validation and classification metrics

This project is designed with scalability and production readiness in mind, making it easy to integrate into APIs or real-world applications.
