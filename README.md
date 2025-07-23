# 🌾 Crop Disease Detection App

A mobile application developed using **Flutter** that enables users, especially farmers, to detect crop diseases by simply capturing or uploading an image of a crop leaf. The app uses a powerful **EfficientNet-B0** deep learning model with **TensorFlow** to identify diseases, and provides **relevant treatment suggestions** based on the detected disease. All images are securely stored using **Firebase** and **Cloudinary**, ensuring scalability and real-time access.

## 🚀 Features

- 📷 Capture or upload images of crop leaves
- 🤖 Detect specific plant diseases using EfficientNet-B0
- 💊 Get accurate **treatment suggestions** based on disease type
- ☁️ Secure image storage with Firebase and Cloudinary
- 📱 Clean and responsive Flutter UI
- 🔐 Optional Firebase authentication for user access

## 🛠️ Tech Stack

- **Frontend**: Flutter
- **Model**: EfficientNet-B0 (TensorFlow)
- **Backend/ML Serving**: TensorFlow Lite / TensorFlow Model API (Cloud-hosted)
- **Storage**: Firebase Storage & Cloudinary
- **Authentication**: Firebase Auth (optional)

## 📷 How It Works

1. The user captures or uploads an image of a crop leaf.
2. The image is uploaded to Firebase/Cloudinary.
3. The image is analyzed by the EfficientNet-B0 model.
4. The app displays the **disease name** and the **corresponding treatment suggestions**.
5. The user can follow the recommendations to address the crop issue.

## 🧠 Model Details

- **Architecture**: EfficientNet-B0
- **Framework**: TensorFlow / TensorFlow Lite
- **Training Dataset**: Public crop disease datasets (e.g., PlantVillage)

## 💊 Treatment Suggestion

Each disease prediction is paired with a curated treatment guide which may include:
- Recommended pesticides/fungicides
- Organic solutions
- Preventive measures
- Agronomic best practices

## 📈 Future Improvements
Offline detection using TensorFlow Lite

Multilingual support for wider regional use

Crop health tips and seasonal care reminders

Farmer feedback integration for treatment validation

## Credits
Ananya D R - Machine Learning model development and integration
Sanal Sajan E, Roslina Manue, Aditya R K - App Development,Firebase and Cloudinary integration
