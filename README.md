# Predicting Risk of Diabetes

Background: 

Healthcare providers face challenges in accurately identifying individuals at high risk of developing diabetes. Delayed or missed diagnoses can lead to preventable complications and inefficient allocation of medical resources. As someone with a family history of diabetes, this project is especially meaningful to me, and it aims to improve early detection of diabetes by predicting an individual’s risk based on clinical and lifestyle data. In addition, the model highlights the features that most significantly contribute to diabetes risk, providing actionable insights for preventive care and patient management.

Approach:
* Collected and preprocessed clinical and lifestyle data (e.g., glucose level, BMI, blood pressure, insulin, family history).
* Performed feature engineering (normalization, categorical encoding, interaction terms)
* Applied Logistic Regression and Linear Discriminant Analysis (LDA) models to predict diabetes risk.and cross-validation for model robustness.

Key Features Considered:
* Clinical metrics: Glucose, BMI, blood pressure, insulin levels.
* Lifestyle/health indicators: Physical activity proxy features, pregnancies, skin thickness.

Results:
* Achieved 0.74 AUC and 89.5% specificity, ensuring fewer false positives in diagnosis.
* Identified high glucose, BMI, and insulin resistance as top predictive factors for diabetes risk.

Impact:
* Provides a decision-support tool for clinicians to target preventive care more effectively.
* Supports resource allocation by highlighting patients most likely to benefit from early intervention.
