🛡️HEALTH INSURANCE COVARAGE PREDICTOR:
This project features an end-to-end Machine Learning Pipeline designed to predict whether an individual in Kenya likely has health insurance coverage. It uses a Random Forest Classifier trained on demographic and socio-economic survey data.
🔗 View Live App Here🚀 

PROJECT OVERVIEW:
The goal of this project is to leverage data science to understand the factors influencing health insurance uptake.
By analyzing features such as age, income, and employment status, the model provides an automated prediction that can be used for financial planning or public health research.

KEY FEATURES: 
End-to-End Pipeline: Automated data cleaning, imputation, and encoding .
Production Deployment: A serialized model artifact (.pkl) served via a Streamlit web interface. 
Custom Preprocessing: Modular Python logic to handle complex demographic data like age and income ranges 

🛠️ TECHNICAL STACK:
Language: Python
Data Analysis: Pandas, NumPy 
Machine Learning: Scikit-Learn (Random Forest, ColumnTransformers, Pipelines) 
Frontend: Streamlit 
Deployment: GitHub & Streamlit Cloud

📂REPOSITORY STRUCTURE:  
app.py: The main Streamlit application script for the user interface.
utils.py: Modular helper functions for data preprocessing .
insurance_model_pipeline.pkl: The trained and serialized Scikit-Learn pipeline 
Model.ipynb: The research notebook containing data cleaning, EDA, and model training 
Requirements.txt: Dependencies required to run the application.

Visualization:

<img width="1335" height="573" alt="image" src="https://github.com/user-attachments/assets/8834db0f-e94a-4f4d-a344-e04ff297d040" />

<img width="1335" height="573" alt="image" src="https://github.com/user-attachments/assets/83a648fe-5869-47e5-9806-615380033629" />

<img width="1335" height="573" alt="image" src="https://github.com/user-attachments/assets/b8f186e3-e583-4503-875d-5f4abbbfb76a" />


 📊 Model Performance: 
 
 The model was evaluated using 5-fold cross-validation, achieving a mean accuracy of approximately 70.9%  
 <img width="1335" height="537" alt="image" src="https://github.com/user-attachments/assets/d78bad57-4e3e-4bc2-bc87-192a0d732af1" />

 
 📝 How to Run Locally
 :
 Clone the repo: git clone  https://github.com/Antoe26/Insurance-Predictor.git
 Create a virtual environment: python3 -m venv venv
 Activate it: source venv/bin/activate
 Install dependencies: pip install -r requirements.txt
 Run the app: streamlit run app.py
 
  👤 AUTHOR
 
 Anthony Macharia
Mathematics and Computer Science Student, Murang'a University of Technology
