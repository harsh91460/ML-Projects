# Diabetes Prediction ML Project

This project is a **Diabetes Prediction System** built using Python and Machine Learning. It predicts whether a person is diabetic based on medical features like glucose level, BMI, age, insulin, and more. The project is implemented in **Google Colab**.

---

## Dataset
The project uses the **Pima Indians Diabetes Dataset** which contains 768 patient records with 8 medical features and an outcome label (0 = Non-diabetic, 1 = Diabetic). The dataset has 500 non-diabetic and 268 diabetic samples.

---

## Approach
1. **Data Preprocessing:** Features are standardized to improve model performance.
2. **Model Training:** A **Support Vector Machine (SVM)** classifier is trained on the dataset.
3. **Evaluation:** The model achieves ~78% accuracy on training data and ~77% on test data.
4. **Prediction:** The trained model can predict diabetes for new patient data.

---

## Features Used
- Pregnancies  
- Glucose  
- Blood Pressure  
- Skin Thickness  
- Insulin  
- BMI  
- Diabetes Pedigree Function  
- Age  

---

## Outcome
- **0:** Not Diabetic  
- **1:** Diabetic  

The model can be used to predict the diabetes status of a person by inputting these features.

---

## Notes
- Implemented in Python using `pandas`, `numpy`, and `scikit-learn`.  
- Can be run directly in Google Colab.  
- Performance can be improved with feature engineering and hyperparameter tuning.
