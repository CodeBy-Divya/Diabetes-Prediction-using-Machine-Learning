# Diabetes Prediction using Machine Learning

## Overview

This project uses **Machine Learning** to predict whether a person is diabetic or not based on medical attributes.
The model is trained on the **Pima Indians Diabetes Dataset** and uses a **Support Vector Machine (SVM)** classifier to make predictions.

The system takes health-related inputs such as glucose level, blood pressure, BMI, age, etc., and predicts the likelihood of diabetes.

---

## Dataset

The dataset used in this project is the **Pima Indians Diabetes Dataset**.

Features in the dataset:

* Pregnancies – Number of times pregnant
* Glucose – Plasma glucose concentration
* BloodPressure – Diastolic blood pressure
* SkinThickness – Triceps skin fold thickness
* Insulin – 2-Hour serum insulin
* BMI – Body Mass Index
* DiabetesPedigreeFunction – Diabetes family history function
* Age – Age of the person

Target Variable:

* **Outcome**

  * 0 → Non-Diabetic
  * 1 → Diabetic

---

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* Google Colab / Jupyter Notebook

---

## Machine Learning Workflow

### 1. Data Collection

The dataset is loaded using **Pandas**.

### 2. Data Analysis

Basic analysis is performed:

* Checking dataset shape
* Statistical summary
* Class distribution
* Group analysis using Outcome

### 3. Data Preprocessing

* Features and labels are separated.
* Data is standardized using **StandardScaler**.

### 4. Train-Test Split

The dataset is divided into:

* 80% Training Data
* 20% Testing Data

### 5. Model Training

A **Support Vector Machine (SVM)** classifier with a linear kernel is used to train the model.

### 6. Model Evaluation

Accuracy score is calculated for:

* Training data
* Testing data

### 7. Prediction System

The trained model can predict diabetes using new input data.

Example input:

(5,166,72,19,175,25.8,0.587,51)

Output:

* Person is Diabetic
  or
* Person is Not Diabetic

---

## Project Structure

```
Diabetes-Prediction/
│
├── diabetes.csv
├── diabetes_prediction.ipynb
├── README.md
```

---

## How to Run the Project

1. Clone the repository

```
git clone https://github.com/yourusername/diabetes-prediction.git
```

2. Install required libraries

```
pip install numpy pandas scikit-learn
```

3. Run the notebook or Python file.

---

## Future Improvements

* Use multiple ML algorithms (Random Forest, Logistic Regression, XGBoost)
* Improve accuracy with hyperparameter tuning
* Build a web application using Flask or Streamlit
* Deploy the model online

---

## Conclusion

This project demonstrates how machine learning can be applied in the healthcare domain to assist in early diabetes detection. With proper data and improved models, such systems can support medical decision-making.
