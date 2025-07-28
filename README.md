🫀 Cardiovascular Disease Detection
This project aims to detect the likelihood of cardiovascular disease in a patient using machine learning models based on medical and lifestyle attributes. 
It provides a streamlined pipeline for data preprocessing, model training, evaluation, and prediction through an interactive web interface.

📌 Features
✅ Data preprocessing and feature scaling


✅ Multiple ML model support (Logistic Regression, Random Forest, XGBoost, etc.)
✅ Model evaluation with accuracy, precision, recall, and ROC-AUC
✅ Streamlit/FastAPI web interface for real-time prediction
✅ Clean and modular codebase


🧠 Technologies Used
Python 3.x
Pandas, NumPy
Scikit-learn, XGBoost
Matplotlib, Seaborn
Streamlit / FastAPI
Jupyter Notebook / VSCode

📁 File Structure 
cardiovascular-detection/
│
├── data/
│   └── cardio_data.csv             # Dataset used for training
│
├── models/
│   └── model.pkl                   # Trained ML model
│
├── notebooks/
│   └── EDA.ipynb                   # Exploratory Data Analysis notebook
│
├── app/
│   ├── app.py                      # FastAPI or Streamlit backend
│   └── utils.py                    # Helper functions
│
├── train.py                        # Model training and evaluation script
├── requirements.txt                # Dependencies
├── README.md                       # Project README
└── LICENSE                         # Optional license file

📊 Dataset
The dataset contains patient health metrics like:

Age

Gender

Blood pressure (systolic/diastolic)

Cholesterol and glucose levels

Smoking, alcohol intake, physical activity

Body Mass Index (BMI)

Target: Presence of cardiovascular disease

🧪 Model Performance
Model	                Accuracy	Precision	Recall	 ROC-AUC
Logistic Regression	    0.72	   0.70	      0.75	 0.78
Random Forest    	      0.78	   0.76      	0.80	 0.84
XGBoost	                0.80	   0.78	      0.82	 0.86

📌 Future Improvements
Incorporate deep learning models
Real-time ECG/EHR data integration
Backend database for user management
Mobile app integration

Contributors- M Sree Nikhil
