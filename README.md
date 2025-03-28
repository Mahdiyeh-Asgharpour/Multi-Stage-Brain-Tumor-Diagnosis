# 🧠 Multi-Stage Brain Tumor Diagnosis 🔬

This project focuses on the multi-stage diagnosis of brain tumors using deep learning models. The implementation is done in a Jupyter Notebook using Python.

## ✨ Features

- **📊 Data Preprocessing:** Conversion of MATLAB (`.mat`) data to `JPG` images and their normalization.
- **🏗 Deep Learning Modeling:** Utilization of CNN and transfer learning models.
- **📈 Model Evaluation:** Calculation of accuracy metrics, confusion matrix, and visualization of training and validation performance.
- **🛡 Overfitting Reduction:** Use of Dropout and data augmentation techniques.

## Algorithms Used

Several deep learning models have been explored in this project:

- **Convolutional Neural Networks (CNN):** For feature extraction and data classification.
- **Transfer Learning (like VGG16, ResNet50 and etc):** Pretrained models to enhance accuracy.

## 🚨 Overfitting Analysis

During model training, the issue of overfitting was assessed.

## ⚙ Requirements

To run this project, install the following dependencies:

```bash
pip install tensorflow keras numpy pandas matplotlib seaborn opencv-python scikit-learn albumentations scipy h5py pillow
