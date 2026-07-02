#  Heart Disease Prediction using Decision Tree and Random Forest

##  Project Overview

This project predicts whether a patient has heart disease or not using Machine Learning. Two classification algorithms, **Decision Tree** and **Random Forest**, are used to train and evaluate the model. The performance of both models is compared based on accuracy, and the most important features affecting heart disease are identified using Feature Importance.

---

##  Project Objective

- Predict whether a patient has heart disease.
- Compare the performance of Decision Tree and Random Forest.
- Identify the most important features responsible for heart disease prediction.

---

##  Dataset

- **Dataset Name:** UCI Heart Disease Dataset
- **Format:** CSV
- **Target Column:** `target`
  - `0` = No Heart Disease
  - `1` = Heart Disease

### Features Used

- Age
- Sex
- Chest Pain Type (cp)
- Resting Blood Pressure (trestbps)
- Cholesterol (chol)
- Fasting Blood Sugar (fbs)
- Resting ECG (restecg)
- Maximum Heart Rate (thalach)
- Exercise Induced Angina (exang)
- Oldpeak
- Slope
- CA
- Thal

---

##  Technologies Used

- Python
- Pandas
- Scikit-learn

---

##  Machine Learning Algorithms

- Decision Tree Classifier
- Random Forest Classifier

---

##  Project Workflow

1. Import Libraries
2. Load Dataset
3. Separate Features and Target
4. Split Dataset into Training and Testing Data
5. Train Decision Tree Model
6. Predict using Decision Tree
7. Calculate Accuracy
8. Train Random Forest Model
9. Predict using Random Forest
10. Calculate Accuracy
11. Find Feature Importance
12. Compare Both Models

---

##  Evaluation Metric

- Accuracy Score

---

##  Feature Importance

Random Forest provides Feature Importance, which shows which features contribute the most to predicting heart disease.

Example:

| Feature     |  Importance |
|-------------|-------------|
| Age         |    High     |
| Chest Pain  |    High     |
| Cholesterol |   Medium    |
| Resting BP  |   Medium    |

---

##  Expected Output

- Decision Tree Accuracy
- Random Forest Accuracy
- Feature Importance Table
- Prediction of Heart Disease

Example:

```
Decision Tree Accuracy: 84%

Random Forest Accuracy: 91%

Patient has Heart Disease.
```

---

##  Project Structure

```
Heart-Disease-Prediction/
│
├── heart_disease_cleveland.csv
├── Heart_Disease_Prediction.ipynb
├── README.md
├── requirements.txt
```

---

##  Future Improvements

- Add Confusion Matrix
- Add Classification Report
- Add Feature Importance Graph
- Build a Streamlit Web Application
- Deploy the Model Online

---

##  Author

**Prerna**

