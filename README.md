# 🧠 Stroke Prediction Using Machine Learning:  Identifying Key RiskFactors
# 👩‍⚕️ Project Overview
Stroke is one of the leading causes of death and long-term disability worldwide, accounting for
approximately 11% of all deaths (World Health Organization). Early detection of stroke risk is essential for effective prevention and timely medical intervention.

This project investigates how machine learning can enhance early stroke risk prediction in real-world scenarios where data is limited and imbalanced. Using models such as Random Forest, K-Nearest neighbor, Decision Tree, and Logistic Regression, the study aims to classify stroke cases and identify key risk factors influencing stroke occurrence.

# 🎯 Goals
- Develop robust ML models that perform well on small, imbalanced datasets.
- Improve interpretability to aid clinical decision-making.
- Minimize false negatives (missed stroke cases).
- Evaluate whether complex models outperform a Logistic Regression baseline.

# 🗂️ Dataset
- Source: Kaggle – [Stroke Prediction Dataset](https://www.kaggle.com/datasets/imaadmahmood/stroke-risk-synthetic-2025)
- Size: 100 records
- Features: Age, gender, hypertension, heart disease, average glucose level, BMI, smoking status, work type, etc.
⚠️ Only 4% of patients had a stroke, making class imbalance a major challenge.

# 🧪 Methods
- Preprocessing: Null handling, one-hot encoding, robust scaling
- Modeling: Logistic Regression, K-Nearest Neighbor, Decision Tree, Random Forest
- Evaluation: Precision, Recall, F1-score, AUC–ROC, Confusion Matrix
- Feature Selection: health-related attributes (age, hypertension, heart_disease, avg_glucose_level, bmi) vs. lifestyle factors (smoking_status, work_type, Residence_type, ever_married, gender).
- Handling Class Imbalance: SMOTE (Synthetic Minority Oversampling Technique) was applied to balance classes, improving recall and model sensitivity toward stroke cases.
- Hyperparameter Tuning: Prioritize recall to reduce false negatives

# Results and Discussion

# Final Model


# 🚀 Deployment Considerations
- Can be integrated into hospital Electronic Health Record (EHR) systems
- Supports interoperability with wearable devices for continuous health monitoring


