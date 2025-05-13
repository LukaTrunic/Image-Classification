# Pet Breed Image Classification using Deep Learning

This project is a deep learning-based image classification system developed for the **Computer Vision** final exam. It utilizes the Oxford-IIIT Pet Dataset to classify images of pets into their respective breeds. The model is built and trained using TensorFlow and Keras in a Jupyter Notebook environment.

## 📌 Problem Description

The task is to build a convolutional neural network that can identify and classify the breed of a pet (cat or dog) from an image. The challenge involves handling different classes, variable image sizes, and ensuring generalization across unseen data.

## ✅ Solution Overview

- **Dataset**: Oxford-IIIT Pet Dataset (37 classes)
- **Preprocessing**:
  - Image resizing
  - Normalization
  - Data augmentation
- **Model Architecture**:
  - TensorFlow & Keras
  - Convolutional layers
  - Batch normalization
  - Dense output layer with softmax activation
- **Training**:
  - Categorical Crossentropy loss
  - Adam optimizer
  - Accuracy as the evaluation metric

## 🧠 Libraries & Tools

- Python 3
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn
- OpenCV (optional, depending on implementation)

## 📊 Results

- The model achieves high accuracy on validation data after multiple epochs.
- Evaluation includes confusion matrix, classification report, and loss/accuracy curves.
- Visualizations of sample predictions are included in the notebook.

## 🛠 How to Run

1. Put the project in Google Drive and run it in google colab

3. Download the dataset:
   - The dataset link is available in `https://www.robots.ox.ac.uk/~vgg/data/pets/`
   - Download and extract the dataset to the working directory
   - Update the dataset path in the notebook if necessary

4. Run the notebook:
   - Execute all cells in sequence
   - The notebook will handle preprocessing, training, evaluation, and visualization

## 📝 Summary

This project demonstrates the successful implementation of a deep learning model for multi-class image classification using the Oxford-IIIT Pet Dataset. The use of modern neural network practices such as batch normalization, data augmentation, and performance visualization resulted in a robust model capable of generalizing well to unseen pet images.

## 📬 Author

Luka Trunić