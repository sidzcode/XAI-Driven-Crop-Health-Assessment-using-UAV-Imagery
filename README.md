# XAI-Driven-Crop-Health-Assessment-using-UAV-Imagery
In this project, we have developed a robust Convolutional Neural Network (CNN) model designed to classify UAV images of crops as either diseased or non-diseased. The CNN model is trained on a large dataset of UAV images and is optimized for high accuracy in disease detection.

![home_page](https://github.com/user-attachments/assets/8c1a58e7-f1ef-4bdf-aab3-f6848a6e9cc5)


# Overview

This project focuses on the detection of Alternaria solani, a fungal pathogen causing early blight in potato crops, using UAV (Unmanned Aerial Vehicle) images. By leveraging deep learning technology, specifically Convolutional Neural Networks (CNN), this project aims to provide an efficient and accurate solution for early disease detection. The integration of Explainable AI (XAI) techniques ensures transparency and trust in model predictions, while a user-friendly interface allows users to upload images and receive real-time predictions.

# Features

Disease Detection: Classifies UAV images as healthy or diseased based on Alternaria solani presence.

Explainable AI: Utilizes XAI tools like LIME or SHAP to visualize and explain predictions.

User Interface: An intuitive platform where users can upload images and get instant results.


# Project Workflow

Data Collection: High-resolution UAV images of potato crops were collected and labeled as healthy or diseased.

Model Development: A CNN was trained for binary classification of images, using techniques like data augmentation to improve accuracy.

Explainability: Integrated XAI tools to highlight features contributing to model predictions.

User Interface: Developed a web-based UI for seamless interaction, enabling farmers or agronomists to upload images and view results.

# Usage

Launch the application.

Upload a UAV image of a potato field.

View the prediction result (“Healthy” or “Diseased”) along with an explainability heatmap.

# Technologies Used

Deep Learning: Convolutional Neural Networks (CNN) implemented in TensorFlow/Keras.

Explainable AI: LIME for model interpretation.

Web Development: Streamlit for the user interface.

Programming Language: Python.

# Dataset

The dataset consists of UAV images of potato farms, labeled into two categories: healthy and diseased (Alternaria solani).

# Results

The model achieved an accuracy of 92% on the validation dataset and demonstrated robust performance in real-world scenarios.

![upload_page](https://github.com/user-attachments/assets/c5d7d540-659d-434f-9ab5-c6207ed0321f)


# Future Work

Expand dataset diversity for broader applicability.

Enhance UI for multi-language support.

Extend the model to detect multiple crop diseases.
