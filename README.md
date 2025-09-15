# 🌱 Plant Disease Classification using EfficientNetB4

This project implements a **deep learning model** for detecting and classifying plant leaf diseases using **TensorFlow** and **EfficientNetB4**.  
The dataset is preprocessed, split into training/validation/testing sets, and then used to train a transfer learning model. The model helps in early identification of crop diseases, assisting farmers and agriculturists in better crop management.  

---

## 📌 Business Problem
Plant diseases can severely impact crop yield and food supply. Early and accurate disease detection enables farmers to take timely measures, reducing economic losses and improving agricultural productivity. This project leverages **computer vision** to classify plant leaf images into healthy or diseased categories.

---

Technogies used
- TensorFlow
- NumPy
- Matplotlib
- split-folders


## 🚀 Features
- Data preprocessing and augmentation  
- Transfer learning with **EfficientNetB4**  
- Model training, validation, and fine-tuning  
- Visualization of accuracy and loss curves  
- Evaluation on test dataset  
- Prediction visualization with sample test images  

---

## 📂 Dataset
The dataset is downloaded from **[Mendeley Plant Leaf Diseases Dataset](https://data.mendeley.com/datasets/tywbtsjrjv/1)** and contains various plant leaf disease classes with augmentation.  
It is split into **train (80%)**, **validation (10%)**, and **test (10%)** using the `split-folders` library.

---

## 🛠️ Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/plant-disease-classification.git
cd plant-disease-classification
pip install -r requirements.txt
