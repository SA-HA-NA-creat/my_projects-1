# Blood Group Detection Using Fingerprint

## Description

Blood Group Detection Using Fingerprint is a machine learning-based web application that predicts a person's blood group from a fingerprint image. The system uses a trained deep learning model to analyse fingerprint patterns and provide a predicted blood group.

## Features

- Upload fingerprint images
- Supports JPG, JPEG and PNG image formats
- Automatically validates uploaded images
- Preprocesses fingerprint images before prediction
- Uses a trained deep learning model
- Predicts the blood group based on the fingerprint image
- Displays the prediction result through a simple web interface

## Technologies Used

- Python
- Flask
- TensorFlow / Keras
- HTML
- CSS
- JavaScript
- Machine Learning

## Project Structure

```text
BloodPrintAI/
│
├── app.py
├── requirements.txt
├── models/
│   ├── blood_group_fingerprint_model.h5
│   └── label_map.json
│
├── templates/
│   └── index.html
│
├── static/
│   └── style.css
│
└── uploads/
