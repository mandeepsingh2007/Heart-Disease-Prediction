# Heart Disease Prediction Model

This project utilizes logistic regression to predict the likelihood of heart disease based on patient data. The model is trained using the **Heart Disease Dataset** and provides predictions for new input data.

---

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Usage](#usage)
- [Results](#results)
- [Installation](#installation)
- [Future Improvements](#future-improvements)

---

## Overview
Heart disease is a critical health issue, and early detection can significantly improve treatment outcomes. This project uses a machine learning approach to analyze clinical features and predict the presence of heart disease. The logistic regression algorithm is employed for classification.

---

## Dataset
The **Heart Disease Dataset** contains various clinical features such as:
- Age
- Gender
- Chest pain type
- Resting blood pressure
- Cholesterol level
- Fasting blood sugar
- Resting ECG results
- Maximum heart rate achieved
- Exercise-induced angina
- ST depression induced by exercise
- Number of major vessels
- Thalassemia, and more.

The target variable is:
- `0`: No heart disease
- `1`: Presence of heart disease

---

## Model Training
1. **Preprocessing**:
   - Features (`X`) and target (`Y`) variables were separated from the dataset.
   - Data was split into training and testing sets with a ratio of 80:20.
   
2. **Algorithm**:
   - Logistic Regression was chosen for its simplicity and effectiveness in binary classification tasks.

3. **Training**:
   - The model was trained on the training data (`X_train`, `Y_train`).

---

## Evaluation
The model's performance was evaluated using **accuracy** on both training and test datasets.

- **Training Data Accuracy**: `85.1%`
- **Test Data Accuracy**: `82%`

---

## Usage
To use the model for prediction:

1. Provide patient data as a tuple. Example:
   ```python
   input_data = (52, 1, 0, 125, 212, 0, 1, 168, 0, 1, 2, 2, 3)
   
---

## Future Improvements
Add more advanced models like Random Forest or Neural Networks.

Implement feature scaling for better model performance.

Deploy the model as a web application for public usage.

   
