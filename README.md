# 🧠 Sentiment Analysis Project (Flask + Next.js)

## Overview

This project is a **Sentiment Analysis Web Application** built with a **Flask backend** and a **Next.js frontend**. It allows users to input text, analyze its sentiment (Positive, Negative, Neutral), and also check the model’s accuracy against a test dataset. The model achieves an **accuracy of 76%**.

## 👨‍💻 Author & Researcher

**Name:** Syed Sajid Hussain
**Role:** AI Researcher & Full Stack Developer
**Contribution:** Model training, dataset creation, backend & frontend integration, and research on automated sentiment evaluation systems.

## 🚀 Tech Stack

* **Frontend:** Next.js (React-based UI)
* **Backend:** Flask (Python API)
* **AI Model:** TensorFlow / Keras
* **Preprocessing:** Tokenizer + Label Encoder (via Joblib)
* **Dataset:** Custom-generated balanced dataset (100k samples)
* **Accuracy Evaluation:** Integrated using sklearn’s `accuracy_score`

## ⚙️ Features

* Real-time sentiment prediction via Flask API
* Accuracy testing directly from frontend (no manual script required)
* Dataset auto-processing (tokenization, padding, label encoding)
* Balanced dataset generation (100k samples equally divided among 3 sentiments)
* Flask + Next.js integration with full CORS support

## 📊 Model Details

* Model: TensorFlow Sequential Model
* Layers: Embedding → LSTM → Dense → Softmax
* Optimizer: Adam
* Loss: Categorical Crossentropy
* Accuracy Achieved: **76%**

## 🧩 Dataset

* **Size:** 100,000 samples (balanced)
* **Classes:** Positive, Negative, Neutral
* **Format:** CSV (`text`, `label`)
* **Generated using:** Custom Python script with semantic diversity

## 💡 What’s Unique / New in This Project

This project introduces a **completely automated sentiment evaluation system** where:

* The **frontend** can trigger both **single predictions** and **accuracy evaluations** without requiring separate scripts or Jupyter notebooks.
* The **dataset generation system** can create **balanced, large-scale synthetic datasets** (up to 100k+ entries) automatically.
* The **backend dynamically validates** models for performance using real input + CSV validation in real-time.
* It provides a **ready-to-train AI environment** where developers can drop in any model and immediately test its live performance.

These innovations make it one of the few projects that **combine live AI inference, evaluation, and dataset automation** within a single integrated platform.

## 🧠 Research and Implementation Summary

During development, the following research and implementation steps were carried out:

1. Collected and preprocessed textual sentiment data.
2. Trained a TensorFlow-based model for sentiment classification.
3. Used Joblib to store and load preprocessing components (tokenizer, label encoder).
4. Built Flask API endpoints for prediction and accuracy testing.
5. Integrated with a Next.js frontend using REST APIs and CORS.
6. Designed an accuracy checking feature to test model performance directly from the UI.
7. Created custom Python scripts to generate 50k, 100k, and balanced datasets.
8. Achieved 76% accuracy after iterative testing and hyperparameter tuning.

## 🧪 How to Run

1. **Backend (Flask):**

   ```bash
   python app.py
   ```
2. **Frontend (Next.js):**

   ```bash
   npm run dev
   ```
3. Visit: `http://localhost:3000`

## 📁 Folder Structure

```
project/
│
├── backend/
│   ├── app.py
│   ├── sentiment_model.h5
│   ├── tokenizer.pkl
│   ├── label_encoder.pkl
│   └── sentiment_dataset.csv
│
├── frontend/
│   ├── pages/
│   ├── components/
│   └── ...
│
└── README.md
```

## 📈 Current Accuracy

* Model Accuracy: **76.0%** on balanced 100k dataset
