# 🧠 Character Recognition System (OCR)

## 📌 Overview
This project is an OCR-based character recognition system that identifies
alphabets and numbers across different fonts using a Convolutional Neural Network.

## 🎯 Problem Statement
Traditional OCR systems struggle with font variations and handwritten styles.
This project aims to improve recognition accuracy using deep learning techniques.

## 🛠️ Tech Stack
- Python
- TensorFlow
- CNN
- NumPy
- OpenCV

## ⚙️ How It Works
1. Images are preprocessed (grayscale, resizing, normalization)
2. Data is split into training and testing sets
3. A CNN model is trained on MNIST + custom font datasets
4. The model predicts characters from new images

## 📊 Results
- Improved accuracy after preprocessing and tuning
- Model generalizes better across multiple font styles

## 🚀 How to Run
```bash
pip install -r requirements.txt
python src/train.py
