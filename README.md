# 🫁 Lung Cancer Detection Using CNN

A deep learning-based image classification project that detects lung cancer from CT scan images using a Convolutional Neural Network (CNN). The model is trained to classify lung CT images into different categories, helping automate the early detection process.

## 📌 Overview

Early detection of lung cancer can significantly improve treatment outcomes. This project leverages CNNs to analyze CT scan images and classify them into predefined categories using TensorFlow and Keras.

## 🚀 Features

- Image classification using a Convolutional Neural Network (CNN)
- Image preprocessing and data augmentation
- Model training and validation
- Performance evaluation using accuracy and loss metrics
- Prediction on unseen CT scan images

## 🛠 Tech Stack

- Language: Python
- Libraries: TensorFlow, Keras, NumPy, Pandas, Matplotlib
- Platform: Kaggle Notebook

## 📂 Dataset

The project uses a publicly available Lung CT Scan dataset from Kaggle.

> Note: Download the dataset from Kaggle and place it in the appropriate directory before running the notebook.

## 📁 Project Structure

Lung-Cancer-Detection/
│── Lung_Cancer_Detection.ipynb
│── README.md

## ⚙️ Installation

1. Clone the repository:

git clone https://github.com/snehal04deshmukh/Lung-Cancer-Detection.git

2. Navigate to the project folder:

cd Lung-Cancer-Detection

3. Install the required libraries:

pip install tensorflow keras numpy pandas matplotlib

4. Open the notebook and run all cells.

## 📊 Model Workflow

- Load CT scan image dataset
- Preprocess and augment images
- Build the CNN model
- Train the model
- Evaluate model performance
- Predict lung cancer classes for new images

## 📈 Results

The CNN model successfully learns image features from CT scans and achieves strong classification performance on the validation dataset. Training and validation accuracy/loss curves are used to evaluate the model.
