# Diabetes Prediction Using Machine Learning
A machine learning project to predict diabetes using the Pima Indian dataset, with Streamlit app for interactive use.

📊 Project Overview
The objective of this project is to classify whether a patient is likely to be diabetic based on diagnostic measurements. It demonstrates the full machine learning pipeline from data preparation to deployment.

Key components:
- Data cleaning and preprocessing.
- Exploratory Data Analysis (EDA).
- Machine learning model development (Logistic Regression, Random Forest).
- Streamlit-based prediction web app.

🧬 Dataset
- Source: Pima Indian Diabetes Dataset – Kaggle
- Features: Glucose, Blood Pressure, BMI, Age, Insulin, etc.
- Target: Outcome (0 = Non-diabetic, 1 = Diabetic)

📁 Project Structure
File	                      Description
diabetes.csv	              Dataset used for analysis
diabetes_analysis.ipynb	    Jupyter Notebook with data exploration & ML
app.py	                    Streamlit web application
diabetes_model.pkl	        Trained Random Forest model
scaler.pkl	                StandardScaler for input normalization
requirements.txt	          Python dependencies
README.md	                  Project documentation

🚀 Getting Started
1. Clone the Repository

git clone https://github.com/SaiKeerthanaLavudya/Healthcare-Diabetes-Prediction.git
cd Healthcare-Diabetes-Prediction

2. Install Required Packages

pip install -r requirements.txt

3. Run the Streamlit App

streamlit run app.py

📒 Notebook Highlights
The diabetes_analysis.ipynb notebook includes:
- Data exploration with charts and statistics
- Cleaning and feature scaling
- Model training and comparison
- Performance evaluation using accuracy, confusion matrix, and ROC curve

🌐 Deployment
This application can be deployed on Streamlit Cloud for public access.

👩‍💻 Author
Sai Keerthana Lavudya
GitHub Profile: https://github.com/SaiKeerthanaLavudya
