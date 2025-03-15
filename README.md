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

📂 Human-Disease-Detection-Nail-Color
│── 📁 data/                # Dataset (Images & Augmented Images)
│── 📁 models/              # Trained Model Files
│── 📁 notebooks/           # Jupyter Notebooks for experiments
│── 📁 src/                 # Source code
│    │── data_preprocessing.py   # Preprocessing images & extracting RGB values
│    │── train_model.py          # CNN Model training script
│    │── predict.py              # Prediction script for new images
│── 📄 requirements.txt     # Dependencies & libraries
│── 📄 README.md            # Project documentation
│── 📄 LICENSE              # License for the project


---

## 📊 Dataset & Preprocessing

- The dataset was sourced from **All India Institute of Medical Sciences (AIIMS)**.
- The dataset includes images categorized into the five disease classes.
- **Data Augmentation**: To enhance the dataset, images were transformed using **tilting, mirroring, and rotation**.
- **RGB Feature Extraction**: Each image was analyzed for its dominant color values (R, G, B) and saved in a structured format for classification.

---

## 🧠 Model Architecture

- **CNN-based Model**: Uses **VGG16** as the base model for feature extraction.
- **Pre-trained Weights**: Allows the model to achieve high accuracy even with limited training data.
- **Supervised Learning**: Uses RGB features to classify images into disease categories.

---

## 🔬 Results & Performance

- **Validation Accuracy**: **78.90%**
- **Class-wise Performance**:

| Class                  | Precision | Recall | F1-Score |
|------------------------|-----------|--------|----------|
| Bluish Nail           | 0.11      | 0.07   | 0.08     |
| Healthy               | 0.08      | 0.09   | 0.09     |
| Splinter Hemorrhage   | 0.22      | 0.14   | 0.17     |
| White Nail            | 0.32      | 0.45   | 0.37     |
| Yellow Nail           | 0.17      | 0.16   | 0.17     |

- The model **correctly classified a test image as White Nail with 99.94% confidence**.

---

## 🔧 Installation & Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/Human-Disease-Detection-Nail-Color.git
cd Human-Disease-Detection-Nail-Color
