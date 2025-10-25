# 🧠 Sentiment Analysis (AI Web App)

## 📋 Overview
This is a **Sentiment Analysis Web Application** built using **Flask (Backend)** and **Next.js (Frontend)**.  
It predicts the sentiment (Positive, Negative, Neutral) of any given text and also measures model accuracy.

---

## 🧩 Project Repositories

### 🖥️ Frontend (Next.js)
➡️ **Repository:** [Sentiment Analysis Frontend](https://github.com/sajid384/Sentoiment_analysis_frontend)

This repository contains:
- User interface built with **Next.js**
- Real-time prediction & accuracy test UI
- Integration with Flask backend via REST API

### ⚙️ Backend (Flask)
➡️ **Repository:** [Sentiment Analysis Backend](https://github.com/sajid384/sentiment_analysis_backend)

This repository contains:
- Flask API for model prediction and accuracy testing
- Trained TensorFlow sentiment model (`sentiment_model.h5`)
- Tokenizer and Label Encoder saved via Joblib
- Dataset loading and preprocessing

---

## 👨‍💻 Author & Researcher
**Name:** Syed Sajid Hussain  
**Role:** AI Researcher & Full Stack Developer  
**Contribution:** Developed, trained, and integrated the AI model with the frontend and backend. Created a self-generated dataset and achieved 76% accuracy on evaluation.

---

## ⚙️ Features
- Real-time sentiment prediction from the web UI  
- Accuracy testing directly from frontend  
- Flask–Next.js full-stack integration  
- Custom dataset generation & preprocessing  
- Achieved **76% accuracy** on 100k+ balanced dataset  

---

## 🧠 Model Details
- **Framework:** TensorFlow / Keras  
- **Architecture:** Embedding → LSTM → Dense → Softmax  
- **Optimizer:** Adam  
- **Loss:** Categorical Crossentropy  
- **Accuracy:** 76%  

---

## 🧪 How to Run

### 1️⃣ Backend (Flask)
```bash
python app.py
