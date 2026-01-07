## STROKESENSE-ML BASED STROKE PREDICTION
The project aims to predict stroke risk using a stacked ensemble of machine learning models combined with fuzzy logic. Logistic Regression is used as a meta-learner to enhance prediction accuracy, interpretability, and decision reliability in healthcare applications.

## About
This project focuses on stroke risk prediction using machine learning and fuzzy logic.Multiple base models such as Random Forest, XGBoost, LightGBM, and CatBoost are trained to capture different risk patterns.A stacked ensemble approach is used, where Logistic Regression acts as a meta-learner to combine base model predictions.Fuzzy logic and medical rules are integrated to improve clinical interpretability.The system is deployed using a Flask REST API to provide real-time stroke risk assessment.

## Features

1. Predicts stroke risk using medical and lifestyle data.

2. Uses multiple machine learning models to capture different risk patterns.

3. Applies stacked ensemble learning for improved prediction accuracy.

4. Uses Logistic Regression as a meta-learner to combine model outputs.

5. Integrates fuzzy logic to handle uncertainty and borderline cases.

6. Balances imbalanced data using SMOTE for fair predictions.

7. Provides explainable results using SHAP feature importance.

8.Deploys the system through a Flask REST API for real-time prediction.

## Requirements
1. Operating System: Requires a 64-bit operating system such as Windows 10/11 or Ubuntu for smooth execution of machine learning workflows.

2. Development Environment: Python 3.8 or later is required for implementing machine learning models, fuzzy logic, and backend services.

3. Machine Learning Frameworks: Scikit-learn for traditional machine learning models, XGBoost, LightGBM, and CatBoost for ensemble learning.

4. Backend Framework: Flask is used to develop RESTful APIs for handling model inference and communication with the frontend.

5. Data Processing & Explainability Libraries: Pandas and NumPy for data handling, SHAP for explainable AI and model interpretation.

6. Imbalance Handling & Utilities: Imbalanced-learn (SMOTE) for class balancing and Joblib for model serialization and loading.

7. Frontend Technologies: HTML, CSS, JavaScript, and React (optional) for building a user-friendly interface.

8. IDE & Version Control: Visual Studio Code (VS Code) as the IDE and Git for version control and collaborative development.

## System Architecture

<img width="1044" height="832" alt="image" src="https://github.com/user-attachments/assets/88eb69c1-d763-44f1-809a-84cff1640a0c" />


## Output

<img width="1918" height="915" alt="image" src="https://github.com/user-attachments/assets/0328c50f-d46f-495c-80b3-798c758ce36f" />


<img width="1919" height="904" alt="image" src="https://github.com/user-attachments/assets/676cfca0-982a-4945-997c-885061591cdd" />


<img width="1919" height="912" alt="image" src="https://github.com/user-attachments/assets/f168ff33-d95c-413e-ab7a-24bfce0aadf5" />



Detection Accuracy: 95%

<img width="786" height="230" alt="image" src="https://github.com/user-attachments/assets/6329fbb7-c858-457c-b4a8-a1f7ba499637" />




## Results and Impact
The Stroke Risk Prediction System improves early identification of individuals at risk of stroke, enabling timely preventive care and lifestyle interventions. The integration of stacked ensemble learning, fuzzy logic, and explainable AI enhances prediction accuracy, reliability, and clinical interpretability. The project demonstrates the potential of intelligent decision-support systems to assist healthcare professionals and individuals in proactive health monitoring.This project serves as a foundation for future developments in assistive technologies and contributes to creating a more inclusive and accessible digital environment.

## Articles published / References

S. A. Dey, A. K. Dash, P. K. Mishra, and R. K. Nayak,
“Stroke Risk Prediction Using Machine Learning and Ensemble Techniques”,
International Journal of Medical Informatics, vol. 176, pp. 105–118, Mar. 2023.

M. Mitu, S. M. M. Hasan, M. P. Uddin, M. A. Mamun, V. Rajinikanth, and S. Kadry,
“A Stroke Prediction Framework Using Explainable Ensemble Learning”,
Computer Methods in Biomechanics and Biomedical Engineering, vol. 28, no. 4, Apr. 2025.

T. Fang and J. Deng,
“An Interpretable Prediction Model for Stroke Based on XGBoost and SHAP”,
Journal of Clinical and Nursing Research, vol. 9, no. 2, Feb. 2024.

S. Lundberg and S. I. Lee,
“A Unified Approach to Interpreting Model Predictions”,
Advances in Neural Information Processing Systems (NeurIPS), vol. 30, pp. 4765–4774, 2017.

N. V. Chawla, K. W. Bowyer, L. O. Hall, and W. P. Kegelmeyer,
“SMOTE: Synthetic Minority Over-sampling Technique”,
Journal of Artificial Intelligence Research, vol. 16, pp. 321–357, Jun. 2002.



