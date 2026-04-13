# 🧠 Brain Tumor Detection System

## 📌 Overview
A deep learning-based medical imaging system that detects and classifies brain tumors from MRI scans into multiple categories.

## 🎯 Objective
- Automate tumor detection
- Assist early diagnosis using AI

## 🧠 Approach
- Dual-model approach:
  - Logistic Regression (baseline)
  - Xception CNN (deep learning)
- Image classification into:
  - Glioma
  - Meningioma
  - Pituitary
  - No Tumor

## 📊 Dataset
- MRI brain scan images
- Structured into Training and Testing folders
- Preprocessing:
  - Resizing
  - Normalization
  - Label encoding

## ⚙️ Tech Stack
- Python
- TensorFlow / Keras
- OpenCV
- Streamlit

## 🏗️ Architecture
1. Image input
2. Preprocessing
3. Model prediction
4. Output classification

## 📈 Results
- High accuracy using Xception model
- Improved performance over traditional ML models

## ⚠️ Challenges
- Class imbalance → handled via preprocessing
- Image quality variation → normalization

## 🔮 Future Improvements
- Deploy on cloud
- Add explainability (Grad-CAM)
- Real-time hospital integration

## 🖥️ How to Run
```bash
pip install -r requirements.txt
streamlit run app.py
