# 🩺 TB Detection Using CNN

A Deep Learning-based system for detecting **Pulmonary Tuberculosis** from chest X-ray images using Convolutional Neural Networks (CNN). This project aims to assist medical professionals by automating the classification of X-ray images as **Normal** or **Tuberculosis-infected**, contributing to early diagnosis and treatment planning.

---

## 📂 Dataset

- **Name:** TB_Chest_Radiography_Database  
- **Source:** [Kaggle](https://www.kaggle.com/datasets)  
- **Classes:** `Normal` and `Tuberculosis`  
- **Format:** Grayscale chest X-ray images  
- **Image Size:** Resized to `128x128` pixels for model compatibility  

---

## 🛠️ Technologies Used

- 🐍 Python (Google Colab)
- 🧠 TensorFlow / Keras
- 🖼️ OpenCV (image processing)
- 📊 Matplotlib (visualizations)
- 🔢 NumPy (numerical operations)
- 📈 Scikit-learn (metrics & evaluation)

---

## 🧱 Model Architecture

- `Conv2D` → `ReLU` → `MaxPooling`
- 3 convolutional blocks with increasing filters
- `Flatten` → `Dense` → `Dropout`
- Final `Dense` layer with `Sigmoid` activation for binary classification

> Optimized using **Adam** optimizer and **Binary Crossentropy** loss.

---

## ⚙️ Training Configuration

- **Epochs:** 10  
- **Learning Rate:** 0.0001  
- **Optimizer:** Adam  
- **Loss Function:** Binary Crossentropy  
- **Data Augmentation:**  
  - Rotation  
  - Zoom  
  - Horizontal Flip  
  - Width & Height Shift  

---

## 📈 Model Performance

- ✅ **Accuracy:** ~94.05% on test data
- 🩻 Demonstrated ability to generalize features from TB and normal X-rays
- 📊 Visualization of training/validation metrics provided in the notebook

---

## 🚀 Usage

1. Clone this repository  
   ```bash
   git clone https://github.com/yourusername/tb-detection-cnn.git
