# 🫁 Pulmonary Tuberculosis Detection from Chest X-Rays

A Deep Learning-based system for classifying chest X-ray images as **Normal** or **Tuberculosis-infected** using Convolutional Neural Networks (CNNs).

---

## 📦 Dataset

- **TB_Chest_Radiography_Database**  
  Source: [Kaggle Dataset](https://www.kaggle.com/datasets/tawsifurrahman/tuberculosis-tb-chest-xray-dataset)

---

## 🚀 Getting Started

### ✅ Step-by-step Execution:

1. **Upload Dataset**
   - Upload the full dataset to your **Google Drive** for Colab access.

2. **Open the Notebook**
   - Launch the Jupyter notebook via **Google Colab**.

3. **Update Paths**
   - Modify the dataset file paths as per your Google Drive directory structure.

4. **Run the Notebook**
   - Execute the notebook **cell-by-cell** to:
     - Preprocess data
     - Build and train the CNN model
     - Evaluate the results

5. **Predict from Images**
   - Use either a **random image** from the dataset or upload your **custom image** for prediction.

> 🎯 **Tip:** You can adjust the prediction **threshold value** in the final sigmoid layer to fine-tune sensitivity or specificity.

---

## 🧠 Model Output

- ✅ Trained CNN model saved as:  
  `tb_detection_model128.h5`

- 📌 Prediction Output:
  - Classifies input image as **Normal** or **Tuberculosis**
  - Displays:
    - 🖼️ Input X-ray image
    - 📊 Predicted class label
    - 📈 Confidence score (probability)

---

## 🧪 Functional Testing

- 🧪 Random test images were selected to validate model performance.
- 🔄 Ensured end-to-end pipeline:
  - Data Loading → Preprocessing → Prediction → Output
- 🔐 Verified:
  - No I/O failures
  - No logic errors
  - Model integration stability

---

## 🧑‍💻 Contributor

### 👩‍💻 K Keerthi  
Final Year B.Tech – Computer Science and Engineering (AI & ML)  
Vel Tech University, Chennai  
🔍 Passionate about applying Deep Learning for medical diagnostics
