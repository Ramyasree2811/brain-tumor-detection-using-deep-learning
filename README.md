# 🧠 Brain Tumor Detection and Segmentation using Deep Learning

## 📌 Project Overview

This project implements an end-to-end deep learning pipeline for **brain tumor classification and MRI image segmentation**. The model uses **ResNet50** for brain MRI image classification and **ResUNet** for semantic segmentation to accurately identify tumor regions in MRI scans. The project demonstrates the application of transfer learning and medical image processing using TensorFlow and Keras.

---

## 🚀 Features

- Brain MRI image classification using **ResNet50**
- Brain tumor segmentation using **ResUNet**
- Image preprocessing and normalization
- Data augmentation for improved model generalization
- Tumor mask prediction and visualization
- Performance evaluation using segmentation metrics
- Training with custom **Focal Tversky Loss**

---

## 👩‍💻 Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-image
- Scikit-learn
- Google Colab

---

## 📊 Dataset

**Dataset:** LGG MRI Segmentation Dataset (Kaggle)

- Total MRI Images: **3,929**
- Training Images: **2,838**
- Validation Images: **501**
- Testing Images: **590**

Each MRI image has a corresponding ground truth tumor mask used for semantic segmentation.

---

## 🛠️ Project Workflow

1. Data Loading
2. Image Preprocessing
3. Exploratory Data Analysis (EDA)
4. Brain Tumor Classification using ResNet50
5. Brain Tumor Segmentation using ResUNet
6. Model Training using Focal Tversky Loss
7. Prediction and Visualization
8. Model Evaluation

---

## 📈 Deep Learning Techniques

- Transfer Learning
- ResNet50
- ResUNet
- Convolutional Neural Networks (CNN)
- Semantic Segmentation
- Medical Image Processing
- Data Augmentation
- Focal Tversky Loss
- Early Stopping
- Model Checkpointing

---

## 📂 Project Structure

```text
Brain-Tumor-Detection/
│── brainsegmentation.ipynb
│── README.md
│── requirements.txt
│── dataset/
│── ResUNet-MRI.json, resnet-50-MRI.json
│── results
│── resnetandresunet.ipynb
```

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/Ramyasree2811/brain-tumor-detection-using-deep-learning.git
```

Navigate to the project folder

```bash
cd brain-tumor-detection-using-deep-learning
```

Install the required dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open **Brain_Tumor_Segmentation.ipynb** and run all the cells.

---

## 📷 Results

The model predicts tumor regions from MRI scans and visualizes:

- Original MRI Image
- Ground Truth Mask
- Predicted Tumor Mask
- MRI Image with Predicted Tumor Overlay

---

## 💡 Future Enhancements

- Improve classification accuracy
- Deploy the model using Flask or Streamlit
- Train on larger MRI datasets
- Optimize the segmentation model for faster inference

---

## 📚 Learning Outcomes

Through this project, I gained hands-on experience in:

- Deep Learning
- Medical Image Processing
- Transfer Learning
- Semantic Segmentation
- TensorFlow & Keras
- Computer Vision
- Model Evaluation
- Data Preprocessing and Augmentation

---

## 👩‍💻 Author

Bandi Ramyasree

- GitHub: https://github.com/Ramyasree2811

---

## ⭐ If you found this project helpful, consider giving it a Star!
