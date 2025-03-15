# Human Disease Detection Based on Color Change in Fingernail

## 📌 Overview

This project focuses on **automated disease detection based on fingernail color analysis** using **Convolutional Neural Networks (CNNs) with transfer learning**. Changes in nail color can indicate underlying medical conditions such as **hypoxia, jaundice, malnutrition, and cardiovascular diseases**. This study classifies nails into five categories:

- **Bluish Nail** (possible oxygen deficiency)
- **Healthy Nail** (normal)
- **Splinter Hemorrhage** (possible endocarditis)
- **White Nail** (potential kidney or liver disease)
- **Yellow Nail** (potential jaundice or fungal infection)

By leveraging **deep learning and image processing**, this project aims to provide a **non-invasive and accessible diagnostic tool** for early disease detection.

---

## 🚀 Features

- **Machine Learning-based Classification**: Uses CNNs, specifically **VGG16 with transfer learning**.
- **Image Processing & Augmentation**: Enhances the dataset using transformations like mirroring, rotation, and tilt.
- **Automated RGB Color Extraction**: Converts images into structured color data for classification.
- **Medical Relevance**: Helps in detecting early signs of **health conditions based on nail color**.

---

## 🏗 Project Structure

📂 Human-Disease-Detection-Nail-Color │── 📁 data/ # Dataset (Images & Augmented Images) │── 📁 models/ # Trained Model Files │── 📁 notebooks/ # Jupyter Notebooks for experiments │── 📁 src/ # Source code │ │── data_preprocessing.py # Preprocessing images & extracting RGB values │ │── train_model.py # CNN Model training script │ │── predict.py # Prediction script for new images │── 📄 requirements.txt # Dependencies & libraries │── 📄 README.md # Project documentation │── 📄 LICENSE # License for the project
