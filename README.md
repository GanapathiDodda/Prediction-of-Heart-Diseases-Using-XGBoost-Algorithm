 Heart Disease Risk Prediction using XGBoost

This repository contains a machine learning project that predicts the risk of developing heart disease using the **XGBoost** algorithm. The predictive model was trained on the **Framingham Heart Disease Dataset**, with feature selection and analysis performed using **ANOVA** to identify the most significant predictors.

 Project Overview

- Dataset Framingham Heart Study dataset (Available publicly for research purposes)
- Algorithm : XGBoost Classifier  
- Feature Selection : ANOVA (Analysis of Variance)  
- Deployment: Streamlit Web App  
- File Format : Project files uploaded as a `.zip` archive


Files Included

- `app.py` – Python source code for the Streamlit web application  
- `scaler.pkl` – Pre-fitted scaler used for feature normalization  
- `selected_features.pkl` – List of significant features selected via ANOVA  
- `requirements.txt` – (Optional) Dependencies required to run the app (you can add this if needed)  
- `heart_disease_xgboost_project.zip` – Compressed archive containing the above files

How to Run the Project
-Clone the repository: git clone https://github.com/your-username/heart-disease-xgboost.git
cd heart-disease-xgboost
- Unzip the project files : unzip heart_disease_xgboost_project.zip
- Install required dependencies : pip install -r requirements.txt
- Run the Streamlit app : streamlit run app.py


Features

- Interactive UI built with **Streamlit**
- Predicts the likelihood of heart disease based on user input
- Uses preprocessed features and scaling for consistent predictions
- Model trained using **XGBoost**, known for its high performance and accuracy
