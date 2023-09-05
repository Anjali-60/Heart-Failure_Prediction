# Heart-failure-prediction-project

### Introduction
Heart failure is a critical medical condition that affects millions of individuals worldwide. Early detection and prediction of heart failure can significantly improve patient outcomes and aid healthcare providers in making informed decisions. This project addresses the need for an accurate and reliable heart failure prediction model using machine learning techniques.

### Problem Statement
The primary objective of this project is to develop a predictive model that can estimate the risk of heart failure in individuals based on their medical and demographic information. Early identification of high-risk patients can lead to proactive medical interventions and potentially save lives.

### Dataset
We have utilized a comprehensive dataset containing a wide range of patient attributes and outcomes. The dataset includes the following features:

1) **Age**: The age of the patient.
2) **Anaemia**: Whether the patient has anemia (0 for No, 1 for Yes). 
3) **Creatinine Phosphokinase**: The level of creatinine phosphokinase in the blood.              
4) **Diabetes**: Whether the patient has diabetes (0 for No, 1 for Yes).
5) **EjectionFraction**: The percentage of blood that is ejected from the heart during each heartbeat. 
6) **High Blood Pressure**: Whether the patient has high blood pressure (0 for No, 1 for Yes). 
7) **Platelets**: The count of platelets in the blood.  
8) **Serum Creatinine**: The level of serum creatinine in the blood.
9) **Serum Sodium**: The level of serum sodium in the blood.  
10) **Sex**: The gender of the patient (0 for Female, 1 for Male).
11.**Smoking**: Whether the patient is a smoker (0 for No, 1 for Yes).
12) **Time**: The follow-up period in days.
13) **DEATH_EVENT**: The outcome (0 for Survived, 1 for Deceased).

### Key Features:
1) **Data Exploration and Visualization**: We begin by exploring and visualizing the dataset to gain insights into the distribution of features and their relationships with the target variable (DEATH_EVENT).
2) **Feature Scaling**: We perform feature scaling to ensure that all features have consistent scales.
3) **Model Building**: We employ logistic regression, a powerful classification algorithm, to build our predictive model. Logistic regression is chosen for its interpretability and ability to handle binary classification tasks effectively.
4) **Evaluation and Confusion Matrix**: To assess the model's performance, we generate a confusion matrix and calculate relevant metrics such as accuracy, precision.
5) **Prediction**: Once our model is trained and validated, it can be used to predict the risk of heart failure for new patients, aiding healthcare professionals in making timely and informed decisions.

### Getting Started:
1) Clone the repository to your local machine using the command: git clone https://github.com/Anjali-60/Driver-Drowsiness-Detection-System-Project.git
2) Install the required dependencies and libraries as mentioned in the requirements.txt file.
3) Explore the Jupyter notebooks in order to understand the system's functionality and model training process.
4) Run the main.ipynb notebook to experience the heart failure prediction system.
