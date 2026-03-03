# 🏥 HealthCare Premium Prediction

🚀 **Live Demo:**  
👉 https://healthcare-premiuim-prediction.streamlit.app/

---

## 📌 Project Overview

HealthCare Premium Prediction is a Machine Learning web application that predicts a user's healthcare insurance premium based on personal and medical details.

The system intelligently selects different models based on user conditions to provide accurate premium estimation.

This project demonstrates:
- Real-world ML problem solving
- Model deployment using Streamlit
- Production-ready ML pipeline structure
- Conditional model selection logic

---

## 🎯 Problem Statement

Health insurance premiums depend on multiple factors such as:

- Age  
- BMI  
- Medical history  
- Lifestyle habits  
- Smoking status  
- Other health-related parameters  

This project automates premium prediction using trained ML models and provides instant results through a web interface.

---

## ⚙️ Features

✅ User-friendly Streamlit interface  
✅ Condition-based model switching  
✅ Feature scaling before prediction  
✅ Multiple trained ML models  
✅ Real-time premium prediction  
✅ Clean and modular project structure  

---

## 🧠 Machine Learning Approach

- Separate models for different age categories  
- Pre-trained models stored using `joblib`  
- Feature scaling using trained scalers  
- XGBoost / Scikit-learn based training  
- Organized artifact storage  

Model artifacts are stored inside:

```
artifacts/
│
├── model_young.joblib
├── model_rest.joblib
├── scaler_young.joblib
└── scaler_rest.joblib
```

---

## 🛠️ Tech Stack

- Python  
- Streamlit  
- Pandas  
- NumPy  
- Scikit-learn  
- XGBoost  
- Joblib  

---

## 🚀 How to Run Locally

1️⃣ Clone the repository

```
git clone https://github.com/KrishnaTiwari1cr/ml_project_health_premium_prediction.git
```

2️⃣ Navigate to the project folder

```
cd ml_project_health_premium_prediction
```

3️⃣ Install dependencies

```
pip install -r requirements.txt
```

4️⃣ Run the app

```
streamlit run main.py
```

---

## 🌐 Deployment

This application is deployed using **Streamlit Cloud**.

Live Application:  
https://healthcare-premiuim-prediction.streamlit.app/

---

## 👨‍💻 Author

Krishna Tiwari  
B.Tech | Data & ML Enthusiast  

GitHub:  
https://github.com/KrishnaTiwari1cr  

---

## ⭐ If you like this project

Give it a star on GitHub ⭐
