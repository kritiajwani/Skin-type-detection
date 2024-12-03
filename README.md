# Skin-type-detection
This project leverages Convolutional Neural Networks (CNN) and OpenCV to predict skin types from facial images with high accuracy. It is designed to assist dermatological applications by providing insights into individual skin types based on image analysis.

Project Overview
The aim of this project is to build a reliable machine learning model to classify skin types. By processing facial images, the model extracts key features and categorizes skin into predefined types. This tool can benefit cosmetic, skincare, and medical industries.

Features
Image preprocessing using OpenCV for accurate feature extraction.
CNN model for efficient classification of skin types.
Evaluation metrics to validate model accuracy and performance.
Scalable for real-world applications, with a user-friendly interface for future integration.
Dataset
The dataset contains labeled images of different skin types. It includes variations across:

Skin tone
Lighting conditions
Facial angles
Columns in Metadata:

Image_ID
Skin_Type (Normal, Oily, Dry, Combination)
Skin_Tone
Additional attributes like age, gender, and region.
Model Architecture
Input Layer: Accepts preprocessed images.
Hidden Layers: Convolutional layers with ReLU activations and max-pooling for feature extraction.
Output Layer: Fully connected softmax layer for classification into skin types.
