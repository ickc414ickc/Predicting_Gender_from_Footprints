# Predicting Gender from Footprints (Kaggle Competition)

### [View the Full Project Report (PDF)](Deep_Learning_report.pdf) | [View the Jupyter Notebook](data_mining.ipynb)

---

## 1. Project Goal

The goal of this project, part of a Kaggle competition, was to develop a machine learning model to predict an individual's gender based on 18 key landmarks from their footprint. The model was required to achieve at least 90% accuracy, simulating a real-world application for a police department to narrow down suspects from crime scene evidence.

**Final Result:** The developed model achieved a **final private score of 0.9067**, successfully exceeding the target and placing highly in the competition.

---

## 2. Skills & Tools Used

*   **Languages & Libraries:** Python, Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn, SHAP
*   **Machine Learning:** Predictive Modeling, Feature Engineering, Hyperparameter Tuning (Bayesian Optimization), Model Evaluation, Explainable AI (XAI)
*   **Data Processing:** Outlier Detection, Missing Value Imputation (KNN Imputer), SMOTE (for class imbalance)

---

## 3. Analytical Process

The project followed a structured machine learning workflow:

1.  **Exploratory Data Analysis (EDA):** Analyzed the raw landmark data, identified outliers, and visualized the initial class imbalance.
2.  **Advanced Feature Engineering:** This was the key to the model's success. I engineered novel biomechanical features based on podiatric research (e.g., foot length, width, and the "HB Index"). These engineered features proved to be the most impactful predictors.
3.  **Systematic Modeling:** I tested and evaluated multiple classification models (e.g., Logistic Regression, SVM, Random Forest, XGBoost) and preprocessing techniques to find the optimal combination.
4.  **Hyperparameter Tuning & Optimization:** Used Bayesian Optimization to fine-tune the final XGBoost model, systematically searching for the best parameters to maximize performance.
5.  **Model Explainability:** Utilized SHAP (SHapley Additive exPlanations) to interpret the final model, providing clear, visual insights into which features were most important in its predictions and confirming the value of the engineered features.

---
