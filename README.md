❤️ **Heart Disease Prediction using Logistic Regression**


📌 **Project Overview**

Heart disease is one of the leading causes of death worldwide. Early detection can help prevent serious complications and improve patient outcomes.

In this project, I built a Logistic Regression classification model that predicts whether a person is likely to have heart disease based on several medical attributes such as age, cholesterol levels, heart rate, and other clinical measurements.

The goal of this project is to demonstrate how machine learning can assist healthcare professionals in identifying high-risk patients, potentially reducing the need for expensive or invasive diagnostic procedures.



🎯 **Problem Statement**

Medical diagnosis often requires multiple clinical tests, which can be costly and time-consuming.

Using historical patient data, this project aims to answer:

Can we predict the presence of heart disease using patient health metrics?

This model attempts to classify patients into:

0 → No Heart Disease

1 → Presence of Heart Disease




📊 **Dataset**

The dataset used in this project is the Heart Disease Dataset from the UCI Machine Learning Repository.

Dataset contains 14 medical attributes, including:

| Feature  | Description                          |
| -------- | ------------------------------------ |
| age      | Age of the patient                   |
| sex      | Gender of the patient                |
| cp       | Chest pain type                      |
| trestbps | Resting blood pressure               |
| chol     | Serum cholesterol                    |
| fbs      | Fasting blood sugar                  |
| restecg  | Resting electrocardiographic results |
| thalach  | Maximum heart rate achieved          |
| exang    | Exercise induced angina              |
| oldpeak  | ST depression induced by exercise    |
| slope    | Slope of peak exercise ST segment    |
| ca       | Number of major vessels              |
| thal     | Thalassemia                          |
| target   | Heart disease presence (0 or 1)      |

Source:
UCI Machine Learning Repository



🛠️ **Project Workflow**
1️⃣ **Data Exploration**

Checked for missing values

Generated statistical summaries

Analyzed distributions of features

Visualized relationships between variables

2️⃣ **Exploratory Data Analysis**

Key visualizations included:

Target distribution

Feature relationships

Correlation analysis

These steps helped identify patterns between health indicators and heart disease risk.

3️⃣ **Data Preprocessing**

Feature selection

Train-test split

Data preparation for machine learning models

4️⃣ **Model Building**

A Logistic Regression model was trained to classify patients based on their medical attributes.

Why Logistic Regression?

Suitable for binary classification problems

Provides interpretable results

Helps understand feature influence on predictions

5️⃣ **Model Evaluation**

The model performance was evaluated using:

Accuracy

Confusion Matrix

Classification Metrics

These metrics help assess how well the model distinguishes between patients with and without heart disease.


📈 **Key Insights from the Model**

From the exploratory analysis and modeling process, several insights emerged:

-- Certain clinical indicators such as chest pain type, cholesterol levels, and maximum heart rate show strong relationships with heart disease.

-- Patients with exercise-induced angina and abnormal ST depression levels are more likely to have heart disease.

-- Logistic Regression provides interpretable coefficients that help understand how each feature contributes to the prediction.

-- These insights demonstrate how machine learning can support medical decision-making by identifying potential risk factors.



🚀 **Technologies Used**

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook



📂 **Project Structure**
Logistic-Regression-Heart-Disease/
│
├── Logistic-Regression-Project.ipynb
├── heart.xls
├── README.md



🔮 **Future Improvements**

Possible improvements for this project include:

Testing additional models such as:

Random Forest

Gradient Boosting

Support Vector Machines

Hyperparameter tuning

Feature engineering

Deploying the model as a web application for real-time predictions



🤝 **Conclusion**

This project demonstrates how machine learning models like Logistic Regression can be applied to healthcare datasets to predict disease risk. With proper validation and further improvements, such models could assist doctors in early detection and preventive care strategies.
