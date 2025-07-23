# Employee-Salary-Prediction
I have created an Employee Salary Prediction Web Application which helps to Predict the salary of the employees who work in a organization.
<br>
<br>
💼 Employee Salary Prediction Web Application:
<br>
This is a machine learning web application that predicts the salary category of employees (e.g., >50K or <=50K) based on features such as education, experience, and other demographic factors. The application uses the K-Nearest Neighbors (KNN) algorithm and is deployed using Streamlit and ngrok for public access.
<br>
<br>
📌 Overview
The primary goal of this project is to build and compare multiple classification models to predict employee salary categories, and finally deploy the best-performing model using an interactive web interface.
<br>
<br>
✅ Features
Multiple ML models tested (KNN, Logistic Regression, MLP Classifier)
<br>
Final model chosen: K-Nearest Neighbors (KNN)
<br>
Clean and interactive Streamlit UI
<br>
Hosted using ngrok for public tunneling
<br>
Real-time user input for predictions
<br>
<br>
🛠️ Tech Stack:
<br>
Frontend/UI: Streamlit
<br>
Model Development: Scikit-learn, Pandas, NumPy
<br>
Model: K-Nearest Neighbors (KNN)
<br>
Deployment Tunnel: ngrok
<br>
Language: Python
<br>
<br>
<br>
🎯 How It Works
<br>
User inputs employee details (age, education, experience, etc.) via the UI.
<br>
Data is preprocessed to match training schema.
<br>
The KNN model predicts whether the employee earns >50K or <=50K.
<br>
The result is shown instantly in the UI.
<br>
<br>
📊 Sample Input Features
<br>
Age
<br>
Education Level
<br>
Hours-per-week
<br>
Workclass
<br>
Occupation
<br>
Marital Status
<br>
Native Country
<br>
<br>
📎 Dependencies
<br>
streamlit
<br>
scikit-learn
<br>
pandas
<br>
numpy
<br>
joblib
<br>
ngrok (optional CLI tool for tunneling)
<br>
<br>
🧩 Future Improvements
We can also add support for model selection in UI
<br>
Add data visualization panels
<br>
Save prediction history
<br>
Deploy on cloud (e.g., Streamlit Cloud, Heroku, or AWS)
