# Brain Tumor Detection System

## Overview
A deep learning-based system that detects and classifies brain tumors from MRI scans into multiple categories.

## Objective
- Automate tumor detection
- Assist early diagnosis using AI

## Approach
- Dual-model approach:
  - Logistic Regression (baseline)
  - Xception CNN (deep learning)
- Classification:
  - Glioma
  - Meningioma
  - Pituitary
  - No Tumor

## Dataset
- MRI brain scan images
- Training and Testing folders
- Preprocessing:
  - Resizing
  - Normalization
  - Label encoding

## Tech Stack
- Python
- TensorFlow / Keras
- OpenCV
- Streamlit

## Architecture
1. Image input
2. Preprocessing
3. Model prediction
4. Output classification

## Results
- High accuracy using Xception model
- Better performance than traditional ML models

## Challenges
- Class imbalance handled via preprocessing
- Image quality variations addressed with normalization

## Future Improvements
- Cloud deployment
- Model explainability (Grad-CAM)
- Real-time integration

## How to Run
```bash
pip install -r requirements.txt
streamlit run app.py
