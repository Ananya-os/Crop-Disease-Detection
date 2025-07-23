# Crop-Disease-Detection
# 🌾 Crop Disease Detection App

A mobile application developed using **Flutter** that allows users to detect plant diseases by capturing or uploading an image of the crop leaf. The app uses a trained **EfficientNet-B0** deep learning model powered by **TensorFlow**, and stores user-uploaded images via **Firebase** and **Cloudinary**.

## 🚀 Features

- 📷 Capture or upload images of crop leaves
- 🤖 Detect specific plant diseases using EfficientNet-B0
- ☁️ Images stored securely using Firebase and Cloudinary
- 📱 Clean and user-friendly Flutter UI
- 🔐 Firebase authentication (optional for user access control)
- ⚡ Real-time predictions with high accuracy

## 🛠️ Tech Stack

- **Frontend**: Flutter
- **Model**: EfficientNet-B0 (TensorFlow)
- **Backend/ML Serving**: TensorFlow Lite / TensorFlow Model API (Cloud hosted)
- **Storage**: Firebase Storage & Cloudinary
- **Authentication**: Firebase Auth (optional)

## 📷 How It Works

1. The user captures or uploads an image of a crop leaf.
2. The image is uploaded to Firebase/Cloudinary.
3. The image is passed through the EfficientNet-B0 model.
4. The model predicts the disease category and displays the result.
5. The user receives actionable information for disease identification.


## 🧠 Model Details

- **Architecture**: EfficientNet-B0
- **Framework**: TensorFlow / TensorFlow Lite
- **Trained On**: Publicly available crop disease datasets (e.g., PlantVillage)





