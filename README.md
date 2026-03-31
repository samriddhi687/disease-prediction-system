# 📌 Disease Prediction System 
---
## 📖 Overview
This project is a Machine Learning-based Disease Prediction System that predicts whether a person is likely to have a disease based on medical parameters such as glucose level, BMI, age, etc. The system uses a trained ML model and provides predictions through a simple Streamlit web interface.

## 🎯 Objective
- Predict disease presence (Yes/No)
- Assist in early risk detection
- Demonstrate end-to-end ML pipeline

## 🧠 Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Joblib
- Streamlit

## 📊 Dataset
Pima Indians Diabetes Dataset
Features include:
- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

## Target:
0 → No Disease

1 → Disease

## ⚙️ Project Workflow
Data Collection → Preprocessing → Model Training → Evaluation → Deployment

## 🏗️ Project Structure

├── diabetes_data.csv

├── train.py

├── app.py

├── model.pkl

├── scaler.pkl

└── README.md

## 🚀 How to Run the Project
- Step 1: Install Dependencies
pip install pandas numpy scikit-learn streamlit joblib
- Step 2: Train the Model
python train.py. This generates: model.pkl and scaler.pkl .
- Step 3: Run the App
streamlit run app.py

## Sample input
Pregnancies: 6

Glucose: 148

Blood Pressure: 72

Skin Thickness: 35

Insulin: 0

BMI: 33.6

Diabetes Pedigree Function: 0.627

Age: 50

## Sample Output
<img width="702" height="848" alt="Screenshot 2026-03-31 193323" src="https://github.com/user-attachments/assets/2081e6cb-7694-40ad-a981-3aae6b146455" />

## 📊 Evaluation Metrics
- Accuracy
- Precision
- Recall (priority metric)
- Confusion Matrix

## 🔮 Future Improvements
- Use larger and real-world datasets
- Add visualization dashboards
- Deploy online (cloud)
- Improve model accuracy

## 📌 Conclusion
This project demonstrates how machine learning can be used to analyze medical data and predict disease risk, providing a foundation for real-world healthcare applications.
