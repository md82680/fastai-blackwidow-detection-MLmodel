# 🕷️ Black Widow Detection Model

## 📌 Project Overview
This project is a **deep learning model** that classifies spider images to determine whether a given spider is a **Black Widow or not** using a **ResNet-based Convolutional Neural Network (CNN)**.

### 🔍 Key Features
- **Image Classification**: Predicts if an image contains a Black Widow spider.
- **Transfer Learning**: Utilizes `resnet18` from FastAI for accurate predictions.
- **Dataset**: Web-scraped images from DuckDuckGo.
- **High Accuracy**: The model achieves strong classification performance.
- **FastAI + PyTorch**: Built using Python’s powerful deep learning frameworks.

## 🚀 How to Use

### **1️⃣ Clone this repository**
git clone https://github.com/md82680/fastai-blackwidow-detection-MLmodel.git
cd fastai-blackwidow-detection-MLmodel

### **2️⃣ Install dependencies**

pip install -r requirements.txt

### **Example Prediction:**

is_bwspider, _, probs = learn.predict(PILImage.create('bwspider.jpg'))
print(f"This is a: {is_bwspider}.")
print(f"Probability it's a Black Widow: {probs[0]:.4f}")

### **Example Output:**

This is a: black widow spider.
Probability it's a Black Widow: 0.9985

### **📖 Notebook**

Check out the full implementation in black_widow_detection.ipynb.

### Author: 
Michael Despo

### Built With: 
FastAI, PyTorch, and Python

### 🎯 Feel free to contribute or reach out for collaboration! 🚀
