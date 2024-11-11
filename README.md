# App is stopped... Cloud is expensive bruh 🤑🤑
# 🌾 MACHINE LEARNING MODELS FOR RICE SALINITY PREDICTION 🌾

## 🌟 Overview

This project classifies rice crops based on **salinity stress levels** using **image analysis**. 🌱 Salinity stress affects crop health and yield, and this model assists farmers and agricultural experts in evaluating salinity stress to make better-informed decisions.

## 🧠 Models Used

1. **🌿 Plant Detection Model**: A CNN model that verifies if the uploaded image contains a plant. If not, it’s rejected. 🚫🌱
2. **🔍 Base Models for Feature Extraction**:
   - **InceptionV3**: Captures detailed multi-scale patterns.
   - **ResNet50**: Extracts deep features using skip connections.
   - **EfficientNetB3**: Balances accuracy and efficiency in feature extraction.
   - **VGG16**: A deep architecture that captures high-level features.
3. **🤖 Meta-Learner**: A logistic regression model combines features from the base models to predict the salinity stress level.

## 🔄 How It Works

1. **📥 Input**: Upload an image of rice crops.
2. **🌱 Plant Detection**: The system verifies the presence of a plant.
3. **🖼️ Preprocessing**: Image resizing and background removal are applied.
4. **🧬 Feature Extraction**: Base models extract important features from the image.
5. **📊 Prediction**: The meta-learner combines these features to predict the salinity stress level.
6. **📈 Output**: The predicted salinity level is displayed to the user.

## 📝 Instructions for Users

1. **Upload** an image of the rice crop through the interface.
2. **Check** the result displayed, showing the predicted salinity stress level.
3. Ensure the **image size is below 1.5 MB** for optimal processing. 📏

## ⚙️ Tech Stack

- **Frontend**: HTML, CSS, Bootstrap, JavaScript 🌐
- **Backend**: Flask API 🐍
- **Deployment**: Azure ☁️
- **Model Storage**: Azure Blob Storage 📦

### 📱 This responsive web app ensures compatibility across all devices, bringing **salinity stress detection** right to your fingertips!
