# AgroGuard-Ghana-AI-Maize-Disease-Detection-System
AgroGuard Ghana is an AI-powered platform that detects maize leaf diseases using deep learning, provides management recommendations, and tracks disease trends across Ghana. As team lead, I contributed to project documentation, model training, and testing.

## Project Overview

AgroGuard Ghana is an AI-driven maize disease detection and regional surveillance platform developed to support early identification of maize leaf diseases and improve agricultural decision-making in Ghana.

The system uses deep learning to analyse images of maize leaves, provide disease diagnosis and management recommendations, and support regional monitoring of disease patterns through a surveillance dashboard.

Developed as a five-member team project at Takoradi Technical University, AgroGuard Ghana combines artificial intelligence, mobile technology, and agricultural surveillance to help bridge the gap between disease detection and timely intervention.

## Problem Statement

Maize farmers in Ghana often face challenges identifying crop diseases early due to limited access to agricultural extension services and timely expert assistance. Delayed diagnosis can contribute to disease spread, crop losses, and reduced productivity.

AgroGuard Ghana addresses this challenge by providing an accessible, technology-driven approach to maize disease identification and regional disease monitoring.

## Key Features

- **AI-Powered Disease Detection:** Analyses uploaded or captured maize leaf images to identify disease conditions.
- **Disease Classification:** Recognises Northern Leaf Blight, Gray Leaf Spot, Common Rust, Healthy Maize Leaves, and a Not Maize rejection category.
- **Management Recommendations:** Provides relevant disease management information based on diagnosis results.
- **Mobile-Responsive Application:** Allows farmers to access the platform through smartphone browsers.
- **Regional Surveillance Dashboard:** Visualises reported disease cases according to location, time, and disease type.
- **Disease Alerts:** Supports individual-level assistance and regional alerts to help agricultural extension officers identify areas requiring attention.
- **Diagnosis History:** Allows farmers to review previous submissions.

## AI Model and Approach

The project uses a MobileNetV2-based deep learning image classification model, implemented with TensorFlow/Keras.

The model development process involved:
- Image preprocessing and augmentation.
- Transfer learning and fine-tuning.
- Model training and validation.
- Performance evaluation using a held-out test dataset.
- TensorFlow Lite conversion with dynamic-range quantisation.
- Grad-CAM-based visual explainability.

## Model Performance

The trained classification model achieved an overall test accuracy of **94.82% across five classes**.

Usability evaluation involved 30 participants, recording task completion rates between 70% and 90%, with a mean System Usability Scale (SUS) score of 51.25.

These results demonstrate the project's potential as a proof of concept while identifying areas for further improvement, particularly image capture, dataset localisation, and usability.

## My Role and Contributions

As the **Team Lead**, my contributions included:
- Coordinating the team and supporting project activities.
- Contributing to the technical and project documentation.
- Participating in the development, training, and testing of the deep learning classification model.
- Supporting system evaluation and documentation of project findings.
- Contributing to project presentations and reporting.

Model training was undertaken jointly with another team member, while other members handled their respective backend, database, frontend, testing, and documentation responsibilities.

## Project Team

This project was developed by a five-member team at Takoradi Technical University under the supervision of **Mr. Kenneth Broni**.

## Future Improvements

- Expand the dataset with maize leaf images collected under real Ghanaian farming conditions.
- Improve disease classification, particularly between visually similar diseases.
- Enhance the image capture and upload experience.
- Extend field testing to additional maize-growing regions.
- Improve regional alert delivery, including the proposed SMS notification extension.

## Project Significance

AgroGuard Ghana demonstrates how artificial intelligence and digital technologies can contribute to agricultural innovation by supporting early crop disease detection, timely farmer assistance, and more informed regional disease monitoring.
