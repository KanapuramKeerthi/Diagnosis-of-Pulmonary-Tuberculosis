**Diagnosis of Pulmonary Tuberculosis using Deep Learning**
This project focuses on the automated detection of Pulmonary Tuberculosis (TB) using a Convolutional Neural Network (CNN) model trained on chest X-ray images. The goal is to assist healthcare professionals in early and accurate diagnosis, improving patient outcomes and reducing manual screening time.

**Project Overview**
Tuberculosis is a potentially serious infectious disease that primarily affects the lungs. Traditional diagnosis through chest X-rays requires expert radiologists and can be subjective. This project leverages deep learning techniques to build a CNN model that classifies X-ray images into TB-positive or TB-negative categories.

**Dataset**
**Source:** Publicly available datasets containing labeled chest X-ray images.

**Classes:**

TB Positive

Normal (TB Negative)

**Model Architecture**
Model: Custom-built Convolutional Neural Network (CNN)

**Layers Used:**

Convolutional Layers
Max Pooling
Dropout for regularization
Fully Connected Dense Layers
Softmax / Sigmoid activation for final classification
Loss Function: Binary Crossentropy
Optimizer: Adam
Metrics: Accuracy, Precision, Recall

**Technologies Used**
Python
TensorFlow / Keras
NumPy, Matplotlib, Pandas (for data handling and visualization)
 Google Colab

 **Results**
Achieved high accuracy on validation data
Model was able to generalize well on unseen chest X-ray images
Visualization tools like confusion matrix and ROC curves were used to evaluate performance
