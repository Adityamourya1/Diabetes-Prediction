🫁 Lung Cancer Prediction Web Application
📌 Overview

The Lung Cancer Prediction Web Application is a machine learning–based healthcare tool that predicts the likelihood of lung cancer based on patient health parameters.

The application uses a trained machine learning model and an interactive web interface built with Streamlit to provide real-time predictions based on user input.
This Streamlit App utilizes a Machine Learning API built with FastAPI in order to detect lung cancer in patients based on the following criteria: age, gender, blood pressure, smoke, coughing, allergies, fatigue etc.
This project demonstrates the application of machine learning in healthcare analytics and web deployment, showcasing skills in data science, model deployment, and interactive web applications.

🚀 Features

🧠 Machine Learning–based lung cancer risk prediction
📊 Interactive and user-friendly web interface
⚡ Real-time predictions using trained ML models
📝 Input multiple health-related parameters
🔍 Instant prediction results

⚙️ System Workflow

User Input → Data Preprocessing → ML Model → Prediction → Result Display
User enters health-related parameters.
Input data is processed and formatted.
The trained machine learning model analyzes the input.
The system predicts whether lung cancer risk is present.
The prediction result is displayed instantly on the interface.


The values "M" and "F" in the "GENDER column were converted to 1 and 0 respectively.
The values "YES" and "NO" in the "LUNG_CANCER" column were converted to 1 and 0 respectively.
The values "2" and "1" in the rest of the columns were converted to 1 and 0 respectively.
The processed dataset was then saved as processed_lung_cancer.csv

Logistic Regression
Decision Tree
Random Forest
XGBoost
GradientBoostClassifier
SupportVectorClassifier
The final model used for the API was the Gradient Boost Classifier model which had an accuracy score of 0.94.


