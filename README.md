# ❤️ Heart Stroke Prediction by Sakshi

A Machine Learning-based web application that predicts the risk of heart disease using user health parameters. This project is built using a KNN algorithm and deployed with Streamlit for an interactive user experience.

---

## 🚀 Features
- Predicts heart disease risk (High / Low)
- User-friendly web interface using Streamlit
- Real-time prediction based on input parameters
- Data preprocessing with:
  - Feature Scaling
  - One-Hot Encoding
- Trained Machine Learning model (KNN)

---

## 🧠 Technologies Used
- Python  
- Pandas  
- Scikit-learn  
- Streamlit  
- Joblib  

---

## 📊 Input Parameters
The model takes the following inputs:
- Age  
- Sex  
- Chest Pain Type  
- Resting Blood Pressure  
- Cholesterol  
- Fasting Blood Sugar  
- Resting ECG  
- Maximum Heart Rate  
- Exercise-Induced Angina  
- Oldpeak (ST Depression)  
- ST Slope  

---

## ⚙️ How It Works
1. User enters health details in the web app  
2. Data is preprocessed (encoding + scaling)  
3. Input is passed to trained KNN model  
4. Model predicts:
   - ⚠️ High Risk  
   - ✅ Low Risk  

---

## 💻 Installation & Setup

```bash
https://github.com/Sak12345641/smart-heart-risk-prediction/tree/main

# Run the app
streamlit run app.py
